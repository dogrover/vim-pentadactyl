vim-pentadactyl
===============

Pentadactyl ftdetect, ftplugin, and syntax files, consumable by Vundle

The excellent [Pentadactyl](http://5digits.org/pentadactyl/) plugin for Firefox already provides syntax files and such. You can even generate them right from FF with the `mkvimruntime` command. However, that creates the directories right in your vim path.

I use [Vundle](https://github.com/gmarik/vundle), which encourages a cleaner approach. You can use this repo to keep the pentadactyl-specific stuff in a separate bundle. Just add this to your `.vimrc`:

    Bundle 'dogrover/vim-pentadactyl'

This is, by no means, an official repository. I'll keep it up to date as needed, until the selfless maintainers of pentadactyl see fit to create their own.

