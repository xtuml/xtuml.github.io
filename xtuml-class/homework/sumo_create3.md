# Build a Sumo Model - Homework 3  ![robot](../img/sumo_robot.jpg)  

1. Create package *sumo* under component *sumo*   

2. Double-click package *sumo* to open it on the canvas    

3. Create class *navigate*  

4. Create class *drive*  

5. Create class *steering*  

6. Click the **Association** tool in the Palette and drag between *navigate* and
*steering* on the canvas to draw an association   

7. Click the **Association** tool in the Palette and drag between *navigate* and
*drive* on the canvas to draw an association   

8. Select the association *R1* and then open the Properties view  
  * Expand Association Participant End
  * Expand Class As Simple Participant for *steering*  
  * Set the Text Phrase field to *navigates*  
  * Expand Class As Simple Participant for *navigate*  
  * Set the Text Phrase field to *steers for*  

9. Select the association *R2* and then open the Properties view  
  * Expand Association Participant End
  * Expand Class As Simple Participant for *drive*  
  * Set the Text Phrase field to *directs*  
  * Expand Class As Simple Participant for *navigate*  
  * Set the Text Phrase field to *motivates*  

10. Right-click on *navigate* and select **New > Attribute**. Name the attribute *retreat_duration*   

11. Right-click on *navigate* and select **New > Attribute**. Name the attribute *target_duration*   

12. Right-click on *drive* and select **New > Attribute**. Name the attribute *speed*   

13. Right-click on *drive* and select **New > Operation**. Name the operation *forward*   

14. Right-click on *drive* and select **New > Operation**. Name the operation *reverse*   

15. Right-click on *drive* and select **New > Operation**. Name the operation *stop*     

<br/>

Take a screenshot of your BridgePoint with Model Explorer view expanded to show all the 
elements you have just created.  Send the screenshot to your instructor.  

<br/>

You are now ready to proceed to the [next step](./sumo_create4.html)

<br/>
<br/>
[Back to homework list](../homework)  
