JSON editor jQuery plugin
=========================

A JSON editor component for you web apps/pages.
[Blog post](http://www.daviddurman.com)

[Live example](http://www.daviddurman.com/flexi-json-editor/jsoneditor.html)


USAGE
=====

        var myjson = { any: { json: { value: 1 } } };
        var opt = { 
            change: function(data) { /* called on every change */ },
            propertyclick: function(path) { /* called when a property is clicked with the JS path to that property */ }
        };
        /* opt.propertyElement = '<textarea>'; */ // element of the property field, <input> is default
        /* opt.valueElement = '<textarea>'; */  // element of the value field, <input> is default
        $('#mydiv').jsonEditor(myjson, opt);
