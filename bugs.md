# Bugs and software

## What makes a good bug story?

1. The root cause must require at most one technical concept explained
   before it makes sense to a lay person.
2. At most two things must go wrong to trigger this bug.
3. Once the bug is triggered, it is allowed to cascade to other areas -
   the actual bug is not necessarily near the manifestation, and indeed
   *shouldn't be* too close to the manifestation.
4. Error handling paths should be assumed to be more likely to be wrong
   than not. Cascading failure is common.

Note: Because of the multiple redundancy of the ship's design, nothing
short of catastrophic damage should result in failure cascading all the
way. At worst a bug should result in a partial outage.

## Tools

The tools that Arthur has available to them are essentially end state
versions of most of what we have today.

Primary rules for programming tools:

* Anything that exists today can be assumed to have an almost magically
  good version of it.
* Anything that is obviously a purely mechanical process is done by an
  actual machine.
* The voice interface knows about these tools better than Arthur does
  and will largely just do what they ask it to.

Specific capabilities include:

* "Give me a minimal version of this input that produces this failure"
* "Run this backwards until this specified event happens for the first
  time"
* "Watch this program for anomalous events" (the anomalous event detection
  is not vastly intelligent and tends to produce false positives but is
  well enough tuned that it's a pretty good starting place).
* "Can this event happen?" (This one is is not guaranteed to work. It
  uses something that can be regarded as concolic testing on speed,
  but sometimes it runs into cases where the state space is too large
  for it to work well).
* "Mirror this real data to a simulated version of the program and see
  what it does, tracking any discrepancies".

## Software Ecosystem

With great technical tools come great technical challenges.

The following are some of the major obstacles:

* The system is massively distributed (imagine multiple independent 
  service oriented event driven architectures. Some interact through
  defined interfaces that cross firewalled network boundaries. Some
  interact only through their mutual interaction with the physical
  world). All of the expected level of horror this implies is present.
* The amount of generated data is mind boggling huge. 
  You can record some of the data all of the time, or all of
  the data some of the time, but you cannot record all of the data all
  of the time.
* Everything is breaking all the time. Just logging details of services
  which are crashing and being restarted would generate many gigabits
  of data.
* Nobody knows how things actually work, because it's an emergent system
  that has passed so far out of human comprehension so long ago that
  any attempt to understand it would barely scratch the surface within
  a human lifetime. The expectation is that even when you are at the
  cutting edge of work, the overwhelming majority of the code you are
  depending on has not been touched within living human memory.
* Any bug that has been possible in almost any language that has ever
  been used is probably represented *somewhere* in the system due to
  the extreme diversity of origins for the software.
 
## Source Material

This is just links to interesting debugging war stories and similar
that can serve as interesting source material for Arthur to have
to debug:

* [The Discovery of Apache ZooKeepers Poison Packet](https://www.pagerduty.com/blog/the-discovery-of-apache-zookeepers-poison-packet/)
* [Debug War Story](http://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=4700672) - on tracking down a hardwarea fault.
* ["My Hairiest Bug" war stories](http://web.media.mit.edu/~lieber/Lieberary/Softviz/CACM-Debugging/Hairiest.html)
* [Debugging strategies / techniques](https://macroware.wordpress.com/2014/03/29/debugging-strategies-techniques/)
* [Debugging Your Operating System: A Lesson In Memory Allocation](https://lukasa.co.uk/2016/12/Debugging_Your_Operating_System/)
* [Who called git?](https://www.schneems.com/2016/11/28/who-called-git-an-unusual-debugging-story/)
* [Attack of the DaliBug](http://pozorvlak.livejournal.com/150891.html)
* [Post-mortems by Dan Luu](https://github.com/danluu/post-mortems)
* [We had a unit test once which only failed on Sundays](https://qntm.org/unit)
* [Rachel by the Bay](https://rachelbythebay.com/w/)
