local-dots
==========

Dotfiles and scripts useful when you don't have root.

Requires [...](http://github.com/ingydotnet/....git) (well, actually, it requires that you install to ~/.../src/local-dots/ and then otherwise get the files in the `$PATH` and sourced from your init .rc's)

<!--
Requires: https://github.com/sharpsaw/perl-dots (for its bin/bin-docs)
Update by having sharpsaw/perl-dots then yy@" on the next line:
jjV}k!bin-docs
-->
*         ,b (Start a browser. Prefers webbrowser.py (which is very smart), then falls back to firefox, elinks, links, and lynx (in that order).)
*       ,pdo (packages.debian.org in browser, add args to search (-n ... for name search))
*       ,pkg (Install a package (from URL or file) to `~/local` (or `$LOCAL_INSTALL_ROOT` if you override))
*  lddpackup (For relocating a binary + its deps. (Note: Highly experimental.))

Context
-------

See [rkingy-dots-conf](https://github.com/ouicode/rkingy-dots-conf) for a
sample entry point into the whole system.
