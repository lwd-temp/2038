# Year 2038 Problem Countdown
A timer the counter down to when [The Year 2038 Prolem](https://en.wikipedia.org/wiki/Year_2038_problem) happens.

## What is The Year 2038 Problem?
The Year 2038 Problem is the result a technical limitation on how computers store the time along with the size of numbers that 32-bit computers can hold, similar to the Year 2000 Problem. Basically, each computer keeps track of time in the UNIX time format. UNIX time is the number of seconds since the 1st of January 1970, also known as the "epoch". 32-bit variables can hold numbers as big as 2 147 483 647.

So once 2 147 483 647 seconds since the epoch has passed, which will be on the 19th of January 2038 at 03:14:07 UTC, the time variable will overflow and revert to -2 147 483 647, causing the computer to think the the date is the 13th of December 1901.

## Will I be affected?
**Probably not**, since the most computers and smartphones made recently are 64-bit, which can hold numbers as big as 9 223 372 036 854 775 807 and their time variable wont overflow until the year 292 277 026 596 (the universe is predicted to not exist by then!). So most consumer devices (except for old ones) will not be affected. As for other devices (like ATMs, military equipment and others), by the year 2038 it is likely that most (if not all) 32-bit devices will no longer be in use because of the impending time overflow, but I can't say that for sure.

## Copyright
&copy; 2017 Gregory Karastergios

Font: "Barlow" by Jeremy Tribby