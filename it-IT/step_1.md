Click on **Variables** in the Code tab, then click on **Make a Variable**.

![Variable blocks](images/make-a-variable.png)

Type in the name of your variable. You can choose whether you would like your variable to be available to all sprites, or to only this sprite. Press **OK**.

![Create variable](images/name-variable.png)

The variable will show on the Stage:

![Variable on the stage](images/stage-total.png)

If you want to hide the variable on the Stage, uncheck the box next to the variable in the `Variables`{:class="block3variables"} blocks menu.

## Setting a start value

If your variable should have the same starting value every time your project is run, then add a script to set it:

```blocks3
when flag clicked
set [total v] to [0]
```  
