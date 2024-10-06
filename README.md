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
> [!TIP]
> Update all Scoop programs with `scoop update *`

## <a name="scoop-ham.programs">What programs?</a>
<sub>:100:- Fully tested and working. :heavy_check_mark:- Minimal testing but should work. :warning:- Newly added. User beware. :clock730:- In progress. :grey_question:- To Do/Considering.</sub>
|**Program**|**Status**|**Scoop Name**|**Notes**|
|:--|:-:|:-:|:--|
|[CHIRP-next](https://chirpmyradio.com/)|:warning:|`chirp`|64-bit only. Use `chirp-legacy` for 32-bit.|
|[CHIRP-legacy](https://chirpmyradio.com/)|:warning:|`chirp-legacy`||
|[GridTracker](https://gridtracker.org)|:warning:|`gridtracker`||
|[JS8Call](http://js8call.com/)|:warning:|`js8call`||
|[WSJT-X](https://wsjt.sourceforge.io/wsjtx.html)|:warning:|`wsjtx`|Might conflict with `wsjtx-rc`.|
|[WSJT-X Release Candidate](https://wsjt.sourceforge.io/wsjtx.html)|:warning:|`wsjtx-rc`|Might conflict with `wsjtx`.|
|[N1MM Logger+](https://n1mmwp.hamdocs.com/)|:clock730:|---|This will take some time to figure out.|
|[NetTime](https://www.timesynctool.com/)|:clock730:|---||
|[CQSSTV](https://www.cqsstv.com/)|:grey_question:|---||
|[EchoLink](https://www.echolink.org/)|:grey_question:|---||
|[EZNEC Pro+](https://www.eznec.com/)|:grey_question:|---||
|[fldigi](http://www.w1hkj.com/)|:grey_question:|---||
|[HAMRS](https://hamrs.app/)|:grey_question:|---||
|[SDR++](https://www.sdrpp.org/)|:grey_question:|---||
|[SatDump](https://www.satdump.org/)|:grey_question:|---||
|[wfview](https://wfview.org/)|:grey_question:|---||

<sup>:100:- Fully tested and working. :heavy_check_mark:- Minimal testing but should work. :warning:- Newly added. User beware. :clock730:- In progress. :grey_question:- To Do/Considering.</sup>
<hr/>
<sub>TODO: Add the topic 'scoop-bucket' to the repo to be indexed on https://scoop.sh.</sub>
