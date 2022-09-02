# Oracle OA Framework (OAF) Guidelines

<br>

- OA Framework File Contents Standards Guidelines
- OA Framework Model Standards Guidelines
- OA Framework View Standards Guidelines
- OA Framework Controller Standards Guidelines
- OA Framework Java Guidelines
- OA Framework Deployment Standards Guidelines

<br>

## OA Framework File Contents Standards Guidelines

<br>

### OA Framework Package Naming Standards

<br>

#### Scenario: General

<img align="center" src="https://github.com/demasy/Oracle-OA-Framework-OAF-Guidelines/blob/main/resources/images/diagrams/demasy_oaf_general_structure.png">

<br>

#### Scenario: Custom Solution

<img align="center" src="https://github.com/demasy/Oracle-OA-Framework-OAF-Guidelines/blob/main/resources/images/diagrams/demasy_oaf_hrss_structure.png">

<br>

#### Scenario: Extended View Objects

<img align="center" src="https://github.com/demasy/Oracle-OA-Framework-OAF-Guidelines/blob/main/resources/images/diagrams/demasy_oaf_extended_view_objects_structure.png">


<br>

## OA Framework Model Standards Guidelines

<br>

### OA Model Naming Conventions

<br>

 | SEQ       | File Type                    | File Extension | Length | Prefix | Suffix | Syntax                    | Example |
 | :-        | :----                        | :---           | :-:    | :---   | :---   | :----                     | :---- | 
 | 1         | **Entity**                   |  -             | -      |  -     |  -     | -                         | -|
 | 1.1       | Entity Object                | .xml, .java    | 30     |  -     | EO     | {entityName}{suffix}      | EmployeeEO|
 | 1.2       | Association Object           | .xml           | 30     |  -     | AO     | {parent}To{child}{suffix} | EmployeeToAssignment|
 | 1.3       | Entity Expert                | .java          | 30     |  -     | Expert | {name}{suffix}            | EmployeeExpert |
 | 1.4       | Entity Objects for Translatable (_TL) Tables | .java          | 30     |  -     | TLEO   | {name}{suffix}            | LookupCodeTLEO | 
 | 2         | **View Object**              | -              | -      |  -     |        | -                         | - |
 | 2.1       | View Object/View Row         | .xml, .java    | 30     |  -     | VO     | {DescriptiveName}{suffix} | - |
 | 2.2       | Validation View Object       | .xml, .java    | 30     |  -     | VVO    | {DescriptiveName}{suffix} | - | 
 | 2.3       | View Link                    | .xml           | 30     |  -     | VL     | {Master}To{Detail}{suffix}| - |
 | 3         | **Application Module**       | -              | -      |  -     | -      | -      | - |
 | 3.1      | Application Module            | .xml, .java    | 30     |  -     | VL     | {ModuleName}{suffix}      | - |
 | 3.2      | Validation Application Module | .xml, .java    | 30     |  -     | VAM    | {TopLevelEntityName}{suffix}     | - |
 

<br>

## OA Framework View Standards Guidelines

<br>

### OA Controller Naming Conventions

<br>

 | SEQ    | File Type                    | File Extension | Length | Prefix | Suffix | Syntax                    | Example |
 | :-     | :----                        | :---           | :-:    | :---   | :---   | :----                     | :---- | 
 | 1      | Page Definition              | .xml           | -      |  -     |      |   - {object}{function}{suffix} <br> - {object}{suffix} | |
 | 2      | **Region**                   |  -             | -      |  -     |  -     | -                         | -|
 | 2.1    | Shared Region Definition     | .xml           | -      |  -     |   RN  |  - {object}{function}{suffix} <br> - {object}{suffix}  | |
 | 2.1    | Shared List of Values (LOV) Definition | .xml           | -      |  -     | LovRN  | {descriptiveName}{suffix}   | |
 | 3      | UI Controller                | .xml, .java           | -      |  -     | CO  | - {object}{function}{suffix} <br> - {object}{suffix}  | |
 | 4      | Attribute Set Package                | .xml           | -      |  -     | -  | {tableName}   | | 
 | 5      | UI Components Package                | .xml           | -      |  -     | -  | {moduleName}   | | 


<br>

## OA Framework Controller Standards Guidelines 

<br>

 | SEQ    | File Type                    | File Extension | Length | Prefix | Suffix | Syntax                    | Example |
 | :-     | :----                        | :---           | :-:    | :---   | :---   | :----                     | :---- | 
 | 1      | UI Controller                | .xml, .java           | -      |  -     | CO  | - {object}{function}{suffix} <br> - {object}{suffix}  | |



<br> <br>

 ## Contributors

| Author | GitHub & LinkedIn account |
| :-  | :---- |
| Ahmed El-Demasy (Original Author) | <a href="https://github.com/demasy">Github</a> & <a href="https://www.linkedin.com/in/demasy">LinkedIn</a> |
<br>



### Contributing to the OA Framework (OAF) guidelines
We welcome new Oracle OAF developers to join our community and contribute to the OA Framework (OAF) guidelines project. If you are interested in helping please don’t hesitate to contact on an e-mail: founder@egyptianprogrammers.com

<br>
  
###### Suggestions & Issues
> If you find any issue or have a great idea in mind please create an issue on <a href="https://github.com/demasy/Oracle-OAF-Guidelines/issues">GitHub</a>.

