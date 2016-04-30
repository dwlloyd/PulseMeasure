# PulseMeasure
PulseMeasure library for Arduino

The PulseMeasure library for Arduino was developed to provide an easy and reliable way to use external interrupts with pulse outputs from most any sensor or switching contacts. Designed to work with INT0 or INT1 in any interrupt mode (CHANGE, FALLING or RISING). 

It uses timer2 to provide false interrupt supression. Extremely noisy signals are completely recovered without impact on performance. The only requirement is to specify the minimum and maximum frequency of the signal. The signal needs to have a small portion of stability (both high and low) which is calculated from the maximum frequency specified.

Measured quantities for all interrupt modes are:

• Pulse Count
• Pulse Period (µs)
• Pulse Frequency (Hz)

Additional quantities with CHANGE mode:

• Pulse Width (µs)
• Pulse Duty Cycle (%)

Open Source License

PulseMeasure is free software. You can redistribute it and/or modify it under the terms of Creative Commons Attribution 3.0 United States License. To view a copy of this license, visit:  http://creativecommons.org/licenses/by/3.0/us/
