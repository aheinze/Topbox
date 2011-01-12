# Topbox #

... a dialog alternative.


# Usage #

    $.topbox.show(content, {
        //settings
        'title'     : false,
        'closeOnEsc': true,
        'theme'     : 'default',
        'height'    : 'auto',
        'width'     : 'auto',
        'speed'     : 500,
        'easing'    : 'swing',
        'buttons'   : false,

        //events
        'beforeShow'  : function(){},
        'beforeClose' : function(){},
        'onClose'     : function(){}
    });

where content could be a string, dom element or jQuery element.


*Shortcuts*

- Alert

    $.topbox.alert("...")

    
- Confirm

    $.topbox.confirm("...", function(){ 
        //your callback code
    });