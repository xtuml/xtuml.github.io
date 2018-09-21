# Build a Sumo Model - Homework 1  ![robot](../img/sumo_robot.jpg)  

1. Create a new xtUML Project named *Sumo_mine*   

2. Create package *IO DTs* under *Sumo_mine*   

3. Create package *RobotInterface* under *Sumo_mine*    

4. Double-click package *IO DTs* to open it   

5. Create Enumeration DataType *Direction* inside *IO DTs* package   

6. Create Enumerator *backward* inside *Direction*   

7. Create Enumerator *stop* inside *Direction*   

8. Create Enumerator *forward* inside *Direction*   

9. Create Enumeration DataType *Orientation* inside *IO DTs* package   

10. Create Enumerator *left* inside *Orientation*   

11. Create Enumerator *straight* inside *Orientation*   

12. Create Enumerator *right* inside *Orientation*   

13. Double-click package *RobotInterface* in the Model Explorer view to open it  

14. Create interface *platform* inside *RobotInterface*   

15. Add the following operations and signals to *platform*   
  * operation: *init*  
  * operation: *lineDetected*  
  * operation: *touchLeft*  
  * operation: *touchRight*  
  * operation: *untouchLeft*  
  * operation: *untouchRight*  
  * signal: *go*  
  * signal: *turn*  
  * signal: *setName*  

16. Use the Properties view to modify the "Message Direction" property for each operation to be "From Provider"   

17. Expand the *platform* interface in Model Explorer view.  All the interface messages are shown.  

18. Right-click on *go* and select **New > Parameter**. Name the parameter *direction*.  

19. Expand the *go* interface message.  The *direction* parameter is shown.  

20. Right-click on the *direction* parameter and select **Set Type...**.  Use the wizard to select the *Direction* type.  

21. Right-click on *turn* and select **New > Parameter**. Name the parameter *orientation*.  

22. Expand the *turn* interface message.  The *orientation* parameter is shown.  

23. Right-click on the *orientation* parameter and select **Set Type...**.  Use the wizard to select the *Orientation* type.  

24. Right-click on *setName* and select **New > Parameter**. Name the parameter *name*.  

25. Expand the *setName* interface message.  The *name* parameter is shown.  

26. Right-click on the *name* parameter and select **Set Type...**.  Use the wizard to select the *string* type.  


<br/>

Take a screenshot of your BridgePoint with Model Explorer view expanded to show all the 
elements you have created.  Send the screenshot to your instructor.  

<br/>

You are now ready to proceed to the [next step](./sumo_create2.html)

<br/>
<br/>
[Back to homework list](../homework)  
