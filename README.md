<img src="https://user-images.githubusercontent.com/134798/98393425-40541e00-2027-11eb-9412-3247cc1b5072.png" height="175">

![iOS](https://img.shields.io/badge/iOS-10%20-blue)
![macOS](https://img.shields.io/badge/macOS-10.15-blue)
![Swift](https://img.shields.io/badge/Swift-5-orange?logo=Swift&logoColor=white)
[![Gitter](https://badges.gitter.im/CoronaTrackerApp/community.svg)](https://gitter.im/CoronaTrackerApp/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
<a href="https://twitter.com/intent/follow?screen_name=Hejazi"><img src="https://img.shields.io/badge/@hejazi-x?color=08a0e9&logo=twitter&logoColor=white" /></a>

![image](https://user-images.githubusercontent.com/121827/77246699-e25efb80-6c3a-11ea-8a49-30bd87ff33c0.png)

## Features
* __Live data__: Shows the most recent data, and updates automatically.
* __Distribution map__ with two levels of details:
  * __Countries__: When the user zooms out. Fewer details and reduced clutter.
  * __Cities__: When the user zooms in. More details.
* __Charts__:
   * __Current state chart__ for all countries (and cities).
   * __Timeline chart__ for all countries (and cities).
   * __Top affected countries__ chart with info about every country.
   * __Daily new cases__ shows how fast the virus is spreading in a given country.
   * __Cases since the 100th case__ how fast the virus is spreading in different countries.
   * Option for using a __logarithmic__ scale.
* __Search__ for countries & cities.
* __Share__ stats & charts as images.
* __Today widget__ for worldwide stats (Contributed by [Piotr Ożóg](https://github.com/pbeo)).
* __Red color scale__: Reflects the number of confirmed cases. In addition to increasing circle size.
* __Statistics__: Including the number of confirmed, recovered, and deaths, in addition to percents.
* __iPad__ & __macOS__ support.

![image](https://user-images.githubusercontent.com/121827/77246980-a6796580-6c3d-11ea-80dd-57833a7c386a.png)
![image](https://user-images.githubusercontent.com/121827/77247007-03751b80-6c3e-11ea-91fc-b3d535fda6a2.png)

## How to Use
### 1. iOS & macOS App
#### Build from source code
1. Clone/Download the repo.
2. Open `Corona.xcodeproj` in Xcode.
3. Choose the right target (iOS or macOS).
4. Build & run!

### 2. macOS App
[Download the latest release](https://github.com/rbottoms/SpatialReality/releases/latest) for macOS.

Or install via [brew](http://brew.sh):

  ```bash
  brew cask install spatialreality
  ```

## Fork Info
Forked code from Mhd Hejazi's brilliant CoronaTracker https://github.com/mhdhejazi/CoronaTracker

## Author
Richard Bottoms <a href="https://twitter.com/intent/follow?screen_name=rbottoms"><img src="https://img.shields.io/badge/@hejazi-x?color=08a0e9&logo=twitter&logoColor=white" valign="middle" /></a> (contact@intelligentmessenger.com)

## Credits
### Temp Data
Data is provided by JHU CSSE (https://github.com/CSSEGISandData/COVID-19).

### Translations


### Libraries
* [CSV.swift](https://github.com/yaslab/CSV.swift): For parsing the CSV data file.
* [Charts](https://github.com/danielgindi/Charts): Beautiful and powerful charts.
* [FloatingPanel](https://github.com/SCENEE/FloatingPanel): For the bottom sheet.
* [Disk](https://github.com/saoudrizwan/Disk): Simplifies loading/saving files.
