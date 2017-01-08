# Archaisms and legacy protocols

Many of the technologies and protocols used would be distressingly
familiar to a 21st century programmer. e.g. they are still
using the Gregorian calendar, they are still running code written
in C and C++ (and JavaScript!). x86 assembly is the main interoperability
standard for getting someone else's software working on your system.

There are two main reasons for this:

* In many cases interoperability with other ships is more important than
  fixing things, and there is intrinsically no possibility of coordination
  with those other ships - many of them you could not send a round trip
  message within the lifetime of your crew (and the crew spend a significant
  amount of time in suspended animation. The life time of a crew member can
  easily top five hundred years). This means that the only way to coordinate
  is to use things in your common lineage, and the only real set of things in
  their common lineage are prediaspora (I haven't decided exactly when the
  diaspora occurred, but I'm tentatively pencilling in mid to late 22nd century).
* The set of legacy code is unimaginably huge, even before the diaspora, and
  there were some things that nobody ever got around to rewriting as a result.
  Trying to write a ship's operating system from scratch is as close to impossible
  as makes no difference - if you were to devote several generations of a planetary
  civilization to it then you would probably have a working operating system at the
  end but it would be at a significant robustness disadvantage compared to a well
  established one. This means that there will *always* be old things hanging around
  and there's not much point in trying to avoid that.

This doesn't mean that people are still writing in C++ or JavaScript *today*, generally
speaking. Instead it means that people have got very good at managing legacy systems
and interoperability. Regardless of what language they're written in, they all run on
a common infrastructure (possibly nested inside several previous generations of the
common infrastructure they all ran on back then) and they can all be managed fairly
uniformly regardless of their extremly heterogenous nature.
