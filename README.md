Joy
---

Build|Linux|Windows|Coverage|Quality
---|---|---|---|---
status|[![Travis CI build status](https://travis-ci.org/Wodan58/Joy.svg?branch=master)](https://travis-ci.org/Wodan58/Joy)|[![AppVeyor CI build status](https://ci.appveyor.com/api/projects/status/github/Wodan58/Joy?branch=master&svg=true)](https://ci.appveyor.com/project/Wodan58/Joy)|[![Coverage Status](https://coveralls.io/repos/github/Wodan58/Joy/badge.svg?branch=master)](https://coveralls.io/github/Wodan58/Joy?branch=master)|[![Language grade: C/C++](https://img.shields.io/lgtm/grade/cpp/g/Wodan58/Joy.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/Wodan58/Joy/context:cpp)

This is a distribution of [Joy1](https://github.com/Wodan58/joy1), without
the libraries. All modifications done in that fork make it difficult to see
what the original version was. Joy is a good language and needs a decent
presentation.

Changes
-------

All changes done in Joy1 have been undone. The only new thing is a portable
makefile, following the advice from [here](nullprogram.com/blog/2017/08/20).
Even so, there is something different in these sources compared to the ones
that you can download from the original [site](www.latrobe.edu.au/humanities/research/research-projects/past-projects/joy-programming-language) and that is
the comments at the start of main.c and of interp.c. Manfred von Thun really
wanted those comments in main.c, but the [newsgroup](https://groups.yahoo.com/neo/groups/concatenative/info) did not allow attachments, so it was never
realized. As for the comments in interp.c, I added them because I like some
version history. It proves that the language and the implementation was not
done during one night. In fact, according to this [interview](https://www.nsl.com/papers/interview.htm) the implementation in C was started in 1995.

Installation
------------

The [BDW garbage collector](https://github.com/ivmai/bdwgc) can be installed
and used, but Joy can operate without: this is both easier and faster.