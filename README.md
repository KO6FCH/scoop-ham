[![Tests](https://github.com/KO6FCH/scoop-ham/actions/workflows/ci.yml/badge.svg)](https://github.com/KO6FCH/scoop-ham/actions/workflows/ci.yml) [![Excavator](https://github.com/KO6FCH/scoop-ham/actions/workflows/excavator.yml/badge.svg)](https://github.com/KO6FCH/scoop-ham/actions/workflows/excavator.yml) ![GitHub Repo Size](https://img.shields.io/github/repo-size/KO6FCH/scoop-ham?style=flat&logo=bookmeter&logoColor=959da5)


# A Big Ol' Bucket o' Scooped Ham!
A **[Scoop](https://scoop.sh/)** bucket for amateur radio programs!
## If you already have Scoop
```pwsh
scoop bucket add ham https://github.com/KO6FCH/scoop-ham
```
There's a [list of supported programs below](#scoop-ham.programs). Have fun!
## What is Scoop?
> Scoop installs programs you know and love, from the command line with a minimal amount of friction.

<sup>:link: https://scoop.sh/</sup>
## How do I?
### Install Scoop
> Open a PowerShell terminal (version 5.1 or later) and from the PS C:\> prompt, run:
> ```pwsh
> Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
> Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
> ```
<sup>:link: https://scoop.sh/</sup>
### Add the **scoop-ham** bucket
If you don't already have `git` installed.
```pwsh
scoop install git
```
Then, add the bucket.
```pwsh
scoop bucket add ham https://github.com/KO6FCH/scoop-ham
```
### Install Programs
```pwsh
scoop install chirp
```
> [!TIP]
> You can install multiple programs at the same time!
>
> `scoop install chirp wsjtx gridtracker`

### Update Programs
```pwsh
scoop update chirp
```
Or update everything!
```pwsh
scoop update *
```
> [!IMPORTANT]
> You should decline updates from your programs. Instead, let Scoop manage the updates.
## <a name="scoop-ham.programs">What programs?</a>
|**Program**|**Scoop Name**|**Notes**|
|:--|:-:|:--|
|[CHIRP-next](https://chirpmyradio.com/)|`chirp`|64-bit only. Use `chirp-legacy` for 32-bit.|
|[CHIRP-legacy](https://chirpmyradio.com/)|`chirp-legacy`||
|[EchoLink](https://www.echolink.org/)|`echolink`|Installer URL may change between versions.|
|[flamp](http://www.w1hkj.com/)|`flamp`||
|[fldigi](http://www.w1hkj.com/)|`fldigi`|Includes `flarq`.|
|[flrig](http://www.w1hkj.com/)|`flrig`||
|[GridTracker](https://gridtracker.org)|`gridtracker`||
|[HAMRS](https://hamrs.app/)|`hamrs`||
|[JS8Call](http://js8call.com/)|`js8call`||
|[NanoVNA Saver](https://github.com/NanoVNA-Saver/nanovna-saver)|`nanovnasaver`||
|[NetTime](https://www.timesynctool.com/)|`nettime`||
|[QLog](https://github.com/foldynl/QLog/releases/tag/v0.41.1)|`qlog-np`||
|[SatDump](https://www.satdump.org/)|`satdump`||
|[WSJT-X](https://wsjt.sourceforge.io/wsjtx.html)|`wsjtx`|Might conflict with `wsjtx-rc`.|
|[WSJT-Z](https://sourceforge.net/projects/wsjt-z/)|`wsjtz`||
|[WSJT-X Release Candidate](https://wsjt.sourceforge.io/wsjtx.html)|`wsjtx-rc`|Might conflict with `wsjtx`.|
