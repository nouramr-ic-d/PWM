# PWM
pulse with modulation(PWM) , which is a technique to control the amount of power you provide to certain analog devices.

- Pulse-Width Modulation, or PWM is a very common technique that varies the width of the pulses in a pulse-train. PWM has a few applications, the main ones are for controlling things like servos and speed controllers and limiting the effective power for things like motors and LEDs. This tutorial will cover how to use PWM to change the brightness of an LED. 
# This design depend on 
- Duty cycle
- Resolution
- switching frequency
# Main components of This design  
- up counter(R-bit)
- simple small combinational circuit which is just comparator : tells me if the inputs from the counter is actually less than comparator.

- duty cycle : is proportion of time that signal stays in the ON position versus the total period of the whole signal.

- Timer : to control frequency of up counter .

- D FF : to avoid glitches
