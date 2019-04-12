# Climber Container
<a href="http://www.climberextensions.com/" class="image_link" target="_blank"><img src="./screenshots/downloadbutton.png?raw=true" alt="Download latest release" width="400" height="40" border="0" /></a>  

 > The Climber Container allows for multiple objects in a container and have possibility to change visualizations with a tab row. There is no limitiation to the number of tabs or the type of objects to include. It's like having sheets within sheets and the extension can be used as a navigation system within your Qlik Sense sheet. Some of the potential use cases are:  
 
***Tested from Qlik Sense June 2017 (in the initial release of June 2017, extensions load slow. It's fixed in patch 1 )***

<div style="page-break-after: always;"></div>   

## Most recent update 1.3.0 - 2019-03-12
### Added
- Support for February 2019
### Fixed
- CSS Memory leak bug chrome
- ES-11518 - Filterpane export to image/pdf/ppt

Full CHANGELOG can be found end of this file.

<div style="page-break-after: always;"></div>  

* Replacing the "Fast Change" functionality of QlikView.  
<img src="./screenshots/ContainerWithIcons.gif?raw=true" alt="Fast Change in Qlik Sense" />

* Simple menu system for different charts that you want to hide/show.  
<img src="./screenshots/ContainerWithIconsAndText.gif?raw=true" alt="Tab dropdown menu" />

* Drop down menu  
<img src="./screenshots/ContainerWithDropDown.gif?raw=true" alt="Tab dropdown menu" />

* Using container in container to create a hierarchy of charts.  
<img src="./screenshots/ContainerInContainer.gif?raw=true" alt="Container in container" />

Have you built something nice with our extensions? Screenshots and animated gifs of your work is always welcome.

<div style="page-break-after: always;"></div>  

## Getting started
1. Add your visualizations as master items
2. Add the master item to the extensions

<img src="./screenshots/ContainerSetup.gif?raw=true" alt="Container setup" />

<div style="page-break-after: always;"></div>  

## Settings and Features
**Tab positions**

There are five alternative tab placements:

<img src="./screenshots/ContainerTabPlacements.png?raw=true" alt="Tab placements" />


**Tab Size/Tab Text Size**

It's possible to change the size of the tab row with two options. Default and recommended size is medium for both settings. 

**Tab Text size**

| Options  	    | Description 	   |
| --- | --- |
| S  		  	| Small text size  |
| M 		  	| Medium text size |
| L  			| Large text size  |

<div style="page-break-after: always;"></div>  

**Tab Size**

| Options  	    | Description 	  |
| --- | --- |
| S  		  	| Small tab size  |
| M 		  	| Medium tab size |
| L  			| Large tab size  |

**Tab alignment**

The tabs can be aligned to the right, middle and to the left.

**Color options**

There are options for changing the color of the tab row background, the active tab/text and for the inactive tab/text. 

**Show underline**

Options for having the selected tab underlined

**Icon**

Option for only having a icon in the tab description or showing a icon before or after the text. 

**Sync tabs**

Option to sync multiple containers active tab. Tabs with same name will be synced

<img src="./screenshots/ContainerSyncTabs.gif?raw=true" alt="Sync tabs" />

<div style="page-break-after: always;"></div>  

**Other notes**

The extension is created as a generic solution to allow for many different use cases. For instance the tab labels allow an expression so it is possible to create more dynamic solutions and we allow containers to be placed inside containers. However, we still want the solution to be user friendly so we have not exposed more technical options like the ability to assign object id with an expression. We have also kept close to the Qlik Sense design and do not allow for specific font-sizes (in pixels) to retain the possiblities for responsive design. Please have these considerations in mind when/if you suggest improvements to the extension.

<div style="page-break-after: always;"></div>  

## Container +

The Container + version has more functionality then the basic version

* Action on click
	- Clear selections in field
	- Select value in field
	- Select values in field
	- Set a variable

* Use expression to activate a tab
	- When the expression evaluates to the tab name the tab will be active
	
* Hide tab bar
	- Hide the tab bar and use the expression option to activate a tab

Visit www.climber.eu for more information
<div style="page-break-after: always;"></div>  

## Installation

1. Download the latest version
2. Qlik Sense Desktop
	* To install, copy all files in the .zip file to folder "C:\Users\\%Username%\Documents\Qlik\Sense\Extensions\cl-container"
3. Qlik Sense Server
	* See instructions <a href="http://help.qlik.com/en-US/sense/3.2/Subsystems/ManagementConsole/Content/import-extensions.htm"> how to import an extension on Qlik Sense Server </a>  

## Limitations
1. No pdf/png export supported. (This also means no Nprinting support)
2. Export to image/pdf/ppt for Filterpanes is not supported. (Limitation with QS)

## Recommended Versions
Qlik Sense Version | Recommended
------------- | -------------
February 2019|*1.3.0*
November 2018|*1.3.0*
September 2018|*1.3.0*
June 2018|*1.3.0*
April 2018|*1.3.0*
February 2018|*1.3.0*
November 2017|*1.3.0*
September 2017|*1.3.0*
June 2017|*1.3.0*


<div style="page-break-after: always;"></div>  


## More Climber Extensions
Like this extension? Check out the other Climber made extensions below or contact us to let us build your own extension.

**Custom Report**  
<a href="http://www.youtube.com/watch?feature=player_embedded&v=mCb2t4aNppE
" target="_blank" class="image_link"><img src="http://img.youtube.com/vi/mCb2t4aNppE/0.jpg" 
alt="Climber Custom Report Video" width="240" height="180" border="2" /></a>
* https://github.com/ClimberAB/ClimberCustomReport
* https://www.youtube.com/watch?v=mCb2t4aNppE  


**Selection Bar**  
<a href="http://www.youtube.com/watch?feature=player_embedded&v=4fxrphADRKw
" target="_blank" class="image_link"><img src="http://img.youtube.com/vi/4fxrphADRKw/0.jpg" 
alt="Climber Custom Report Video" width="240" height="180" border="2" /></a>
* https://github.com/ClimberAB/ClimberSelectionBar
* https://www.youtube.com/watch?v=4fxrphADRKw  


**KPI**  
<a href="http://www.youtube.com/watch?feature=player_embedded&v=9zdfYshNel4
" target="_blank" class="image_link" ><img src="http://img.youtube.com/vi/9zdfYshNel4/0.jpg" 
alt="Climber Custom Report Video" width="240" height="180" border="2" /></a>
* https://github.com/ClimberAB/ClimberKPI
* https://www.youtube.com/watch?v=9zdfYshNel4  


**Cards**  
<a href="http://www.youtube.com/watch?feature=player_embedded&v=k_IEt8TvB_c
" target="_blank" class="image_link" ><img src="http://img.youtube.com/vi/k_IEt8TvB_c/0.jpg" 
alt="Climber Custom Report Video" width="240" height="180" border="2" /></a>
* https://github.com/ClimberAB/ClimberCards
* https://www.youtube.com/watch?v=k_IEt8TvB_c  

<div style="page-break-after: always;"></div>   

## Change Log
## 1.3.0 - 2019-03-12 
### Added
- Support for February 2019
### Fixed
- CSS Memory leak bug chrome
- ES-11518 - Filterpane export to image/pdf/ppt 
 
## 1.2.0 - 2018-12-03 
### Added
- Support for November 2018
- Bundle information
### Added (Plus-version)
- Export to image/pdf/ppt
- Snapshot
### Fixed
- Alternative state tab in property panel November 2018 and later 
 
## 1.1.2 - 2018-09-21 
### Changed
### Fixed
- Fixed #15 Export in IE 
 
## 1.1.1 - 2018-08-21 
### Changed
- Rebuilt export functionality
### Fixed
- Fixed #8 Export from Single API web page 
 
## 1.1.0 - 2018-06-21 
### Fixed
- Works with QS June 2018
- Improved performance.
- Improved performance container in container.
- Climber Custom Report multiple data sets bug. 
 
## 1.0.5 - 2018-03-28 
### Changed
- Updated export function 
 
## 1.0.4 - 2018-03-28 
### Changed
- Build problem 
 
## 1.0.3 - 2018-03-23 
### Changed
- Font style bug
- White text if you have calculated background (default) 
 
## 1.0.2 - 2018-03-19 
### Changed
- CSS class name to avoid problem with other frameworks 
 
## 1.0.1 - 2018-03-06 
### Changed
- Align dropdown fix for internet explorer 
 
## 1.0.0 - 2018-02-28 
* Initial Release 
 
## 1.3.0 - 2019-03-12 
### Added
- Support for February 2019
### Fixed
- CSS Memory leak bug chrome
- ES-11518 - Filterpane export to image/pdf/ppt 
 
## 1.2.0 - 2018-12-03 
### Added
- Support for November 2018
- Bundle information
### Added (Plus-version)
- Export to image/pdf/ppt
- Snapshot
### Fixed
- Alternative state tab in property panel November 2018 and later 
 
## 1.1.2 - 2018-09-21 
### Changed
### Fixed
- Fixed #15 Export in IE 
 
## 1.1.1 - 2018-08-21 
### Changed
- Rebuilt export functionality
### Fixed
- Fixed #8 Export from Single API web page 
 
## 1.1.0 - 2018-06-21 
### Fixed
- Works with QS June 2018
- Improved performance.
- Improved performance container in container.
- Climber Custom Report multiple data sets bug. 
 
## 1.0.5 - 2018-03-28 
### Changed
- Updated export function 
 
## 1.0.4 - 2018-03-28 
### Changed
- Build problem 
 
## 1.0.3 - 2018-03-23 
### Changed
- Font style bug
- White text if you have calculated background (default) 
 
## 1.0.2 - 2018-03-19 
### Changed
- CSS class name to avoid problem with other frameworks 
 
## 1.0.1 - 2018-03-06 
### Changed
- Align dropdown fix for internet explorer 
 
## 1.0.0 - 2018-02-28 
* Initial Release 
 


## License

See <a href="License.pdf"> LICENSE </a>

