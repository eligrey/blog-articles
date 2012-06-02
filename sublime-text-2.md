title: Why SublimeText2 is my favorite editor
date: May 27, 2012 10:26:23 PM
---

[SublimeText2](http://www.sublimetext.com/2), in *"beta"* as of this writing, is a cross-platform programming text editor. But that's like saying a Swiss army knife is just a knife. Yes, it's merely a text editor, but it's the best damn editor I've ever used. By itself, it has a unique and interesting feature set, but when you add the features the community has developed around it, it becomes far more powerful and useful. If you haven't tried it yet, I recommend you do so. It runs on Mac, Linux, and Windows.

<!--more-->

# It has a great UX
[{% img right http://i.imgur.com/SNXezm.png %}](http://i.imgur.com/SNXez.png "Editing this article in SublimeText2")
SublimeText2 is one of the best looking editors I have ever used. The default theme is very good, and the themes made by the community (more on these in a moment) look even better. It has an incredibly minimalist GUI, that gets out of your way and lets you code. The default GUI is composed of: Sidebar, Tabs, Editor, Minimap, Statusbar. That's it. And each one of these features is useful. The sidebar lets you view a directory tree as well as all currently open files, the tabs, editor, and statusbar do exactly what you expect them to do, and the minimap provides a very useful live overview of your code. This overview highlights find results, errors, and is great for skimming log files.

## The Find Palette
[{% img right http://i.imgur.com/6Sg8km.png %}](http://i.imgur.com/6Sg8k.png "The Find Palette")The find palette is accessed by pressing `⌘+P`, and you get a simple text-entry at the top of the page. Enter a name, and it recursively searches your directory tree for filenames that match, *in real time*. It's incredibly fast and useful, and for larger projects, such as Rails apps, saves an awful lot of clicking.

You can also prefix your find string with a `@`, `:`, or `#`, which act as modifiers; allowing you to navigate the currently open document quickly. `@` lets you jump between class statements or similar in the current open file. `:` lets you jump to line numbers (just like in vim!), and `#` provides fuzzy search. You can mix these, so say i wanted to open `blog.rb` and jump to the `Post` class. I simply hit `⌘+P` and type `blog@Post`, or whatever substring is needed for the autocomplete to catch it. The file will open at the location in my *temporary buffer*.

Temporary buffers are a feature that, in my experience, are unique to ST2 as well. When you click a file or attempt to open it, it won't become the main buffer in your editor, until you've saved a change to it. This lets you very quickly preview things in other files, such as css classes in a stylesheet, while focusing on another document. If you don't save a change, it just disappears.

## The Command Palette
[{% img right http://i.imgur.com/6lz5dm.png %}](http://i.imgur.com/6lz5d.png "The command palette")While the find palette is impressive, the Command Palette is where all the action happens. Accessed by pressing `⌘⇧+P`, it looks almost identical to the find palette. But you won't see files in this, you will see commands. Commands can do things such as sort lines, capitalize code, re-indent, and many more things. You don't have to remember a battery of keystrokes, everything is a quick command away. And, like the find palette, it has complete-as-you-type, so even if you don't remember exactly what something is called, you can quickly invoke it.

# Plugins Galore
Many text editors have plugins and extensions and even themes, although they may be under different names. TextMate was probably the most prolific, followed closely (or exceeded by) vim.  ST2, however, blows everything else out of the water. Not only does it support textmate color-schemes and bundles, it also has a plethora of extensions of its own.

## Package Manager
Not only does it have plugins, but it has a [*fully community developed* package manager](http://wbond.net/sublime_packages/package_control), with tons of packages. Packages range from code-alignment plugins (very useful) to full UI skins (such as [SodaStyle](https://github.com/buymeasoda/soda-theme), the theme I use). Managing plugins is a breeze, you can do it all from within ST2 itself.

## Git Package
There are actually a couple of Git plugins I recommend. [Sublime-text-2-git](https://github.com/kemayo/sublime-text-2-git) and [Sidebar git](https://github.com/SublimeText/SideBarGit). Between these two, you can add, reset, commit, push, pull, and manage your git-ignore.

## Sidebar Enhancements
[Sidebar Enhancements](https://github.com/titoBouzout/SideBarEnhancements) adds several features missing from the sidebar, such as enhanced file management, quick URL copying, and more.

## *Tomorrow Night Modified*
I'm going to do some self-promotion here. The [Tomorrow color scheme](https://github.com/chriskempson/tomorrow-theme) by Chris Kempson is a clean, beautiful color scheme with lots of contrast. Unfortunately, it's lacking in a few areas, such as Diff formatting, rich-text formatting (such as bolds and italics in markdown), etc. I have a fork you can download, which adds these features:

<https://github.com/paradox460/TextMate-Tomorrow-Theme>

You can install this by pasting the above url into the Package control install prompt.

# It's Also a Great Editor
All the previous features are good, but none of them matter if the editor is terrible. This is not the case. SublimeText2 is incredibly fast, opening and closing at a moments whim, and is fairly light on resources. Syntax highlighting is instantaneous, and the extensibility makes it fairly future-proof. Finally, code completion is always helpful, and ST2's seems to get what I want more than other editors. While it doesn't hold your hand as much as some full IDEs do, such as Eclipse or even Coda, it's still far better than anything else I've tried.
