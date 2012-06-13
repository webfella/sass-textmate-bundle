Textmate with alternative SASS Syntax
=======================================

For those of you how prefer the alternative Sass Syntax:

    .pagination
      margin: 10px 0 10px 0
      text-align: center
      font-size: 14px
      span
        color: #000
      span.disabled
        display: none
      a 
        margin: 0 1px 0 1px

Also supports the .scss syntax, introduced in SASS V3.

INSTALLATION
------------------------------------

cd ~/Library/"Application Support"/TextMate/Bundles/

if that directory wasn't found, you'll need to create it, then:

git clone git://github.com/webfella/sass-textmate-bundle.git "Ruby-Sass-Alternative-Syntax.tmbundle"

SUBLIME TEXT 2
------------------------------------

The syntax highlighting is also compatable with Sublime Text 2

To enable it in the editor, clone the repo

git clone git://github.com/webfella/sass-textmate-bundle.git "SASS"

Once checked out, copy the following file: Syntaxes/SASS.tmLanguage

and move to the directory below

~/Library/"Application Support"/"Sublime Text 2"/Packages/SASS/Syntaxes/

Easy peasy