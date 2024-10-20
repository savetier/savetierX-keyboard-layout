# savetierX-keyboard-layout
A transformed Colemak xkb-layout, for central European languages

From the alternative keyboard layouts my favourite is Colemak. However, it has its flaws for central and eastern European languages which I intent to fix with the SavetierX layout. This layout is very suitable for polyglots, linguists, language enthusiasts, Slavs, Slavists, Magyars, Romanians, and many more! SavetierX is a compromise between usability, adaptability, ergonomy, and comfort.

The basic ideas:

1) The German layout provides the Umlauts which are also used in other languages, like Hungarian, Turkish, or Swedish. That's why I have chosen the German keyboard layout as a basis. 

2) I wanted to include as many central and eastern European languages as possible. With this layout you should be able to write flawlessly in German, English, Hungarian, Polish, Slovak, Czech, Slovene, Croatian, Serbian, Bosnian, Montenegrine, Romanian, and Turkish without switching.

3) I wanted to keep the main keyboard-shortcuts at their place. A problem I see with Colemak is that e.g. CTRL+S (save) is at a different place (it kept cut/copy/paste, gladly). This could lead to a catastrophe if you have to often switch between QWERTZ and Colemak. For that reason I wanted to keep CTRL+A/S/X/C/V/Q/W as they were in QWERTZ, and bring CTRL+F/P/Z/T within the closer reach of your left hand (as Colemak has done already).

4) As a passionate gamer I wanted to keep W, A, S, D (for directions) at their place.

TIP for German speakers: With 'autokey-gtk' or 'espanso' you can transform the 105th key (if you have got it) into a 'sch'-key.



And this is the result so far:

![Level 1](https://raw.githubusercontent.com/savetier/savetier-keyboard-layout/main/savetier_keyb_layout_level1.png)

All levels:

![Level 1](https://raw.githubusercontent.com/savetier/savetier-keyboard-layout/main/savetier_keyb_layout_level3+4.png)

SavetierX VS. Colemak

![Savetier vs. Colemak](https://github.com/savetier/savetier-keyboard-layout/blob/main/savetier-colemak-compare.png)



# Install (tested on Ubuntu and Manjaro):
The easiest way to install this layout is to rename it to one you would never use (I renamed it to 'be', because I will never use the Belgian layout) and replace this file in the /usr/share/X11/xkb/symbols folder. After that you simply need to add the Belgian (or whichever you have chosen) layout to your keyboard layout profile. 

	wget https://raw.githubusercontent.com/savetier/savetierX-keyboard-layout/main/savetierX

	sudo mv savetierX /usr/share/X11/xkb/symbols/be

  (Change 'be' in the end to the one you want to replace)
