![](https://github.com/OdinProAgrica/DocumentationImages/blob/master/dapperLogo.png)

# dapper
Functions and macros that make HPCC easier and faster to code in. Currently broken down into transform tools for data transformation and string tools for standard string tidying. 

- [Documentation](#documentation)
- [Installation](#installation)
- [Transform Tools](#transform-tools)
  * [Data Transformations](#data-transformations)
  * [Duplicates](#duplicates)
  * [Column Transforms](#column-transforms)
  * [Filters](#filters)
  * [Arrangement](#arrangement)
  * [Outputs](#outputs)
  * [Summaries](#summaries)
- [String Tools](#string-tools)
  * [Regex Loop](#regex-loop)
- [Issues, Bugs, Comments? ](issues-bugs-comments)
    
## Documentation
The package's github is available at: https://github.com/OdinProAgrica/dapper

This package is released under GNU GPLv3 Licence: https://www.gnu.org/licenses/gpl-3.0.en.html

## Installation

### Option 1: bundles
From your commandline (provided you have clienttools installed and on your path) run: 
*ecl bundle info -v https://github.com/OdinProAgrica/dapper.git*
If you want a specific version use that version's branch, for details see the help in **ecl bundle install**.

### Option 2: Manual
Copy the dapper folder into an ECL repository (or add the folder to your IDE's environment), you can then import the relevant modules. You can get zips of each version in the releases section of the github: https://github.com/OdinProAgrica/dapper/releases

## Important Note!!!!!!!
**Do note that the standard nomenclature for importing the modules should be respected.** This is because each module references its own functions, requiring a known import name. Modules should always be imported as:

* TransformTools: tt
* StringTools: st

For example: 
IMPORT dapper.TransformTools as tt;

**inDS and OutDS are reserved** You may find you get weird errors if you use these variable names, this will be fixed in a later release

## Transform Tools

### Data Transformations
![](https://github.com/odinproagrica/DocumentationImages/blob/master/TransformTools/DataTransformations.PNG)

### Duplicates
![](https://github.com/odinproagrica/DocumentationImages/blob/master/TransformTools/DupsDedups.PNG)

### Column Transforms
![](https://github.com/odinproagrica/DocumentationImages/blob/master/TransformTools/Columns.PNG)

### Filters
![](https://github.com/odinproagrica/DocumentationImages/blob/master/TransformTools/Filters.PNG)

### Arrangement
![](https://github.com/odinproagrica/DocumentationImages/blob/master/TransformTools/Arrange.PNG)

### Outputs
![](https://github.com/odinproagrica/DocumentationImages/blob/master/TransformTools/Outputs.PNG)

### Summaries
![](https://github.com/odinproagrica/DocumentationImages/blob/master/TransformTools/Summaries.PNG)

## String Tools
![](https://github.com/odinproagrica/DocumentationImages/blob/master/StringTools/StringTools.PNG)

### Regex Loop
![](https://github.com/odinproagrica/DocumentationImages/blob/master/StringTools/RegexLoop.PNG)

## Issues Bugs Comments? 
Please use the package's github: https://github.com/OdinProAgrica/dapper

Any contributions are also welcome.
