#MultiSelect
MultiSelect is a jQuery-based replacement for select boxes. It supports single select, multi select, and search functionality.

#### Version: 
1.0

#### Author: 
sabiths (Sabith Sooppikkada)

## How to use:

Include jQuery ,

	<script type="text/javascript" src="http://code.jquery.com/jquery-2.1.3.min.js" />

Include plugin ,

	<script type="text/javascript" src="multiSelect/js/Multiselect.js" />
	
Include css ,
  <link href="multiSelect/css/style.css" rel="stylesheet" type="text/css" />
	
Customise element,

	$("#elementID").MultiSelect();
	
Optional configurations,

	$("#elementID").MultiSelect({
	  	flag:true,
    		searchbox:true,
    		selectall:true,
    		max:4,
    		label:"Test",
    		path:"img/"
	});
	
Optional configurations-In detail,

####flag

 - Default: `false`  
 - Expected: true or false  
 - Function: Specifies if an image has to be shown in  the select or not.

####searchbox

 - Default:  'false'  
 - Expected: Boolean(true or false)  
 - Function: Defines if the select contains search box.

####selectall

 - Default:  'false'   
 - Expected: Boolean (true or false)  
 - Function: Defines if the select contains select all box/option.
 
####max

 - Default: 0  
 - Expected: Integer  
 - Function: Specifies if any restriction is set. If yes,the limit can be specified.
 
####label

 - Default: " "  
 - Expected: String (Header text)  
 - Function: Indicates whether a particular label/header has been chosen in the select.
 - Example : "Item(s)" 
 
####path

 - Default: null  
 - Expected: String (Footer text)  
 - Function: Specifies the path of the images.
 - Example : "Image/"
 
###Methods
 
####MultiSelect({})
 
Invoking this method will replace the select box. Config parameters will be passed with this method
 
####getValue()
 
Invoking this method will return values of selected options from the select box
 
####refresh()
 
Invoking this method will redraw the select box
 
####check(index)
 
Invoking this method with index will mark the option with that index as selected
  
####unCheck(index)
 
Invoking this method with index will mark that option with index as unselected
  
####checkAll()
 
Invoking this method will mark all the options as selected
 
####unCheckAll()
 
Invoking this method will mark all the options as unselected
