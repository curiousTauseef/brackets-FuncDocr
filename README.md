# FuncDocr

A brackets extension to generate JS/PHPDocs for your functions.

## How to Use
* Open a JS or PHP file
* set your cursor on a function declaration
	* `function cool(stuff)`
* Use the ShortCut `Ctrl-Alt-D` (Win) or `Ctrl-Shift-D` (Mac) to start the documentation or `/**` + Enter


The extension will provide a function documentation:

Natural way: `/**` + Enter

![](https://cloud.githubusercontent.com/assets/4931746/4238565/c820925e-39d9-11e4-998b-693c25b3a5b1.gif)

With shortcut:

![](https://cloud.githubusercontent.com/assets/4931746/4141317/f9303404-33ac-11e4-8e3c-c72925b4e550.gif)



`[[Description]]` will be selected so you can start to type. To jump to the next `[[tag]]` you can use `Tab` or jump to the last with `Shift-Tab`. The indenting updates on a tab jump (live indenting).

You will get hints for the `[[Type]]` tag.

![Type hints](https://cloud.githubusercontent.com/assets/4931746/3998983/b3eba9ba-294c-11e4-988b-4330735635fd.png)

Have fun and stay tuned!

## You're rich?
You don't need a second yacht and have some coins to spend? Here I am :)

[![Flattr this git repo](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=Wikunia&url=https://github.com/Wikunia/brackets-FuncDocr&title=Brackets-FuncDocr&language=javascript&tags=github&category=software)
<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
<input type="hidden" name="cmd" value="_s-xclick">
<input type="hidden" name="hosted_button_id" value="B5VQXWCZXYN2W">
<input type="image" src="https://www.paypalobjects.com/en_US/GB/i/btn/btn_donateCC_LG.gif" border="0" name="submit" alt="PayPal – The safer, easier way to pay online.">
<img alt="" border="0" src="https://www.paypalobjects.com/de_DE/i/scr/pixel.gif" width="1" height="1">
</form>



## v0.8.4

- It's possible to disable the autoindent functionality in the settings menu.
- `@callback` links will be visible as `[[Type]]` hints.

## v0.8.0
You can use several JSDoc options to describe your function
and you can dblclick on `[[...]]` to edit the tags.

![funcdocr0 8 0](https://cloud.githubusercontent.com/assets/4931746/5670323/2c266c44-977f-11e4-8683-6b1923c66edf.gif)


## v0.7.0
Document your react functions!
![funcdocr0 7 0](https://cloud.githubusercontent.com/assets/4931746/5670498/a3024bf2-9780-11e4-8bd9-448ef4f04496.gif)


## v0.6.0
## @link tags

![linkTag](https://cloud.githubusercontent.com/assets/4931746/5079729/78a7cc3e-6eb7-11e4-8502-7718bf7c0c97.gif)

Easy way to add @link tags to your docs!

## v0.5.3
### Default values!

![Default values](https://cloud.githubusercontent.com/assets/4931746/4649697/18f8859c-548d-11e4-9f86-9a9a669b71f2.gif)

## v0.5.0
+ It's possible to generate the doc block with `/**` + Enter. You only need to type `/**` in the line above the function declaration and use enter to start the documentation.

## v0.4.0
+ The padding for correct indentation updates on a tab jump

## v0.3.0
+ It's possible to update a doc block if you add a parameter or delete one (you need to use the shortcut again)

## v0.2.0
+ You get the tag `@returns` if the function returns a value
+ The `[[Type]]` is recognized if possible.

