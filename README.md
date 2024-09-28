[![Tests](https://github.com/KO6FCH/scoop-ham/actions/workflows/ci.yml/badge.svg)](https://github.com/KO6FCH/scoop-ham/actions/workflows/ci.yml) [![Excavator](https://github.com/KO6FCH/scoop-ham/actions/workflows/excavator.yml/badge.svg)](https://github.com/KO6FCH/scoop-ham/actions/workflows/excavator.yml)
# A Big Ol' Bucket o' Scooped Ham! 🪣
📻Amateur radio applications for **[Scoop](https://scoop.sh/)**!
## If you already have Scoop
Here ya go, have fun! `scoop bucket add ham https://github.com/KO6FCH/scoop-ham`
## What is Scoop?
> Scoop installs programs you know and love, from the command line with a minimal amount of friction.  
🔗 https://scoop.sh/
## How do I?
### 1. Install Scoop
**Quoted from the [Scoop website](https://scoop.sh/):**  
Open a PowerShell terminal (version 5.1 or later) and from the `PS C:\>` prompt, run:
```pwsh
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
```
And if you don't already have it installed, you'll need `git`.
```pwsh
scoop install git
```
### 2. Add the scoop-ham bucket
```pwsh
scoop bucket add ham https://github.com/KO6FCH/scoop-ham
```
### 3. Install Programs
One at a time.
```pwsh
scoop install wsjtx
```
A bunch at once.
```pwsh
scoop install wsjtx gridtracker chirp
```
Something that has the same name as a program in another bucket.
```pwsh
scoop install ham/chirp
```
### 4. Update Programs
One at a time.
```pwsh
scoop update wsjtx
```
A bunch at once.
```pwsh
scoop update wsjtx chirp gridtracker
```
Everything.
```pwsh
scoop update *
```
## What programs?
|**Program**|**Status**|**Scoop Name**|**Install**|**Update**|
|:--|:-:|:-:|:--|:--|
|[CHIRP](https://chirpmyradio.com/)|:warning:|`chirp`|`scoop install ham/chirp`|`scoop update ham/chirp`|
|[WSJT-X](https://wsjt.sourceforge.io/wsjtx.html)|:warning:|`wsjtx`|`scoop install ham/wsjtx`|`scoop update ham/wsjtx`|
|[GridTracker](https://gridtracker.org)|:warning:|`gridtracker`|`scoop install ham/gridtracker`|`scoop update ham/gridtracker`|
|[JS8Call](http://js8call.com/)|:grey_question:|---|---|---|

<sup>💯 - Everyone's using it. It works. It updates. Hell yeah.</sup>  
<sup>✔️ - I use it regularly and it seems to work fine. It should be safe to download and update.</sup>  
<sup>⚠️ - User beware. This program is new to scoop-ham. It may not be up to date, you may lose settings between updates, etc.</sup>  
<sup>❔ - Todo, investigating feasibility.</sup>  
