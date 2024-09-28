# A Big Ol' Bucket o' Scooped Ham!
[![Tests](https://github.com/KO6FCH/scoop-ham/actions/workflows/ci.yml/badge.svg)](https://github.com/KO6FCH/scoop-ham/actions/workflows/ci.yml) [![Excavator](https://github.com/KO6FCH/scoop-ham/actions/workflows/excavator.yml/badge.svg)](https://github.com/KO6FCH/scoop-ham/actions/workflows/excavator.yml)
## How do I?
### 1. Install Scoop
]https://scoop.sh/
### 2. Add Ham
```pwsh
scoop bucket add ham https://github.com/KO6FCH/scoop-ham
```
### 3. Install Programs
#### One at a time.
```pwsh
scoop install wsjtx
```
#### A bunch at once.
```pwsh
scoop install wsjtx gridtracker chirp
```
#### Something that conflicts with another bucket.
```pwsh
scoop install ham/chirp
```
## What programs?

|**Program**|**Tested**|**By Other People**|**Auto Update**|
|:--|:-:|:-:|:-:|
|CHIRP|:heavy_check_mark:|:x:|:heavy_check_mark:|
|WSJT-X|:heavy_check_mark:|:x:|:heavy_check_mark:|
|GridTracker|:heavy_check_mark:|:x:|:x:|

## What next?

|**Program**|**Status**|
|:--|:-:|
|?|?|
