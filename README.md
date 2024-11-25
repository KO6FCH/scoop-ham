[![Tests](https://github.com/KO6FCH/scoop-ham/actions/workflows/ci.yml/badge.svg)](https://github.com/KO6FCH/scoop-ham/actions/workflows/ci.yml) [![Excavator](https://github.com/KO6FCH/scoop-ham/actions/workflows/excavator.yml/badge.svg)](https://github.com/KO6FCH/scoop-ham/actions/workflows/excavator.yml)
# A Big Ol' Bucket o' Scooped Ham! 🪣
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
<sub>:100:- Fully tested and working. :heavy_check_mark:- Minimal testing but should work. :warning:- Newly added. User beware. :clock730:- In progress. :grey_question:- To Do/Considering.</sub>
|**Program**|**Status**|**Scoop Name**|**Notes**|
|:--|:-:|:-:|:--|
|[CHIRP-next](https://chirpmyradio.com/)|:heavy_check_mark:|`chirp`|64-bit only. Use `chirp-legacy` for 32-bit.|
|[GridTracker](https://gridtracker.org)|:heavy_check_mark:|`gridtracker`||
|[WSJT-X](https://wsjt.sourceforge.io/wsjtx.html)|:heavy_check_mark:|`wsjtx`|Might conflict with `wsjtx-rc`.|
|[CHIRP-legacy](https://chirpmyradio.com/)|:warning:|`chirp-legacy`||
|[flamp](http://www.w1hkj.com/)|:warning:|`flamp`||
|[fldigi](http://www.w1hkj.com/)|:warning:|`fldigi`|Includes `flarq`.|
|[flrig](http://www.w1hkj.com/)|:warning:|`flrig`||
|[HAMRS](https://hamrs.app/)|:warning:|`hamrs`||
|[JS8Call](http://js8call.com/)|:warning:|`js8call`||
|[NanoVNA Saver](https://github.com/NanoVNA-Saver/nanovna-saver)|:warning:|`nanovnasaver`||
|[NetTime](https://www.timesynctool.com/)|:warning:|`nettime`||
|[SatDump](https://www.satdump.org/)|:warning:|`satdump`||
|[WSJT-X Release Candidate](https://wsjt.sourceforge.io/wsjtx.html)|:warning:|`wsjtx-rc`|Might conflict with `wsjtx`.|
|[N1MM Logger+](https://n1mmwp.hamdocs.com/)|:clock730:|---|This will take some time to figure out.|
|[CQSSTV](https://www.cqsstv.com/)|:grey_question:|---||
|[EchoLink](https://www.echolink.org/)|:grey_question:|---|Installer URL may change between versions.|
|[EZNEC Pro+](https://www.eznec.com/)|:grey_question:|---||
|[SDR++](https://www.sdrpp.org/)|:grey_question:|---||
|[wfview](https://wfview.org/)|:grey_question:|---|Installer URL may change between versions.|

<sup>:100:- Fully tested and working. :heavy_check_mark:- Minimal testing but should work. :warning:- Newly added. User beware. :clock730:- In progress. :grey_question:- To Do/Considering.</sup>
