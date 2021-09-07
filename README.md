# Register-Level-PWM-using-STM32F4-Discovery-Board
Timer 4 Output compare is used to generate the PWM Pulses. Channels 1-4 in timer 4 linked with PD12-PD15 are used for this purpose.
Duty cycles of 10%, 20%, 30% and 40% are selected for channels 1-4 respectively. It can be changed by modifying the CCRx register where x corresponds to channel number.
The total duration of the pulse is 10ms. This can be changed by varying the prescaler and autoreload value in timer configuration.
