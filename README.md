# Dojo Mobile SidePane

A container displayed on the side of the screen. It can be displayed on top of the page (mode=overlay) or can push the
content of the page (mode=push). Compatible with Dojo 1.9.x.

To open/close the panel, swipe from the border of the screen to the center.

## Samples

Overlay mode: http://dmandrioli.github.io/sidepane/tests/test_SidePane-overlay.html

Push mode: http://dmandrioli.github.io/sidepane/tests/test_SidePane-push.html

## Installing

Clone this repository into a Dojo 1.9 distribution, next to 'dojo', 'dojox' and 'dijit'.

## Tested platforms

* iOS 6.x
* Android 4.x
* Blackberry 10
* Windows Phone 8

## Known bugs/limitations

* In overlay mode, the size of the panel can't be set in HTML. It is set to 15em by default. To change this value,
change @PANEL_WIDTH in SidePane.less and regenerate themes.

* Windows Phone and Blackberry: opening a right panel using swipe gesture does not work.

## Credits

* Damien Mandrioli (IBM CCLA)
