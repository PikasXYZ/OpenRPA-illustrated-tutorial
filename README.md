# ![OpenRPA](OpenRPA-logo.png)OpenRPA Illustrated Tutorial (Work In Process)
This Repo. is forked from [open-rpa/openrpa](https://github.com/open-rpa/openrpa), containing illustrated tutorial of Open Source Robotic Process Automation Software (OpenRPA).
Basic concept is right below this README, and tutorials of tool usage are in the folder "Tool Usage". There're also some little project as example in the folder "Pikas' Side Project".

[![GitHub forks](https://img.shields.io/github/forks/open-rpa/openrpa.svg)](https://github.com/open-rpa/openrpa/network) 
[![GitHub license](https://img.shields.io/github/license/open-rpa/openrpa.svg)](https://github.com/open-rpa/openrpa/blob/master/LICENSE)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/open-rpa/openrpa/graphs/commit-activity)

Download and try OpenRPA here [💾here](https://github.com/open-rpa/openrpa/releases/latest/download/OpenRPA.msi)

## Basic Concept

### Workflow
  `Workflow` is an execution file in OpenRPA, which can be shared by exporting to json file.

### Project
  `Project` is the container of wolkflows, just like folders in Windows & macOS.

### Sequence


### Cancel Key
   When the computer loses control due to the bad design of a workflow, the key to stop excuting it forcefully is called "Cancel Key", which can be edit in Settings (default is ESC key). 

### Variable Declaration

### Common Variable Type

- #### String
  String means **words**, supposed to be framed by 2 double quotes (e.g. `"Hello World"`).  Multiple strings can be merged by operator `+` (e.g. `"Hello" + " World"`). Double quotes of a string aren't used or displayed while excuting, their exsistence is just for letting computers know  **it's a string.**. Therefore, the result of `"Hello" + " World"` isn't `Hello"" World` but `Hello World`. When putting double quotes which are goning to be used, escape characters `\` must be put before (e.g. `"Hello \"Tom\""`). BTW, some variable types can be convert into string by certain methods like `.ToString` or `Convert.ToString()` (e.g. `100.ToString`).
  
- #### Int16/Int32/Int64
  `Int` is a fundamental variable type that stands for **integer**, which means it can store number. Besides, it's signed, so it can represent both positive and negative values. 
  
- #### Boolean
  `Boolean` is a fundamental variable type that represents a binary value, which has two possible states: `True` or `False`. They are usually used to express the outcome of logical comparisons and decisions within a program. To toggle a boolean variable, `not` should be add before (e.g. `not isChecked`). 

- #### NMElement/IEElement
  In the context of web development, `Element` refer to the building blocks or components that make up a web page's structure and content. They're defined by HTML (Hypertext Markup Language) and also the fundamental components that browsers use to interpret and display web pages. In OpenRPA, they can be get by the tool `Get Element` as a local variable `item`, which has a lot of useful properties and method (e.g. `item.Weight`, `item.Height`, `item.Value`...etc.)

### Logic Operators


   

