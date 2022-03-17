# Terminal Pane [F4] [D-Bus]

A KDE 5 dolphin context menu extension (aka Service Menu), that let's you
open the Terminal panel as with F4 (if bound to) via D-BUS from within the
context menu for folders.

This is for lazy people as me, who want to save the long move with their
pointing device to the "View" menu and "Show Panels" - "Terminal" from
within there or do not know about F4 keyboard shortcut.

After Installation this new action should be available in top level of the
context meneu. (if more than one action applies to directories, it will be
located under "Actions").

This is a clean room implementation based on D-Bus, therefore it lacks any
dependencies beside qdbus(1), that should come basicly always with KDE.
