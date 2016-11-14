<img src="/img/logo/visual-studio.png" width="300" />

# Dynatrace Visual Studio 2015 Extension

The Dynatrace Visual Studio Extension enable you to launch applications with an injected Dynatrace Agent directly from Visual Studio
and perform look-ups of sources files and methods from applications under diagnosis in Dynatrace Application Monitoring.

* Download latest the latest version form the [Visual Studio Gallery](https://visualstudiogallery.msdn.microsoft.com/c13bca24-29d2-42a4-a91c-bdbc9cae7b09)
* The Visual Studio Extension on the [Dynatrace Community](https://community.dynatrace.com/community/display/DL/Visual+Studio+2015+Extension)

#### Table of Contents

* [Installation](#installation)  
 * [Prerequisites](#prerequisites)  
 * [Installation](#installation)
* [Configuration](#configuration)
* [Use the Visual Studio Extension](#use)
 * [Launcher](#launcher)
 * [Source Code Look-up](#source_code)
*  [Problems? Questions? Suggestions?](#feedback)


<a name="installation"/>
## Installation

<a name="prerequisites"/>
### Prerequisites

* Dynatrace Application Monitoring Version: 6.3 and above
* Visual Studio Version: 2015 (all editions supported)

Find further information in the [Dynatrace community](https://community.dynatrace.com/community/display/DL/Dynatrace+AppMon+Visual+Studio+Extension)

<a name="installation"/>
### Installation

* In Visual Studio open Tools -> Extensions and Updates...
* Select "Online" and use the "Search Visual Studion Gallery" search box
* Search for Dynatrace AppMon and follow the instructions to install the extension

<a name="configuration"/>
## Configuration

The settings for the extension are located under Tools / Dynatrace AppMon Extension Configuration:

![configuration](/img/conf/configuration_1.png) 

Configuration screen:

![configuration](/img/conf/configuration_2.jpg) 

<a name="use"/>
## Use the Visual Studio Extension

<a name="launcher"/>
### Launcher

The lancher will run applications with an injected Dynatrace Agent using the agent name and additional parameters defined in the run configuration. The agent will output debug information into the console.

![edit run configurations](/img/use/launcher.png) 


The launcher supports Windows and Web based project; Test projects are not yet supported.


<a name="source_code"/>
### Source Code Look-up

The Dynatrace Client enables you to analyze PurePaths down to the individual methods that have been instrumented in the context of the captured transaction. When you identify a problematic method either in the PurePath view or in the Methods view of the Dynatrace Client, you can use the Source Code Lookup to jump to the source code line if you have the Visual Studio solution open.

![edit run configurations](/img/use/source_code_lookup.png) 

<a name="feedback"/>
## Problems? Questions? Suggestions?

* [Visual Studio Extension FAQ / Troubleshooting Guide](FAQ.md)
* Post any problems, questions or suggestions to the Dynatrace Community's [Application Monitoring & UEM Forum](https://answers.dynatrace.com/spaces/146/index.html).
