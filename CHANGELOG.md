##### Change Log

3.0.0  
* updated all the snippets with for latest vscode snippet options 
* `i2-[variable-name]` ionic scss variables added with default values 

2.4.0  
* updated the ionic data path 
* `i2-carousel` updated to ionic 3
* `i2-actionsheet`
* `i2-tab` 

2.3.5  
* Implement logging colorization 
* Add the ionic data url in the settings 
    
2.3.2  
* Added snippets for most of the icons in ionic 
* Added fab nippet
  
2.3.1  
* small bug fix, thanks to Sebastian Gaul to pointing the issue 

2.3.0  
* Help command Added(implement search using ionic site search)
* Select a word and open context menu select the **ionic 2 Help**
* Select a available option in the list, it will open the related ionic doc webpage
  
2.2.5  
* Missing Windows platform option added
* **run & emulate** commands added with options 
* New **Log switch** command added 
    * it enable/ disable console log and server log for running process. 
    * currently log switch enabled for following command  
        * serve command  
        * run with livereload option
        * emulate with livereload option
  
2.2.0
* Ionic Generate command added in explorer context menu. 
    * Right click on the pages folder and select the ionic generate 
    * Enter the page name to create a page
    * The above steps fit to the rest of the ionic generate items
    * if you select the command any where else, it will open the usual ionic generate command
* New Commands added 
    * Ionic serve with options
    * Ionic Package- Note: if login is expected, command will not work properly
    * Ioinc Resources
    * Ioinc State
* In the new version of ionic cli {page}.scss is Automatically added based on import statement, so i removed the implementaion of including {page}.scss in app.core.scss file
    
2.1.3
* minor bug fix for scss import statement

2.1.0   
* since finding error in output console is too hard, so shown the error in messagebox.  
* ionic generate page command: Automatically add the scss file reference in app.core.scss
* Add some basic validation 
   
2.0.0   
* Added new commands for ionic2 cli,
* It consumes the following commands   
*** serve, build, generate, run, kill Process
