# Digital-Clock

### This project represents 3 files each one represents an independent circuit. The software used is MULTISIM (by National Instruments Company Ltd).

### Contents
- Complex digital 12/24H clock circuit
- Simple digital 24H clock circuit
- Stopwatch circuit

### Complex digital 12/24H clock circuit (clock 12-24)
A digital clock is a clock which can display the time in digits. Three units are often considered: hour, minute and second. To represent the time, a sevensegment LED is often used, two digits for each unit respectively. To store the time, there are internal counters for the units. The counters work as follows.
* A 1 Hz pulse is generated to make the ‘second’ counter count.
* Whenever the ‘second’ counter counts to 60, immediately, it resets to 0, while the ‘minute’ counter counts once.
* Whenever the ‘minute’ counter counts to 60, immediately, it resets to 0, while the ‘hour’ counter counts once.
* For the ‘hour’ counter:
  – In 12-hour format, there is a status representing AM or PM. Whenever the ‘hour’ counter counts to 12, immediately, it resets to 0 while the AM/PM status changes.
  – In 24-hour format, whenever the ‘hour’ counter counts to 24, immediately,it resets to 0.

In addition, three features are equipped:
**Time adjustment.** Using a knob, values for three units could be adjusted, one at a time.
**Format switching.** A switch is used to switch between 12-hour and 24-hour format, and the LED should display different values for hour according to the format we set.
**The hour bell.** Whenever the ‘hour’ counts (but not due to the adjustment by the knob), the buzzer buzzes for the same times as the value of ‘hour’ in 12-hour
format, which signifies the hour (like the Big Ben).

### Simple digital 24h clock circuit (clock 24)
Just for simplicity, we created another file that contains a normal digital clock
that count from 00:00:00 to 23:59:59.

### Stopwatch circuit (stopwatch)
This stopwatch counts to only one minute (from 00 seconds to 59 seconds)
The switch Reset, resets the output to 00.
The switch Pause, stops the circuit ( As shown in the figure ).
The two switches works when they are closed.

### References
1. Wikipedia. 555 timer IC. https://en.wikipedia.org/wiki/555_timer_IC
2. Wikipedia. D flip-flop. https://en.wikipedia.org/wiki/Flip-flop_(electronics)#D_flipflop
3. Wikipedia. Seven-segment display. https://en.wikipedia.org/wiki/Seven-segment_display
4. Learn About Electronics. Digital Counters. http://www.learnabout-electronics.org/Digital/dig56.php
5. Thomas L. Floyd, Digital Fundamentals 9th Edition, Pearson Prentice Hall, Pearson Education International New Jersey, 2007.
6- Mark Balch, Digital Design – A comprehensive Guide to Digital Electronics and Computer System Architecture, McGraw-Hill Companies, Inc, New York, 2003.
