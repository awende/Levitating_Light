Levitating_Light
=============================================

[![Wireless Power Levitator](https://cdn.sparkfun.com/r/500-500/assets/home_page_posts/2/2/3/4/Wireless_Power_Levitator.jpg)](https://cdn.sparkfun.com/assets/home_page_posts/2/2/3/4/Wireless_Power_Levitator.jpg)


This repo is for the Levitating Light project. With the aid of a couple of magnets, you can create a light that floats in the air without any wires connected to it.

**Levitation Tips:**

- Build the levitation circuit first and get that system stable before starting wireless power transfer.
- Use the potentiometer to adjust the levitation set point.
- Secure the hall effect sensor between the magnets you want to levitate and the inductor.
- Adding mass to the levitated object will dampen the oscillations induced by the comparator.

**Wireless Power Transfer Tips:**

- Use a square wave generator to drive the N-Channel FET.
- Find the resonant frequency by sweeping through the frequencies (mine was around 200 kHz).
- Keep the magnetwire turns tight together to maximize efficiency.
