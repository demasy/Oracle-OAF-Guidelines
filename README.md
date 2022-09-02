# Oracle OA Framework (OAF) Guidelines

<br>

- OA Framework General Guidelines
- OA Framework Model Standards Guidelines
- OA Framework View Standards Guidelines
- OA Framework Controller Standards Guidelines
- OA Framework Java Guidelines
- OA Framework Deployment Standards Guidelines

<br>

## OA Framework General Guidelines

### Package Directory Structure

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

 | SEQ       | File Type                   | File Extension | Length | Prefix | Suffix | Syntax                    | Example |
 | :-        | :----                       | :---           | :-:    | :---   | :---   | :----                     | :---- | 
 | 1         | **Entity**                  |  -             | -      |  -     |  -     | -                         | -|
 | 1.1       | Entity Object               | .xml, .java    | -      |  -     | EO     | {entityName}{suffix}      | EmployeeEO|
 | 1.2       | Association Object          | .xml           | -      |  -     | AO     | {parent}To{child}{suffix} | EmployeeToAssignment|
 | 1.3       | Entity Expert               | .java          | -      |  -     | Expert | {name}{suffix}            | EmployeeExpert |
 | 2         | **View Object**                 | -              | -      |  -     |        | -                         | - |
 | 2.1       | View Object/View Row        | .xml, .java    | -      |  -     | VO     | {DescriptiveName}{suffix} | - |
 | 2.2       | Validation View Object      | .xml, .java    | -      |  -     | VVO    | {DescriptiveName}{suffix} | - | 
 | 2.3       | View Link                   | .xml           | -      |  -     | VL     | {Master}To{Detail}{suffix}| - |
 | 3         | **Application Module**          | -           | -      |  -     | -     | -      | - |
 | 3.1      | Application Module          | .xml           | -      |  -     | VL     | {ModuleName}{suffix}      | - |
 | 3.2      | Validation Application Module          | .xml           | -      |  -   | VAM     | {TopLevelEntityName}{suffix}     | - |
 
 
 
