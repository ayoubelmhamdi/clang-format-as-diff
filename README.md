# clang-format-as-diff
view clang-format style like diff

use vim with
```vim
: e file1.c
:diffthis
:vs file2.c
:diffthis
:hi DiffChange guibg=NONE guifg=NONE ctermbg=NONE ctermfg=NONE
```
# 1
```c
someLongFunction(argument1,
    argument2);
```
![diff](https://user-images.githubusercontent.com/34358145/172957830-7a5bc724-0516-4316-99e1-ff2ed5b6c5d5.png)
