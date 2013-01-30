# jQuery Touch Punch
## Touch Event Support for jQuery

> **jQuery Touch Punch is a small event handler mapping plugin that allows for support of mouse events through the simulation of their handlers when a 
touch event is fired **

Extending and modifying the original jQuery UI Touch Punch 0.2.2 into a plug-in that doesn't depend on jQuery UI allows you to call it on any jQuery object selecting elements
you've hooked up event handlers to and want to now wire up touch-based events to properly.

## Using Touch Punch is as easy as 1, 2, 3…

Just follow these simple steps to enable touch events in your jQuery UI app:

1. Include jQuery on your page.

    ```html
    <script src="http://code.jquery.com/jquery.min.js"></script>
    ```

2. Include Touch Punch after jQuery and before its first use.

    ```html
    <script src="jquery.touch-punch.min.js"></script>
    ```

3. Just make a jQuery Touch Punch call on the respective jQuery selection object

    ```html
    <script>$('#widget').touchDraggable();</script>
    ```

_Tested on iPad, iPhone, Android and other touch-enabled mobile devices._