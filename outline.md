# Vim and Ergonomics

    Picture of me 

Use your thumb more

Put Ctrl on Alt and Ctrl on Windows
Backspace and Caps Lock
Use the spacebar

---

# Normal Mode

    <C-u> page up
    <C-d> page down
    <C-y> scroll up
    <C-e> scroll down
    <C-r> redo
    <C-o> jump back
    <C-i> jump forward
    <C-v> visual block mode

---

# Insert Mode

    <C-r> insert register
    <C-n> autocomplete down
    <C-p> autocomplete up
    <C-a> find next number and increment
    <C-x> find next number and decrement
    <C-u> delete current insertion
    <C-w> delete back word
    
---

# Use the Spacebar!

    noremap <SPACE> <C-w>
    noremap <SPACE>h <C-w>h
    noremap <SPACE>j <C-w>j
    noremap <SPACE>k <C-w>k
    noremap <SPACE>l <C-w>l
    noremap <SPACE>v <C-w>v
    noremap <SPACE>s <C-w>s
    
---
# Space Space to Save

    noremap <space><space> :wa<cr>

---

# How on Windows

[http://www.randyrants.com/category/sharpkeys/](http://www.randyrants.com/category/sharpkeys/)

---

# How on Linux

~/.Xmodmap

remove Control = Control_L
remove Control = Control_R
remove Mod1 = Alt_L
remove Mod1 = Alt_R
remove Mod4 = Super_L
remove Mod4 = Super_R

keycode 64 = Control_L
keycode 108 = Control_R
keycode 133 = Alt_L
keycode 134 = Super_R
keycode 37 = Super_L
keycode 105 = Super_R
keycode 135 = Alt_R

add Control = Control_L
add Control = Control_R
add Mod1 = Alt_L
add Mod1 = Alt_R
add Mod4 = Super_L
add Mod4 = Super_R

remove Lock = Caps_Lock
keycode 22 = Caps_Lock
keycode 66 = BackSpace
add Lock = Caps_Lock

---
