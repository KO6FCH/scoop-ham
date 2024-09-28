[![Tests](https://github.com/KO6FCH/scoop-ham/actions/workflows/ci.yml/badge.svg)](https://github.com/KO6FCH/scoop-ham/actions/workflows/ci.yml) [![Excavator](https://github.com/KO6FCH/scoop-ham/actions/workflows/excavator.yml/badge.svg)](https://github.com/KO6FCH/scoop-ham/actions/workflows/excavator.yml)
# A Big Ol' Bucket o' Scooped Ham! 🪣
A **[Scoop](https://scoop.sh/)** bucket for amateur radio programs!
## If you already have Scoop
```pwsh
scoop bucket add ham https://github.com/KO6FCH/scoop-ham
```
There's a [list of supported programs below](#scoop-ham.list). Have fun!
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
## <a name="scoop-ham.list">What programs?</a>
|**Program**|**Status**|**Scoop Name**|**Install**|**Update**|
|:--|:-:|:-:|:--|:--|
|[CHIRP](https://chirpmyradio.com/)|:warning:|`chirp`|`scoop install ham/chirp`|`scoop update ham/chirp`|
|[WSJT-X](https://wsjt.sourceforge.io/wsjtx.html)|:warning:|`wsjtx`|`scoop install ham/wsjtx`|`scoop update ham/wsjtx`|
|[GridTracker](https://gridtracker.org)|:warning:|`gridtracker`|`scoop install ham/gridtracker`|`scoop update ham/gridtracker`|
|[JS8Call](http://js8call.com/)|:clock730:|---|||
|[EchoLink](https://www.echolink.org/)|:grey_question:|---|||
|[HAMRS](https://hamrs.app/)|:grey_question:|---|||
|[N1MM Logger](https://n1mmwp.hamdocs.com/)|:grey_question:|---|||
|[wfview](https://wfview.org/)|:grey_question:|---|||
|[fldigi](http://www.w1hkj.com/)|:grey_question:|---|||
|[CQSSTV](https://www.cqsstv.com/)|:grey_question:|---|||
|[SDR++](https://www.sdrpp.org/)|:grey_question:|---|||

<sup>💯- Fully tested and working. ✔️- Minimal testing but should work. ⚠️- New to **scoop-ham**. User beware. 🕢- In progress. ❔- Todo/considering.</sup>
