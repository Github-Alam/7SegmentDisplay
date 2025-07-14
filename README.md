# 7SegmentDisplay
Controlling the 7 Segment Display using 7 gpio of mcu

To control a 7-segment display, you need to activate the appropriate segments to form the desired character. This is typically done by sending signals to the display's segments (a-g, and sometimes dp for the decimal point). For single-digit displays, you'll need at least seven input/output (I/O) pins, and for multi-digit displays, you'll need an additional pin for each digit to control which digit is currently active. 
I have used here PA0 to PA6
