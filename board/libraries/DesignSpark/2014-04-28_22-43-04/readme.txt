 
 
 
**********************************************************
*************  Important Instructions Follow  ************
**********************************************************
 
All files exported to: C:\UltraLibrarian\Library\Exported\DesignSpark\2014-04-28_22-43-04\2014-04-28_22-43-04.DSL
 
 
To import your new library into DesignSpark:

1. Open DesignSpark
2. On the menu, go to "File" then "Libraries" to open "Library Manager"
3. In "Library Manager", select the "Schematic Symbols" tab.
4. At the end of the "Library:" path is a button for "New Lib...", press that.
5. Browse to a location to save the library to, and give it a name.  When done, "Library Manager" should already have it selected at the top.
6. In the middle column of buttons, select "Add File...".  Browse to the library exported by UL and select it.
7. Next will be a window for "Eagle Symbol Library", with places for "Schematic Design" name, "Technology File", and so on.  Just hit OK.
8. When complete, the Library Manager should list the names of all symbols imported.

9. Next in "Library Manager", select the "PCB Symbols" tab.
10. At the end of the "Library:" path is a button for "New Lib...", press that.
11. Browse to a location to save the library to, and give it a name.  When done, "Library Manager" should already have it selected at the top.
12. In the middle column of buttons, select "Add File...".  Browse to the library exported by UL and select it.
13. Next will be a window for "Eagle Footprint Library", with places for "Schematic Design" name, "Technology File", and so on.  Just hit OK.
14. When complete, the Library Manager should list the names of all footprints imported.

15. Next in "Library Manager", select the "Components" tab.
16. At the end of the "Library:" path is a button for "New Lib...", press that.
17. Browse to a location to save the library to, and give it a name.  When done, "Library Manager" should already have it selected at the top.
18. In the middle column of buttons, select "Add File...".  Browse to the library exported by UL and select it.
19. When complete, the Library Manager should list the names of all components imported.

20. "Library Manager" can be closed.

For additional information, please visit this site:
http://www.accelerated-designs.com/help/DesignSpark_import.html

You may also find this video beneficial:
http://youtu.be/6bHvPsHG4DQ
 
 



**********************************************************
*************  Important Instructions Follow  ************
**********************************************************

All files exported to: C:\UltraLibrarian\Library\Exported\Altium\2014-04-28_22-43-04\2014-04-28_22-43-04


To import your new library part into Altium follow these steps:

1. After running the Ultra Librarian export for the first time,
you will need to copy the following files into an area where
they can be accessed for all future translations.  They are script
files that Altium will need to be able to find.
	a. UL_Form.dfm
	b. UL_Form.pas
	c. UL_Import.pas
	d. UL_Import.prjScr
	
2. The above script file will need to be run from within Altium.
This can be done by going to File, Open and selecting the
UL_Import.PrjScr file stored above.

3. Select the UL_Form.pas file form the new project that has loaded,
and then select runfrom the drop down menu.  You will need to select
the form again. Run the form.

3. When the script is run, it will ask you for the file name of the
Ultra Librarian file to run.  You should select the latest file
produced with a date code (for instance 2010-02-17_23-12-34.txt).

4. The script will open a new Integraged Library project and import
the Ultra Librarian data into it.  When complete a message box
will pop up saying that import is done.

For additional information, please visit this site:
http://www.accelerated-designs.com/help/Altium_import.html

For a video tutorial, please visit:
http://youtu.be/pih50yx9HYU





**********************************************************
*************  Important Instructions Follow  ************
**********************************************************

All files exported to: C:\UltraLibrarian\Library\Exported\Eagle\2014-04-28_22-43-04\2014-04-28_22-43-04


To import your new library into Eagle:
1. Start Eagle.
2. Select File -> New -> Library from the menu.
3. In the blank library window, select File -> Execute Script from the menu.
5. Browse to your newly exported Eagle Script file (".scr" file extension)
6. After opening the file, the script will populate the new library.
7. Use File -> Save (or Save As..) to save the library to the desired location in Eagle native format.

For additional information, please visit this site:
http://www.accelerated-designs.com/help/Eagle_import.html

You may also find this video helpful:
http://youtu.be/5jGuWY-Yy3Q





**********************************************************
*************  Important Instructions Follow  ************
**********************************************************

All files exported to: C:\UltraLibrarian\Library\Exported\Cadstar\2014-04-28_22-43-04\2014-04-28_22-43-04


To import your new library part to CadStar:

Select Cadstar Export check box from the Export Option screen.  Export the
current library.

