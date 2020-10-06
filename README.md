# Vital_radar

This is part of the work done for my master thesis: Vital sign detection with radar. The GUI was developed for real time demonstration of the algorithms used in my thesis. 

# Videos of real time GUI
## Tools

Radar: single channel mm-wave FMCW radar

GUI: written with pyQt

Algorithms: written in python

## Descirption of the video:

1) After clicking on the connection, the radar starts working. The plot will starts after it collects a data length of **15s**. 

2) At the beginning, the radar faces an **empty chair**, so there is no signal to show, when the person sits down, the data starts to show changes.

3) When the person is not moving, the plot starts to show regular vital signs. The result is only reliable when the breath plot is stable and regular.

4) To show the result vividly, the heart and wind pictures change their color accordingly. 

5) The values displayed on LCDs = frequency * 60 times/min. Two values are displayed: 

- Var_cal = Variability = Calculation based on the distance between adjacent peaks, showing the true variation.

- Fre_cal = Calculation based on FFT result of the entire data length(15s), not the true variation, but the average result of this data segment.


Pls click on the 1-min video to see how it works. Thank you for the patience.


[![Watch the video](https://i9.ytimg.com/vi_webp/AHYHygv3Vs8/mqdefault.webp?sqp=CPyL8fsF&rs=AOn4CLCGie0GfQXQQ2QiMIauX15EkvrukQ)](https://youtu.be/AHYHygv3Vs8)

