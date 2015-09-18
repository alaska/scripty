# scripty
A batteries-included library for every-day hackery in go.

## Rationale
Ever since coming to Go, I've enjoyed that I'm required to use only those portions of the standard library that I actually need to get the job done. This is great in keeping projects as small as possible, and separating concerns.

Having said that, I'm not always working on large projects.  Sometimes, I'm just whipping up a (for lack of a better term) "script" to do something simple or process a series of text files.  Sometimes this is one-off, sometimes I end up using it more often, and I put in `~/bin`.  Having been a Perl hacker for many years, this is often the language I reach for for writing such tools because of all of the nice features built into it for handling the opening of files and the usage of regexes. I'd like to have something like that for Go that, when combined with something like [gorun](https://github.com/erning/gorun) could make for a compelling replacement.  So let's see!

## TODO
Almost everything!  Currently everything lives in the base "scripty" package.  Would it make sense to separate it into related libraries with only certain shared crucial functionality (like arg parsing) handled in the base package? Who knows? time will tell.

## Is this a crappy idea?
I don't know.  Honestly, I don't expect anyone to use this but me and, since I wrote it, I already know how to implement each piece of functionality myself, so I'm not worried about it becoming a "framework" or hampering my learning process somehow.  This is purely a convenience library for me to easily bang out code.  If somehow this becomes a "thing", then I guess we'll talk about it.  Or something.  It won't become a thing.
