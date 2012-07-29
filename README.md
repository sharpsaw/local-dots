local-dots
==========

Dotfiles and scripts useful when you don't have root.

The goal is to merge this into `linux-dots`, but it'll take a tiny bit of
work, and I haven't been on a system where I don't have root, lately.

Context
-------

Why "-dots"?  See the system I start with:

  curl sharpsaw.org/init | sh

Scripts
-------

<!--
Requires: https://github.com/sharpsaw/perl-dots (for its bin/bin-docs)
Update by having sharpsaw/perl-dots then yy@" on the next line:
jjV}k!bin-docs
-->
* `,pdo` ⇒ packages.debian.org in browser, add args to search (-n ... for name search)
* `,pkg` ⇒ Install a package (from URL or file) to `~/local` (or `$LOCAL\&INSTALL\&ROOT` if you override)
* `lddpackup` ⇒ For relocating a binary + its deps. (Note: Highly experimental.)

Contact
-------

rking-local-dots@sharpsaw.org

Ask/tell/demand anything. I'll be receptive.
