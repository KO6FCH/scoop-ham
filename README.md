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
<sub>:100:- Fully tested and working. :heavy_check_mark:- Minimal testing but should work. :warning:- New to **scoop-ham**. User beware. :clock730:- In progress. :grey_question:- Todo/considering.</sub>
|**Program**|**Status**|**Scoop Name**|**Install**|**Notes**|
|:--|:-:|:-:|:-:|:-:|
|[CHIRP-next](https://chirpmyradio.com/)|:warning:|`chirp`|`scoop install chirp`||
|[WSJT-X](https://wsjt.sourceforge.io/wsjtx.html)|:warning:|`wsjtx`|`scoop install wsjtx`|may conflict with `wsjtx-rc`|
|[GridTracker](https://gridtracker.org)|:warning:|`gridtracker`|`scoop install gridtracker`||
|[JS8Call](http://js8call.com/)|:warning:|`js8call`|`scoop install js8call`||
|[WSJT-X RC](https://wsjt.sourceforge.io/wsjtx.html)|:warning:|`wsjtx-rc`|`scoop install wsjtx-rc`|may conflict with `wsjtx`|
|[CHIRP-legacy](https://chirpmyradio.com/)|:clock730:|---|||
|[EchoLink](https://www.echolink.org/)|:grey_question:|---|||
|[HAMRS](https://hamrs.app/)|:grey_question:|---|||
|[N1MM Logger+](https://n1mmwp.hamdocs.com/)|:grey_question:|---|||
|[wfview](https://wfview.org/)|:grey_question:|---|||
|[fldigi](http://www.w1hkj.com/)|:grey_question:|---|||
|[CQSSTV](https://www.cqsstv.com/)|:grey_question:|---|||
|[SDR++](https://www.sdrpp.org/)|:grey_question:|---|||
|[NetTime](https://www.timesynctool.com/)|:grey_question:|---|||

<sup>:100:- Fully tested and working. :heavy_check_mark:- Minimal testing but should work. :warning:- New to **scoop-ham**. User beware. :clock730:- In progress. :grey_question:- Todo/considering.</sup>
