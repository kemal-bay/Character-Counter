# Character Counter
Character Counter is a small jQuery plugin for inputs and textareas to count characters in it.

Demo: http://jsfiddle.net/kemalbay/ea5bb026/

#Basic usage:

    $(".char-counter").charCounter();

#Options:

    backgroundColor: (string) Background of counter label.
    default: "#FFFFFF"

    position: (object) Label's position in element.
    default: {
	            right: 10,
	            top: 10
	         }
	font: (object) Label's font size and color.
	default: {
                size: 10,
                color: "#a59c8c"
             }
    limit: (integer) If you want to limit a textarea or an input, 
    you need to specify a limit. 
    If you don't want to limit your inputs set to 0.
    default: 255