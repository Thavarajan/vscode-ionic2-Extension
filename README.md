# ionic 2 Commands & Snippets for VS Code

**Ionic 2 snippets & Commands **

This extension for Visual Studio Code adds snippets for ionic 2 for TypeScript and HTML. also it provides some basic ionic cli commands, implement ionic site doc search inside vscode 

![Sample Generate command](https://raw.githubusercontent.com/Thavarajan/vscode-ionic2-Extension/master/images/ionic2_Command.gif)


## Snippets Usage
Type part of a snippet, press `enter`, and the snippet unfolds.


### HTML Snippets
```Typescript
i2-list             //add a ionic list with header and item 
i2-list-grp         //add a ionic list with header, group and item
i2-list-reord-grp   //add a ionic group with reorder and iterator
i2-itm-grp          //use to add a group section with an item inside an ion list
i2-itm-slide        //Add a sliding item in the list use both side
i2-Infinite         //Use this Snippet at the bottom of the list also look at the method create one to access it
i2-itm-for          //Add a ion item to ion-list with for loop
i2-itm-input        //Add a ion item to ion-list with inputs
i2-dtFormat         //Add a date format to the date field 
i2-itm              //Add a ion item to ion-list
i2-carousel         //Add a slider any where
i2-radiogroup       //Add a Radio group with iterator
i2-search           //Add a searchbar
i2-range            //Add a Range Control
```

### Type Script Snippets
```Typescript
i2-infinite         //ionic 2 Infinite scroll items update snippet with async operation
i2-alert            //ionic 2 alert snippet Import and Use the alertController, don't forget to insert int the constructor
i2-event            //ionic 2 Event snippet Create and Consume
i2-event-raise      //ionic 2 Event snippet for Create
i2-event-handle     //ionic 2 Event snippet for Consume
i2-reorder          //ionic 2 Reorder an item in list
```

Alternatively, press `Ctrl`+`Space` (Windows, Linux) or `Cmd`+`Space` (OSX) to activate snippets from within the editor.

## Commands Usage
Open the Command pallate under the view menu or press `Ctrl`+`Shift`+`p`.  
Type `Ionic` and select a Command from the list showing  
press `enter` then follow the options

### New Ionic Commands Added
* `Ionic Serve`
* `Ionic Generate`
* `Ionic Build`
* `Ionic Emulate`
* `Ionic Run`
* `Ionic Serve Options`
* `Ionic Package`
* `Ionic Resources`
* `Ionic State`
* `Log Switch`
* `Kill running Ionic Process`
* `Ionic 2 Help`
![Ionic help command](https://raw.githubusercontent.com/Thavarajan/vscode-ionic2-Extension/master/images/ionic2_Command_helpMenu.gif)



So far Commands are testd in Windows 10 env only,  
some commands will not work, if it need some input in between the Process.   
Please report any issue in the following  repo
https://github.com/Thavarajan/vscode-ionic2-Extension 