# Vital_radar

This is part of the work done for my master thesis: Vital sign detection with radar. The GUI was developed for real time demonstration of the algorithms used in my thesis. 

# Videos of real time GUI
## Tools

Radar: single channel mm-wave FMCW radar

GUI: written with pyQt

Algorithms: written in python, 

## Highlights

It can show relatively accurate real-time heart and breath rate variability, not just frequency.


## Descirption of the video:

1) After clicking on the connection, the radar starts working. The plot will starts after it collects a data length of **10s**. 

2) At the beginning, the radar faces an **empty chair**, so there is no signal to show, when the person sits down, the data starts to show changes.

3) When the person is not moving, the plot starts to show regular vital signs. The result is only reliable when the breath plot is stable and regular.

4) To show the result vividly, the heart and wind pictures change their color accordingly. 

5) Two values displayed on LCDs are displayed: 

- SDSD = Variability = standard derivation of the differnece of the distance between adjacent peaks, showing the true variation.

- HR(BR) =Heart(breath) Rate= Calculation based on FFT result of the entire data length(10s), not the true variation, but the average result of this data segment(more accurate).

Pls click on the 1-minute video to see how it works. 


[![Watch the video](https://youtu.be/eP6wCq-hCbI)



