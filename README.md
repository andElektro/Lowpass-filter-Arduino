# A2D-1-st-order-RC-lowpass-filter for Arduino
Analog to digital 1:st order RC lowpass filter template.
Choose cut off frequency and samplingtime.

Code ex.:

#include "LPfilter.h"

float fcut = 100; //

float T = 0.001;

LPfilter<float> LPf(fcut, T);

float Vout = 0;