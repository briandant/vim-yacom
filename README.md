Introduction
------------

(Y)et (A)nother (COM)ment is a vim commenting plugin with an extremely
minimalist approach. It has only one keybind (default `<leader>c`) to toggle
the comment (i.e. comment if not commented, uncomment otherwise) the current
line (normal mode) or the selected line(s) (visual mode).

Installation
------------

Drop `yacom.vim` to your `~/.vim/plugin` folder or just use your favorite
install method.

Settings
--------

You can change the default keybinding using:

    let g:yacom_comment_toggle='<C-c>'

I haven't written a documentation for this.

Supported Languages
-------------------

I have only added the languages that I use. You may want to add your own
language and optionally send me a patch (think of it as an educational
exercise if you haven't send a patch before). It should be easy since there is
only one file in the plugin and you'll know where to add your language when
you open it (try to keep it sorted).

Alternative
-----------

If you need a feature rich alternative, you may try
[tcomment](https://github.com/tomtom/tcomment_vim). It's awesome, I'm also
using it.

FQA (Frequently Questioned Answers)
-----------------------------------

I wanted to maintain a comment plugin so that it would be easy to add support
for a new language in case I want to try out an exotic language.

    Exotic languages are already supported by most comment plugins these days.
    Plus it is easy enough to patch existing plugins for new languages.

What if I create my own language?

    That's not gonna happen.

It doesn't have fancy regexp replace algorithms meaning no bugs at all.

    Every program that is longer than a few lines have some bugs within, the
    question is how often you'll face them.

But it's lightweight.

    Lightweight is just a fancy word for redundant startups.

Shut up!

    m'kay

