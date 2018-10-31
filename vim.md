# Vim

## Keyboard shortcuts

### General

* `<leader> w`  Write the file
* `<leader> q`  Close the buffer
* `jj`          Escape (in normal mode)
* `<leader> cd` Auto change directory to match current file
* `<leader> x`  Open the current file in the default program
* `<leader> n`  Toggle NERDTree
* `<leader> tb` Toggle Tagbar
* `<leader> d`  Add PHP Docblock
* `<leader> t`  Run PHPUnit on the current file
* `:ed`         Create/edit a file in the same directory as the current file

### Abbreviations

* `amod` artisan make:model
* `amig` artisan make:migration
* `ajob` artisan make:job

### CtrlP

##### Invoking
* `<leader> f` Find files
* `<leader> b` Find buffers
* `<leader> s` Find symbols
* `<leader> m` Find recently used

##### Using
* `<ctrl>+d` Toggle searching between file name and file path
* `<ctrl>+j`/`<ctrl>+k` Scroll items in CtrlP window
* `<ctrl>+f`/`<ctrl>+b` Switch between find modes

### Phpactor

* `<leader> u`  Include use statement
* `<leader> o`  Goto definition
* `<leader> mm` Invoke the context menu
* `<leader> nn` Invoke the navigation menu
* `<leader> o`  Goto definition of class or class member under the cursor
* `<leader> tt` Transform the classes in the current file
* `<leader> cc` Generate a new class (replacing the current file)
* `<leader> ee` Extract expression (normal mode)
* `<leader> ee` Extract expression from selection
* `<leader> em` Extract method from selection

### ack/ag

##### Invoking

* `<leader> ag`

##### Using

* `?`  Show keyboard shortcuts
* `o`  to open (same as Enter)
* `O`  to open and close the quickfix window
* `go` to preview file, open but maintain focus on ack.vim results
* `q`  to close the quickfix window

### argwrap

* `<leader> aw` Wrap/unwrap code

### fugitive

* `<leader> gs` git status
* `<leader> gcv` git commit (verbose)
* `<leader> gca` git commit amend (verbose)
* `<leader> gb` git blame
* `<leader> gp` git push

### gitgutter

* `]c` jump to next hunk (change)
* `[c` jump to previous hunk (change)
* `<leader> ga` stage the hunk
* `<leader> gu` undo staging the hunk

## Snippets

### PHP

*(Mostly from ~/.vim/bundle/vim-snippets/UltiSnips/php.snippets)*

* `gm` Getter
* `sm` Setter
* `gs` Getter & setter
* `pub` Public method
* `pro` Protected method
* `pri` Private method
* `pubs` Public static method
* `pros` Protected static method
* `pris` Private static method
* `fu` Function
* `new` New class instance
* `ns` Namespace
* `class` Class template
* `interface` Interface template
* `trait` Trait template
* `construct` Constructor template
* `testcase` TestCase template
* `testcase6` TestCase template (phpunit 6)

### Laravel

*(Mostly from ~/.vim/bundle/vim-snippets/UltiSnips/php-laravel.snippets)*

* `l_rsc` Resource controller
* `l_ssp` Service provider for service
* `l_rsp` Service provider for repository
* `l_md` Simple model
* `l_ar` Abstract repository
* `l_r` Repository
* `l_s` Service
* `l_f` Fascade

### HTML

#### Entities

* `down` ↓ (down)
* `enter` ⌅ (enter)
* `escape` ⎋ (escape)
* `left` ← (left)
* `return` ↩ (return)
* `right` → (right)
* `shift` ⇧ (shift)
* `tab` ⇥ (tab)
* `up` ↑ (up)

#### Elements

* `html` HTML basic structure
* `htmll` HTML basic structure with the lang attribute
* `doctype` HTML 5.0 doctype
* `head` `<head>`
* `title` `<title>`
* `viewport` Responsive viewport meta
* `link` `<link>`
* `script` `<script>`
* `scriptsrc` `<script src...>`
* `style` `<style>`
* `meta` `<meta>`
* `body` `<body>`
* `a` `<a>`
* `abbr` `<abbr>`
* `address` `<address>`
* `article` `<article>`
* `aside` `<aside>`
* `b` `<b>`
* `base` `<base>`
* `blockquote` `<blockquote>`
* `br` `<br>`
* `button` `<button>`
* `caption` `<caption>`
* `cite` `<cite>`
* `code` `<code>`
* `data` `<data>`
* `datalist` `<datalist>`
* `dd` `<dd>`
* `del` `<del>`
* `dfn` `<dfn>`
* `div` `<div>`
* `div#` `<div id="" class="">`
* `div.` `<div class="">`
* `dl` `<dl>`
* `dt` `<dt>`
* `em` `<em>`
* `fieldset` `<fieldset>`
* `fig` `<figure>`
* `figcaption` `<figcaption>`
* `footer` `<footer>`
* `form` `<form>`
* `h1` `<h1>`
* `h2` `<h2>`
* `h3` `<h3>`
* `h4` `<h4>`
* `h5` `<h5>`
* `h6` `<h6>`
* `header` `<header>`
* `hr` `<hr>`
* `i` `<i>`
* `img` `<img>`
* `input` Input with Label
* `input` `<input>`
* `ins` `<ins>`
* `kbd` `<kbd>`
* `label` `<label>`
* `legend` `<legend>`
* `li` `<li>`
* `mailto` `<a mailto: >`
* `main` `<main>`
* `mark` `<mark>`
* `meter` `<meter>`
* `nav` `<nav>`
* `noscript` `<noscript>`
* `ol` `<ol>`
* `optgroup` `<optgroup>`
* `output` `<output>`
* `option` `<option>`
* `p` `<p>`
* `picture` `<picture>`
* `pre` `<pre>`
* `progress` `<progress>`
* `q` `<q>`
* `s` `<s>`
* `samp` `<samp>`
* `select` `<select>`
* `small` `<small>`
* `span` `<span>`
* `span#` `<span id="" class="">`
* `span.` `<span class="">`
* `strong` `<strong>`
* `sub` `<sub>`
* `sup` `<sup>`
* `table` `<table>`
* `tbody` `<tbody>`
* `td` `<td>`
* `template` `<template>`
* `textarea` `<textarea>`
* `tfoot` `<tfoot>`
* `th` `<th>`
* `thead` `<thead>`
* `time` `<time>`
* `tr` `<tr>`
* `ul` `<ul>`
* `var` `<var>`
* `wbr` `<wbr>`

#### Attributes

* `access` `accesskey=""` attribute
* `class` `class=""` attribute
* `id` `id=""` attribute
