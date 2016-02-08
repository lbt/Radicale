---
layout: page
title: Feature Freeze for 0.6
---

According to the [roadmap](http://redmine.kozea.fr/projects/radicale/roadmap),
a lot of features have been added since Radicale 0.5, much more than
expected. It's now time to test Radicale with your favourite client and to
report bugs before we release the next stable version!

Last week, the iCal and iPhone support written by Łukasz has been fixed in
order to restore the broken Lightning support. After two afternoons of tests
with Rémi, we managed to access the same calendar with Lightning, iCal, iPhone
and Evolution, and finally discovered that CalDAV could also be a perfect
instant messaging protocol between a Mac, a PC and a phone.

After that, we've had the nice surprise to see events displayed without a
problem (but after some strange steps of configuration) by aCal on Salem's
Android phone.

It was Friday, fun fun fun fun.

So, that's it: Radicale supports Lightning, Evolution, Kontact, aCal for
Android, iPhone and iCal. Of course, before releasing a new tarball:

- [documentation](/user_documentation/#starting-the-client) is needed for the
  new clients that are not documented yet (Kontact, aCal and iPhone);
- tests are welcome, particularly for the Apple clients that I can't test
  anymore;
- no more features will be added, they'll wait in separate branches for the 0.7
  development.

Please [report bugs](http://redmine.kozea.fr/projects/radicale/issues) if
anything goes wrong during your tests, or just let us know
[by Jabber or by mail](/contribute/) if everything is OK.