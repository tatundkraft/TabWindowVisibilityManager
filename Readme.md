# TabWindowVisibilityManager
This plugin will listen when switching between browser tabs using the 
HTML5 Visibility API. And will also listen for browser window focus 
and blur events. Add your code to pause and resume when leaving and 
returning to your webpage.

Orignal by Jonathan Marzullo, [Source](http://greensock.com/forums/topic/9059-cross-browser-to-detect-tab-or-window-is-active-so-animations-stay-in-sync-using-html5-visibility-api/)

## Usage
```
// TabWindowVisibilityManager
$(window).TabWindowVisibilityManager({
    onFocusCallback: function(){
           // resume() code goes here
    },
    onBlurCallback: function(){
           // pause() code goes here
    }
});
```

## Install
Download from the [project page](tatundkraft/TabWindowVisibilityManager).

Install with [Bower](http://bower.io/): `bower install --save tatundkraft/TabWindowVisibilityManager`