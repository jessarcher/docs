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
* `<leader> gc` git commit (verbose)
* `<leader> gb` git blame (verbose)
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
