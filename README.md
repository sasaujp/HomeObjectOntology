# HomeObjectOntology

## Collection of object from video archives
- **Target Video**  
Videos containing scenes of potential accidents, selected by safety engineering experts.：397 (2021/10/22)  
Video of listing objects with manual annotation：48 (2021/10/22)  
- **Method of extraction**  
Randomly extract the annotated videos.  
The list of objects to be annotated is merged with the base list on the previous page. The inclusion and exclusion criteria are described separately. 
- **Results**
    1. Extracted objects from 16 videos（The rate of new objects：0.74)
        - new objects in annotations：200
        - new objects：148
    2. Extracted objects from 7 videos（The rate of new objects：0.25)  
        - new objects in annotations：82
        - new objects：38
    3. Extracted objects from 9 videos（The rate of new objects：0.14)
        - new objects in annotations：190
        - new objects：27
        - ※When the ratio of the new objects was less than 20% of the total, we decided that we had reached saturation and finished the extraction of object candidates.
    - Total：568
## Object exclusion criteria
1. The object type is not classified by by colour, size or shape.
 E.g.：*Yellow boxes*, *small boxes* and *round boxes* should all be unified as *boxes*.
3. The object type is not classified by the purpose of use.  
 E.g.：*TV remote control*, *video remote control* and *air conditioner remote control* should all be unified as *remote control*.
3. The object type is not classified by context-sensitive attributes．  
 E.g.：*The door on the right*, *the door on the left* should be unified with *the door*, and *the room next door* with *the room*.
4. The object type is not classified by materials．  
 E.g：The conceptualisation *pottery* refers to objects made of *clay*. This is not used as a conceptualisation perspective because it does not characterise form, use or function.

## Properties of objects in this ontology
- Affordance: Object-induced human behaviour
    - E.g."Up" and "down" for "step".
- Function: Changes caused by Object
    - E.g. "Cut" for "blade".
- State: Attributes belonging to the Object, which change according to the action or function
    - E.g. For "door", "open" or "closed".
- Attribute: Attributes that belong to the object and do not change
    - E.g. "5 cm" for "step".
- Property: Attribute that qualifies the Attribute compared to some reference value
    - E.g. "High" or "Low" (based on X cm for the elderly, Y cm for young people, etc.)


# [Description generated by pyLODE](./description.md)
