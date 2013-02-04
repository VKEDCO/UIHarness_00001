

Android 2.2 (will run on Android 2.3 and Android 4.2) Eclipse 
project with an application that demonstrates how to test XML 
layouts programmatically.

UIHarnessAct.java is a Java driver (a harness, in other
words) for testing XML GUI layouts. This is the type of
utility one can use to test various XML layouts in
the emulator or an Android device. Why? Sometimes the
XML Graphical Layout does not quite give the right
outlook of what the GUI will really look like on the
phone or emulator. Nothing major but there are some
noticeable discrepancies. To run this harness, just
put your layout file inside /res/layout, build the
project, and setContentView in the onCreate method
below to the id of your layout through R.layout.
  
Below are several sample layouts given in /res/layout/
that you experiment with right away.
  
 1. /res/layout/button_00.xml - simple button
 2. /res/layout/layout_00.xml - vertical linear layout
 3. /res/layout/layout_01.xml - horizontal linear layout
 4. /res/layout/layout_01.xml - nested linear layouts
 5. /res/layout/radio_button_00.xml - radio button
 6. /res/layout/text_view_00.xml - text view
  
Change the argument of the setContentView method below
to the layout handle you want to test, e.g.
setContentView(R.layout.button_00).
  
If you add your own XML layout file, remember
to rebuild the project so that R.java class is updated.

Bugs to vladimir dot kulyukin at gmail dot com

If you run on Mac OS, you may want to use the Unarchiver utility at:
http://wakaba.c3.cx/s/apps/unarchiver.html

UnRarx may work as well: http://www.unrarx.com/


