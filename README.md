Gfonts.css let's you use all the fonts from the [Google Font Directory](http://code.google.com/webfonts) with just one line of code. Makes development much easier and quicker, but you might want to get rid of the ones you don't use in production...

Just save gfonts.css in your 'stylesheets' folder (or wherever you prefer) and then add the following code to your HTML:

        <link rel="stylesheet" type="text/css" media="screen, projection" href="/stylesheets/gfonts.css" /> 

Then you can just refer to the fonts you want in any of your css, for example:

    h1{font-family:Lobster,sans-serif;}
    
Brought to you by [DAZ](http://dazzl.co.uk)
