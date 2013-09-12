SVG Snippets for Sublime Text 2/3
========================

A collection of SVG snippets for Sublime 2 and 3 (Time Saver!)


HOW TO INSTALL
==============
Browse to the following path on your UNIX system. Make sure you change the YOUR_USERNAME placeholder
with your current user.
```bash
cd /Users/YOUR_USERNAME/Library/Application\ Support/Sublime\ Text\ 2/Packages/User/
```

If the folder 'HTML' or 'SVG' doesn't exisit inside of this folder, create it:
```bash
mkdir HTML
```

or

```bash
mkdir SVG
```

I put my SVG snippets in HTML because I like to access them within an HTML file.


```
Enter this folder:
```bash
cd HTML
```

I recommend to checkout the repository directly in this folder:

```bash
git clone git@github.com:roundrobin/sublime-svg-snippets.git .
```

Now you will see inside of the ./HTML folder, a bunch of .sublime-snippet files.
Feel free to add new ones.

Restart Sublime.

HOW TO USE
==============
After you've installed the snippets, you can trigger the insertion of a snippet by typing in one of 
the follwing commands inside of a .js file and pressing the TAB key afterwards.

Note:
-----
All snippets have integrated jump points. Just use tab again to jump to the next one.


The list of available snippets:
```
svg + TAB     ==> <svg width="100%" height="100%" viewBox="0 0 200 200" ......
circle + TAB  ==> <circle cx="20px" cy="20px" r="20px" fill="#64CDAC"></circle>
rect + TAB    ==> <rect x="0" y="0" width="50px" height="50px" fill="#BBCD71"></rect>     
path + TAB    ==> <path ....
line + TAB    ==> <line ....
line + TAB    ==> <polyline ....
group + TAB   ==> <g ....
text + TAB   ==> <text ....
tspan + TAB   ==> <tspan ....

  
