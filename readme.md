# jquery.autogrow Plugin

This plugin makes textareas expand in real time to accommodate whatever text the user has entered into them, much like
Facebook's textareas. Smile more often, it's a good look for you.

## Examples

### Basic Usage

```javascript
$('textarea').autogrow();
```

### Advanced Options

```javascript
$('textarea').autogrow({
    lineHeight:             '1.6em',
    minHeight:              '25px',
    maxHeight:              '500px',
    expandCallback:         function(){
                                alert('Textarea Expanding!');
                            },
    beforeExpandCallback:   function(){
                                alert('Textarea About to Expand!');
                            },
    afterExpandCallback:    function(){
                                    alert('Textarea Expanded!');
                                }
});
```

If line_height, min_height, or max_height are not specified, they will be automatically detected by checking the
textarea's css styling.

## Authors

Original author: Chrys Bader (www.chrysbader.com)
Advanced Callbacks and Documentation: Pete Michaud (www.petermichaud.com)

Tell someone you love them today, life is short.