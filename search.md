# **search location**
> this is **crucial** to whether the file/directory will be successfully found

# search method
> basically, there are two search methods:
> 1. search in all subdirectories
> 2. search in current directory
this can be configured in the *search tab* popping up after ctrl+f is pressed

# what search does
- search in file explorer basically functions like a combination of `find` and `grep`. note that **file content** can be used for searching files.
- search probably processes the input as pattern **'\b + input'**.

# search result
- search result is ==highlighted yellow==

# hot search
> note that the way windows searches is `hot search`, or `incremental search`, namely:
> you don't need to press enter to confirm search string. search string is automatically updated each time you enter a char 

# quick access
> when **search location** is `quick access`, all folders in `quick access` will be searched recursively(if **search method** is `search in all subdirectories`)

# find specific files after ctrl+o
> note that you can use date info(especially today) to find specific files
>
> clicking `modification date` reverses time order

> clicking the inverse caret on the right of `modification date` offers more 
  options to sort files according to time order

> **note that this works both in the dialog invoked by ctrl+o and
> in file explorer**

# the alt key
> the **alt** key plays an *essential* role in navigating to menu items.  
> in *file explorer*, **press the alt key**, and the pay close attention to the **shortcut letters popping up**.
## important
- **alt+f**(file)
- **alt+v**(view)
alt+<key> can also be pressed *one by one*.
### alt+f
after pressing alt+f, you can open a folder frequently used by additionally pressing a number, as shown in the panel popping up.
this is super useful to determine the prerequisite for search(namely, specifying a location).
alt+f -> <number> is the window version shortcut which is the counterpart of cmd+shift+<key>(such as cmd+shift+d for desktop) on mac.
### alt+v
after pressing alt+v, four menus will pop up:
1. panel
2. layout
3. current view
4. show/hide
here are shortcuts for three of them:
- panel
p: open **preview panel**
d: open **detail panel**
-current view
o: open **ordering method**
- show/hide
ht: **toggle item checkbox**
hf: **toggle file extension**
hh: **toggle hidden files**
hs: **hide selected items**

# best layout for search
`detail` is the best layout for search, as it shows path info

# search by typing directly, without ctrl-f
- note that you can simply type what you want to search for, without ctrl-f. so windows supports internally what listary does in this aspect.
- this feature also works in task manager.
