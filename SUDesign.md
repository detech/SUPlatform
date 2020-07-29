Software Update Design (WIP)
============================

## Introduction
Software update deals with _moving from one version to another version of a software system_.

## Designing a Software Update version
### Requirements
#### In Scope
- modular vs monolithic   
- upgrade vs downgrade

#### Out of Scope:
- version scheme

### Notes
* version skipping vs version transition path vs  steps supported 
* Is Update always guaranteed?
* Is versioning in the scope of SU?
* previous to new version vsrollback???
   - Upgrade vs Downgrade
* Types of Updates
    - OS update
    - Application Update
    - module update?
    - processes update??
    - Firmware/Drivers (is it one and the same thing?)
    - modular is a design pattern ....
    - data only
* OTA
* Updates
* Means of comm
* Device based update
    - Firmware vs embedded sw
    - Embedded devices get bricked
    - Manufacturing time????

## Side discussions:
----------------------------
### Detailed design Problems
* Given two versions, find out whether a software update is possible?
    - Requirements: 
      Min versions, Max versions, Version skipping, Version lock

    + Discuss what data structure would you use & why?
      - Array
      - Tree
      - Graph
      - Table
      - map
      _we'll leave it for later where this will be used_
