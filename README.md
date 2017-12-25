<div id="table-of-contents">
<h2>Table of Contents</h2>
<div id="text-table-of-contents">
<ul>
<li><a href="#sec-1">1. Emacs</a>
<ul>
<li><a href="#sec-1-1">1.1. MELPA</a></li>
</ul>
</li>
</ul>
</div>
</div>

This repo contains all of the basic necessities that I use.

# Emacs<a id="sec-1" name="sec-1"></a>

I use the following resources. I also provide my init.el file (Needs updating).

## MELPA<a id="sec-1-1" name="sec-1-1"></a>

    (require 'package)
    (add-to-list
     'package-archives
     '("melpa" . "https://stable.melpa.org/packages/")
     t)