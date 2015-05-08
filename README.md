#MultiSelect
MultiSelect is a jQuery-based replacement for select boxes. It supports single select, multi select, and searching of options.

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
 - Function: Whether to include image in the select option or not

####searchbox

 - Default:  'false'  
 - Expected: Boolean(true or false)  
 - Function: Wheather to include search box or not

####selectall

 - Default:  'false'   
 - Expected: Boolean (true or false)  
 - Function: Wheather to include an option to select all the options
 
####max

 - Default: 0  
 - Expected: Integer  
 - Function: To restrict the maximum selection.
 
####label

 - Default: " "  
 - Expected: String (Header text)  
 - Function: To include a header text.
 - Example : "Item(s)" 
 
####path

 - Default: null  
 - Expected: String (Footer text)  
 - Function: Path to the image location.
 - Example : "Image/"
 
###Methods
 
####MultiSelect()
 
Invoking this method will replace the select box. Config parameters will be passed with this method
 
####getValue()
 
Invoking this method will return selected options from the select box
 
####refresh()
 
Invoking this method will redraw the select box
 
####check()
 
Invoking this method with option index will mark that option as selected
  
####unCheck()
 
Invoking this method with option index will mark that option as unselected
  
####checkAll()
 
Invoking this method will mark all the options as selected
 
####unCheckAll()
 
Invoking this method will mark all the options as unselected
