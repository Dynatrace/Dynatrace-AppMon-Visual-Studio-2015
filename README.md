<img src="/img/logo/visual-studio.png" width="300" />

# Dynatrace Visual Studio 2015 Extension

The Dynatrace Visual Studio Extension enable you to:
* launch applications with an injected Dynatrace Agent directly from Visual Studio
* perform look-ups of sources files and methods from applications under diagnosis in Dynatrace Application Monitoring

#### Table of Contents

* [Installation](#installation)  
 * [Prerequisites](#prerequisites)  
 * [Manual Installation](#manual)
* [Configuration](#configuration)
* [Use the Visual Studio Extension](#use)
 * [Launcher](#launcher)
 * [Source Code Look-up](#source_code)
*  [Problems? Questions? Suggestions?](#feedback)


<a name="installation"/>
## Installation

<a name="prerequisites"/>
### Prerequisites

* Dynatrace Application Monitoring Version: 6.1, 6.2, 6.3
* Visual Studio Version: 2015 (all editions supported)

Find further information in the [Dynatrace community](https://community.dynatrace.com/community/display/DL/Visual+Studio+2015+Extension).

<a name="manual"/>
### Manual Installation

* Download the plugin from the [Dynatrace community](https://community.dynatrace.com/community/display/DL/Visual+Studio+2015+Extension)
* Double-click on the VSIX file
* Follow the steps displayed by the Visual Studio Extension Installer
* Restart Visual Studio

<a name="configuration"/>
## Configuration

![configuration](/img/conf/configuration_1.png) 

![configuration](/img/conf/configuration_2.png) 

<a name="use"/>
## Use the Visual Studio Extension

<a name="launcher"/>
### Launcher

The lancher will run applications with an injected Dynatrace Agent using the agent name and additional parameters defined in the run configuration:

![edit run configurations](/img/use/launcher.png) 

The launcher support the following launch mode:
* ...

The agent will output debug information into the console:

![edit run configurations](/img/use/launcher_console.png) 


<a name="source_code"/>
### Source Code Look-up

The Dynatrace Client enables you to analyze PurePaths down to the individual methods that have been instrumented in the context of the captured transaction. When you identify a problematic method either in the PurePath view or in the Methods view of the Dynatrace Client, you can use the Source Code Lookup to jump to the source code line if you have the Eclipse project open.

![edit run configurations](/img/use/source_lookup.png) 

<a name="feedback"/>
## Problems? Questions? Suggestions?

* [Visual Studio Extension FAQ / Troubleshooting Guide](FAQ.md)
* Post any problems, questions or suggestions to the Dynatrace Community's [Application Monitoring & UEM Forum](https://answers.dynatrace.com/spaces/146/index.html).
