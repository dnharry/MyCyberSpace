---
title: "Auto replace abbreviations with complete words"
date: 2020-05-17
description: "How to use AutoHotkey to to ease increase writing productivity"
draft: false
---

# Writing utility tip

When I began writing my MPhil thesis, I realised how annoyingly repeting some words were. In my case the scientific name for the malaria parasite thus, Plasmodium species which can be malariae, falciparum, vivax, ovale or knowlesi. 

Typing them isn't as annoying as the nned to break, italize, type before returing to your flow of writing.

It was when I was mulling over this gruesome feat that it dawned on me the a program I had used a fews years back; the program is AUTOHOKEY.It is a very light-weight program that allows you to append a set of instructions to a user-defined trigger input which can be keystrokes or a set of alphabets.

With that said, let's dive in....

- First download the program from https://www.autohotkey.com. (Read around if you've got time)
- Pick up the executable file and install (it's very simple).
- Don't run the program immediately (If you accidentally do so, simple right-click on the green "H" icon on the taskbar notification area and exit)
- Next, is to go to where you would want files for the program to be kept. IN my case I would go to My Documents and create a folder named "AutoScripts".
- Inside Autoscripts, right-click on the empty space, select new and click on autohotkey file. THis would create a file with the .ahkey extension.
- Open the file by selecting edit on the right-click menu. The file would open with a text editor.
- Inside it copy and paste this:

```
:*:pm::
SendInput
  , ^i Plasmodium malariae ^i
return 
```

- Save the file and open it. This would prompt the AutoHotkey to start running with the script active.
- So in Ms Word or an word processor that supports Control + I to italize, as soon as you type pm Plasmodium malariae would be typed.
- The script supports multiple commands so you can add as many commands as you want.
