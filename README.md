# 😎 awesome-trilium

A curated list of awesome [Trilium Notes](https://github.com/zadam/trilium) extensions. Including themes, widgets,
scripts, API extensions, ETAPI, etc.

You are welcome to add cool stuff about Trilium Notes here.

<a href="https://github.com/Nriver"><img align="center" src="https://moe-counter--nriver1.repl.co/get/@Nriver_awesome-trilium"></a><br>

--------------------

## 🦮 Table of Contents

<!--ts-->
 * [Migrating to Trilium](#-migrating-to-trilium)
 * [Themes](#-themes)
 * [Widgets](#️-widgets)
 * [Scripts](#-scripts)
 * [Extensions](#-extensions)
 * [Mobile](#-mobile)
     * [Android](#-android)
     * [iOS](#-ios)
 * [API extensions](#-api-extensions)
 * [ETAPI](#️-etapi)
     * [ETAPI client](#-etapi-client)
     * [ETAPI programs](#-etapi-programs)
 * [Translation](#-translation)
 * [Contribution](#-contribution)
<!--te-->

---

## 📥 Migrating to Trilium

These scripts and tips can be used to migrate to Trilium from other note taking applications:
* [Evernote](https://github.com/zadam/trilium/wiki/Evernote-import) (Trilium Wiki Guide) The most recent version of the Evernote application no longer includes the option to export files as an enex file. Instead, it now offers a different encrypted dump file format, which no one else can read. If you want to obtain an enex file, you might need to utilize the following tool: https://github.com/vzhd1701/evernote-backup.
* [HTML](https://github.com/zadam/trilium/wiki/Markdown) Supported Natively
* [Joplin](https://github.com/Nriver/trilium-py#import-from-joplin) Can be imported with trilium-py.
* [Logseq](https://github.com/Nriver/trilium-py#import-from-logseq) Can be imported with trilium-py.
* [Markdown](https://github.com/zadam/trilium/wiki/Markdown) Supported Natively
* [Obsidian](https://github.com/Nriver/trilium-py#import-from-obsidian) Need to convert a Obsidian vault to regular Markdown files first. Then import with trilium-py to handle obisdian's unique linking format. See more in the link.
* [OneNote](https://github.com/zadam/trilium/wiki/Onenote) (Trilium Wiki Guide)
* [Text](https://github.com/zadam/trilium/wiki/Markdown) Supported Natively
* [Turtl](https://github.com/Nriver/trilium-py/tree/main/examples/turtl-to-markdown) Convert Turtl notes to markdown directory
* [Youdao Note/有道云笔记](https://github.com/Nriver/trilium-py#import-from-youdao-note%E6%9C%89%E9%81%93%E4%BA%91%E7%AC%94%E8%AE%B0) Requires to download notes and convert to markdown. More details are in the link.
* [VNote](https://github.com/Nriver/trilium-py#import-from-vnote) Can be imported with trilium-py. The special image format will be well handled.
* .OPML Contents can be read and imported natively
* .TAR Contents can be read and imported natively
* .ZIP Contents can be read and imported natively



---

## 🏡 Themes

**App Themes**

App Themes provide theming to the Trilium application.

* [Blue Theme](https://github.com/SiriusXT/trilium-theme-blue) A brilliant and beautiful theme. Thanks SiriusXT!
* [Chameleon Theme](https://github.com/DavidFuchs/trilium-chameleon-theme) A set of light and dark colour themes for Trilium.
* [Linen Theme](https://github.com/mondayrobot/trilium-linen-theme) A minimal, airy light theme for Trilium with an
  optional distraction-free mode.
* [Melon Theme](https://github.com/raphwriter/trilium-theme-melon) A delightful theme.
* [NieR-Automata Theme](https://github.com/Nriver/NieR-Automata-Trilium-Theme) A fan-made NieR-Automata game UI like
  theme. This theme is made by me :)
* [Obsidian Theme](https://github.com/greengeek/trilium-obsidian-theme) Obsidian Note theme. Not lava and water :)
* [Solarized theme](https://github.com/WKSu/trilium-solarized-theme) Brings the classic solarized themes to Trilium! It
  comes in both light and dark.
* [Stellar Dark Theme](https://github.com/Lolabird/stellar-dark-theme-trilium) A different taste of dark theme.
* [VSCode-Dark Theme](https://github.com/greengeek/trilium-vscode-dark-theme) It's VSCode!

**Sharing Themes**

Sharing themes provide theming to shared notes!

* [FrostMiKu/Share.CSS](https://github.com/FrostMiKu/Share.CSS) A nice and clean theme for sharing notes. You should
  try it!
* [ysslang's theme](https://github.com/zadam/trilium/discussions/2681) Paper with shadow effect, cool!

---

## :scissors: CSS Snippets

Custom CSS to modify the look of Trilium. See ([Trilium Wiki](https://github.com/zadam/trilium/wiki/Themes#custom-css) for instructions on how to enable custom CSS)

* [display edited notes as list](https://github.com/zadam/trilium/discussions/2670#discussion-3884786)
* [remove numbers from table of contents](https://github.com/zadam/trilium/discussions/3873#discussioncomment-5710601)
* [vertical lines for tree](https://github.com/zadam/trilium/issues/3892#issuecomment-1530144842)

---

## ⚙️ Widgets

Widgets can make big difference in the Trilium user experience! 

* [drawio](https://github.com/SiriusXT/trilium-drawio) Integrated drawio plug-in
* [hexmap](https://gitlab.com/QuentinLeCaignec/trilium-hexmap) Interactive hexmap (for TTRPGs)
* [openfilepath](https://gist.github.com/laundmo/de1f386fac9f9e797fd77022d63967c9) Opens italicised file path upon
  double click
* [Scratchpad](https://github.com/zadam/trilium/discussions/1613#discussioncomment-638984) Add scratchpad widget to
  notes
* [Syntax Highlight](https://github.com/antoniotejada/Trilium-SyntaxHighlightWidget) The syntax highlight feature which
  you would like.
* [timeline](https://gitlab.com/QuentinLeCaignec/trilium-timeline) Interactive timeline
* [trilium-auto-hide-info-bar](https://github.com/SiriusXT/trilium-auto-hide-info-bar) Automatically hide the title bar
  and information bar, and you can set to hide one of them individually.
* [trilium-back-to-history](https://github.com/SiriusXT/trilium-back-to-history) Jump to the last browsing position
* [trilium-left-panel-auto-zoom](https://github.com/SiriusXT/trilium-left-panel-auto-zoom) Automatically widen note tree
  by moving your mouse. A convenient widget to navigate through notes with long titles and deep level notes.
* [trilium-show-position-in-toc](https://github.com/SiriusXT/trilium-show-position-in-toc) Mark font red of the position
  being browsed in the Table of contents.
* [Trilium-TocWidget](https://github.com/Lolabird/Trilium-TocWidget) The table of content widget is now built-in feature
  in Trilium Notes. Great thank to developers [antoniotejada](https://github.com/antoniotejada/Trilium-TocWidget)
  and [Lolabird](https://github.com/Lolabird/Trilium-TocWidget) !

---

## 🪄 Scripts

Magic!
Caution! Scripts are executable codes. Use them with care!
* [archiveDoneTask](https://github.com/jwhonce/trilium-addons/blob/main/archiveDoneTask/archiveDoneTask.js) Archive Task Manager Done tasks older then archivedAgeInDays (default: 30)
* [Trilium-chat](https://github.com/soulsands/trilium-chat) The chat plugin for Trilium currently supports Chatgpt
* [Better Include](https://github.com/salmund/trilium_better_include) Make subnotes and include them faster
* [Calendar & Timetable](https://github.com/Mangiola/trilium-scripts) Implements a calendar, timetable, and even a
  musical fretboard.
* [gistMirror](https://github.com/jwhonce/trilium-addons/blob/main/gistMirror/gistMirror.js) Mirror GitHub Gists to Trilium Note tree
* [Open note in split view](https://github.com/zadam/trilium/discussions/3937) Shift+click to open a note in split view. Ctrl+shift+click for tree nodes.
* [OpenFilePaths](https://gist.github.com/laundmo/de1f386fac9f9e797fd77022d63967c9) Italicized file or folder paths can
  be opened with a double click
* [Startup message](https://github.com/Nriver/trilium-translation/blob/main/demo-cn/示例笔记%20-%20请不要删除/Trilium%20扩展/Trilium%20脚本%20script/startup%20启动项/startup%20message%20启动信息.js)
  A quite simple script. Display a random message. Set `#run=frontendStartup` to run it when Trilium startup. Just like
  a MOTD(Message of the day) message :)
* [Trillium Agenda](https://github.com/BeatLink/trilium-agenda) Sorts todos into 6 categories: Overdue, Today, This Week, This Month, This Year, Future

---

## 💥 Extensions

* [trilium-collection-views](https://github.com/mabeyj/trilium-collection-views) A great extension for displaying notes
  in a different way.

---

## 📱 Mobile

Mobile phone related cool stuff.

### 🤖 Android

* [trilium-sender](https://github.com/zadam/trilium-sender) A simple write-only android application for sending images and notes to Trilium 

### 🍎 iOS

* [trilium-ios-shortcut](https://github.com/soulsands/trilium-ios-shortcut) A tutorial on sending messages to Trilium
  via an apple shortcut.

---

## 🧚 API extensions

More magic!

Caution! The plugins in this category involves custom request handlers (user defined APIs). Use them with care!

* [singlefile2trilium](https://github.com/nil0x42/singlefile2trilium) With the power
  of [SingleFile](https://github.com/gildas-lormeau/SingleFile) web extension, you can get a perfect copy
  of the webpage in Trilium.

---

## 🖥️ ETAPI

Trilium's ETAPI related stuff

### 🦾 ETAPI client

* [trilium-py](https://github.com/Nriver/trilium-py) Python client for ETAPI of Trilium Note with some extra cool
  features.
* [pytrilium](https://github.com/perfectra1n/pytrilium) Python client for ETAPI of Trilium Notes that contains all
  currently valid ETAPI paths, and implements a custom underlying `requests` session.

### 🤖 ETAPI programs

* [trilium-bot](https://github.com/Nriver/trilium-bot) A demo telegram bot for Trilium, powered
  by [trilium-py](https://github.com/Nriver/trilium-py).

---

## 🌐 Translation

* [trilium-translation](https://github.com/Nriver/trilium-translation) The unofficial translation project for Trilium.
  For now, a Chinese translation is completed.

## 🔥 Contribution

You are welcome to fork and contribute to this repo.

The [Table of Contents](#table-of-contents) part is generated
by [https://github.com/ekalinin/github-markdown-toc](https://github.com/ekalinin/github-markdown-toc). Then formatted
by `save actions` in PyCharm.
