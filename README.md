TXL Language Support For BBEdit/TextWrangler
---

This adds basic syntax highlighting and rule/function/define recognition to [TXL](http://www.txl.ca/) grammar & rule files in [BBEdit/TextWrangler](http://www.barebones.com/).

I used the [Codeless Language Modules](http://www.barebones.com/support/develop/clm.html) method to implement this.  That means it's not a full parse - it just uses regular expressions - but rules/functions/defines show up in the dropdown menu and are "foldable" in the window and most syntax, comments, and strings are coloured properly.

To use it with *TextWrangler*, put the **Txl.plist** file in your `~/Library/Application Support/TextWrangler/Language Modules` folder and restart TextWrangler.

I don't have *BBEdit* (anymore - I had version 1!), but it should work.  The path would be `~/Library/Application Support/BBEdit/Language Modules`.

Fixes, improvements, and pull requests welcome!
