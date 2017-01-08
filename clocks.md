# Clocks and time keeping

Time, being money, is of course of vital importance for trade.

Which is why trader ships have so much of it. There are at least four
different notions of time they must pay attention to.

## Inter ship timae

The trading fleet records all history against a universal time standard
that everyone can agree on. As the point of divergence may have been very
far back, this means that they must keep track of things by a pre-diaspora
standard.

Specifically they use UTC and the Gregorian Calendar.

Ships have a complex set of astronomical
calculations, relativistic adjustments, etc. layered on top of the already
complicated set of calendrical rules that allows them to keep track of the
following question: If a beam of light recording the exact instantaneous
time in the Gregorian Calendar at its point of departure from Greenwich
observatory were to arrive here right now, what is the earliest value
that it could report? This is taken as being as close to the "current"
time in UTC as relativistically makes sense.

Inevitably this drifts off true despite best efforts: Gravitational curvature
too small to measure, rounding errors over time, etc. mean that it is more
or less impossible to keep this accurate forever.

The systems to their best to account not just for the value but also the
distribution. This is helped by synchronising time distributions when
two ships meet and correcting off pulsar observations and other astronomical
observations. The current 95% credible interval for the Eschaton Arbitrage's
time keeping of UTC is about five minutes.

But, of course, the UTC calculations still include leap seconds, otherwise
they'd be a lot further than that off.

## Intra ship time

Ship time on the other hand is significantly simpler. It is a monotonic
increasing time from several synchronized atomic clocks throughout the
ship, counting seconds from zero since the ship was founded. It has no
leap seconds.

The ship also measures estimated clock skew, so it has an interval estimate
of how long it has *actually* been since ship foundation (The current
95% credible interval for this is about 140 microseconds, which over
300 years isn't bad), but this is purely for calibration purposes: The
time reported by the ship's clock is considered the "true" time. 

Minutes and Hours are still understood because of UTC, but for ship time
the only units used are metric multiples of seconds. A kilosecond is 16
minutes and 40 seconds. A megasecond is about 11 days.

## Local time

When in system a ship will tend to maintain temporary clocks for each of
the local ports they are trading with, but people often don't concern
themselves with this directly as translation software normally takes
care of conversion between the two.

## Service local clocks

A ship will tend to have a large number of other clocks running behind
the scenes too for the benefit of various on board services. Much of
the software running on a ship will have been written with local
assumptions about calendars and times and needs to know whether it is
currently the 51st day of the closest approach of Rajna in order to
determine the appropriate billing rates to record.

The way this is handled is the way software interoperability is always
handled: The system lies shamelessly to the software it's running.

Individual services will typically be running off clocks that bear no
resemblance to reality. They may be running slow, they may be running
fast, they may be stuck in a perpetual groundhog day loop where the
service only lives for one day of its clock time and then is restarted
from zero after that.

How this fiction is maintained varies from service to service - there
are a number of NTP like services that cover specific subsystems, but
these are well firewalled and there is no danger of confusion. In most
cases it is handled more directly at the emulation layer.

This discrepancy between real and service time is one of those facts
that is "well known" but people routinely forget about until they are
forced to confront it.
