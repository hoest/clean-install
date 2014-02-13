# Installatie van Windows

Na een schone installatie van Windows, installeer de volgende onderdelen
voor een volledig werkend systeem:

* 7-Zip
* Browsers: Chrome, FireFox, Opera
* Console2 (http://www.kevwebdev.com/blog/in-search-of-a-better-windows-console-using-ansicon-console2-and-git-bash.html)
* Dropbox
* Fiddler2
* Git (http://git-scm.com/)
* Google Drive
* Editors:
  * gVim (http://www.vim.org/ - inclusief git@github.com:hoest/vim-dotfiles.git)
  * SublimeText (http://www.sublimetext.com/ - inclusief git@github.com:hoest/clean-install.git)
  * Visual Studio 2012
* Microsoft F#
* Microsoft Office
* Microsoft Security Essentials
* Microsoft SQL Server
* Microsoft SQL Server Management Studio
* Oracle Client tools (?)
* Paint.NET
* Powershell
* Putty
* Python 2.7/3+
* Tortoise CVS (http://www.tortoisecvs.org/)
* Tortoise Git (https://code.google.com/p/tortoisegit/)
* Total Commander
* Trillian (Instant Messenger - http://www.trillian.im/)
* WinMerge (?)

Eventueel ook installeren:

* AutoHotkey; AutoHotkey.ahk: 

```
#SingleInstance force

; Shortcut keys
#i::Run, "C:\Program Files\Internet Explorer\iexplore.exe", , %HOME%
#b::Run, "C:\Program Files (x86)\Google\Chrome\Application\chrome.exe", , %HOME%
#t::Run, "C:\Program Files\ConEmu\ConEmu64.exe", , %HOME%
#v::Run, "C:\Program Files (x86)\Vim\vim74\gvim.exe", , %HOME%
#s::Run, "C:\Program Files\Sublime Text 3\sublime_text.exe", , %HOME%
#c::Run, "%windir%\system32\calc.exe", , %HOME%

; remap Capslock to CTRL
Capslock::Ctrl
+Capslock::Capslock

; Right WIN-key => context-menu
RWin::AppsKey
```

* F.lux
* iTunes en iCloud
* Spotify
