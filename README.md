## The road to hell is paved with good intentions

![Oops](https://upload.wikimedia.org/wikipedia/en/5/50/ST_TroubleWithTribbles.jpg)

In sitting down to write a [FreeBSD](https://www.freebsd.org/)-specific application with [rust](https://www.rust-lang.org) I've learned a few things.  Many popular projects simple don't bother to look beyond Linux.  Those projects that do often have a terrible time trying to ensure compatibility.

How hard could it possibly be to set up a small build farm to at least ensure that fresh build validation is readily available?  Apparently pretty hard.  Along the way I've run into a number of [limitations](LIMITATIONS.md), and eventually started to put pen to paper with the hopes of coming up with a more [concrete definition](STORY.md) of usable.
