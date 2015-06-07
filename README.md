This Git repository contains the **~300** metro stations from Paris, thanks to RATP Open Data.

You can visualize the result in many ways, for example:
- GitHub network view: https://github.com/vbarbaresi/MetroGit/network
![GitHub network view](http://i.imgur.com/jV8e2Cx.png)

- `gitk` on your local copy
![gitk view](http://i.imgur.com/T1I7GWX.png)

- `git log --all --graph` (+ your favorite **decorate** options)
![git --graph view](http://i.imgur.com/x18oj9l.png)

Each metro line is represented by a **branch**.

A **commit** corresponds to a station. All commits are empty (with `--allow-empty` option), there is only metadata in this repository (and this `README` file)

A **merge** is a connection between one or more lines (use of `octopus` merges for interconnections of 3 and more)

This is the first version, I had to remove some interconnections, because there were some cycles.
In a second version I would dig more deeply and try to remove the least possible connections.
In a third version I would add **Tramway** stations, **RER** stations (**Réseau Express Régional**), and ultimately Bus stations!

There are still some errors / incorrect merges left.
