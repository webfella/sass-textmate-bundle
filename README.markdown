SASS Syntax highlighting for Textmate & Sublime Text 2
=======================================

Enables Syntax highlighting for those of you how prefer the alternative [SASS](http://sass-lang.com/) Syntax:

**SASS**
    $black: #333
    .pagination
      margin: 10px 0 5px
      text-align: center
      font-size: 14px
      span
        color: $black
      span.disabled
        display: none
      a 
        margin: 0 1px

Also supports the .scss syntax, introduced in SASS V3.

**SCSS**
    $black: #333;
    .pagination {
      margin: 10px 0 5px ;
      text-align: center;
      font-size: 14px;
      span {
        color: $black;
        &.disabled {
          display: none;
        }
      }
      a {
        margin: 0 1px
      }
    }

TEXTMATE INSTALLATION
------------------------------------

cd ~/Library/"Application Support"/TextMate/Bundles/

if that directory wasn't found, you'll need to create it, then:

git clone git://github.com/webfella/sass-textmate-bundle.git "Ruby-Sass-Alternative-Syntax.tmbundle"

SUBLIME TEXT 2 INSTALLATION
------------------------------------

The syntax highlighting is also compatable with Sublime Text 2

To enable it in the editor, clone the repo

git clone git://github.com/webfella/sass-textmate-bundle.git "SASS"

Once cloned, copy the following file witin the repo: Syntaxes/SASS.tmLanguage

and move to the directory below

~/Library/"Application Support"/"Sublime Text 2"/Packages/SASS/Syntaxes/

Easy peasy