Note teh directory your files are stored in from the readme file displayed after
the file is run.

Copy from that location the *.lib file that was created to your Cadstar Library
directory.

Start Cadstar Design Editor and select the menu item "Libraries" and sub menu
"PCB Components"

Select "ADd File" and change teh "Component Files" drop down message to be Archive
files.  This should allow you to select a *.cpa file.  Follow directions on screen
from that point forward.  There may be new items that will need to be added automatically.

Next select the menu item Libraries" and sub menu "Schematic Symbols".  From this screen
select the "Add File" button.  In this screen change the "Symbol Files" drop down box
to read "Archive files".  Now select the *.csa file that was created and stored for you.
Again follow any on screen instructions as line widths, fonts etc. may be required to
be automatically added.

Next select the menu item "Libraries" and sub menu "Parts...".  From this form select
the "Files" button on the right.  You should see the new library you have copied from the
export directory into your library directory.  Select this file and push the "Add File"
button.  You may be asked to re-index your library list at this point.

For additional information, please visit this site:
http://www.accelerated-designs.com/help/CadStar_import.html

To view a video tutorial that illustrates this process, please visit:
http://youtu.be/-3qU9rvs1-M


Component "ADCLK905BCPZ-R2" renamed to "ADCLK905BCPZ-R2"


Ultra Librarian Lite 6.1.136 Process Report


Message - Padstack "RX12Y32D0TSM2" Shape(3) is a CIRCLE with no diameter.
Message - Padstack "RX65Y65D0T" Shape(3) is a CIRCLE with no diameter.
Message - Pattern "CP_16_3", entity (349-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (351-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (354-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (356-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (359-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (361-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (364-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (366-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (369-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (371-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (374-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (376-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (379-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (381-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (384-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (386-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (389-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (391-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (394-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (396-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (399-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (401-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (404-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (406-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (409-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (411-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (414-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (416-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (419-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (421-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (424-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (426-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (437-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (439-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (441-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (443-Line) is a LINE with matching start and end points.

TextStyle count:  25
Padstack count:   2
Pattern count:    1
Symbol count:     1
Component count:  1

Export

Component "ADCLK905BCPZ-R2" renamed to "ADCLK905BCPZ-R2"


Ultra Librarian Lite 6.1.136 Process Report


Message - Padstack "RX12Y32D0TSM2" Shape(4) is a CIRCLE with no diameter.
Message - Padstack "RX65Y65D0T" Shape(4) is a CIRCLE with no diameter.
Message - Pattern "CP_16_3", entity (349-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (351-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (354-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (356-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (359-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (361-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (364-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (366-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (369-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (371-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (374-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (376-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (379-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (381-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (384-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (386-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (389-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (391-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (394-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (396-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (399-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (401-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (404-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (406-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (409-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (411-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (414-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (416-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (419-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (421-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (424-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (426-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (437-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (439-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (441-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (443-Line) is a LINE with matching start and end points.

TextStyle count:  25
Padstack count:   2
Pattern count:    1
Symbol count:     1
Component count:  1

Export

Component "ADCLK905BCPZ-R2" renamed to "ADCLK905BCPZ-R2"


Ultra Librarian Lite 6.1.136 Process Report


Message - Pattern "CP_16_3", entity (349-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (351-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (354-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (356-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (359-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (361-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (364-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (366-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (369-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (371-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (374-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (376-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (379-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (381-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (384-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (386-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (389-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (391-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (394-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (396-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (399-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (401-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (404-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (406-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (409-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (411-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (414-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (416-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (419-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (421-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (424-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (426-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (437-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (439-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (441-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (443-Line) is a LINE with matching start and end points.

TextStyle count:  25
Padstack count:   2
Pattern count:    1
Symbol count:     1
Component count:  1

Export

Component "ADCLK905BCPZ-R2" renamed to "ADCLK905BCPZ-R2"


Ultra Librarian Lite 6.1.136 Process Report


Message - Pattern "CP_16_3", entity (349-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (351-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (354-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (356-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (359-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (361-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (364-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (366-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (369-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (371-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (374-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (376-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (379-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (381-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (384-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (386-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (389-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (391-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (394-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (396-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (399-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (401-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (404-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (406-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (409-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (411-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (414-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (416-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (419-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (421-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (424-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (426-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (437-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (439-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (441-Line) is a LINE with matching start and end points.
Message - Pattern "CP_16_3", entity (443-Line) is a LINE with matching start and end points.

TextStyle count:  25
Padstack count:   2
Pattern count:    1
Symbol count:     1
Component count:  1

Export

