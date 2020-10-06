# Vital_radar

The GUI was developed for real time demonstration of the algorithms used in my thesis. It is also used to display signals from reference sensors(ECG and breath sensor) . 

I'm still working on refining the GUI and algorithm. The reference section hasn't been added because I haven't decided which format to display them.

# Videos of real time GUI
## Tools used

GUI: written with pyQt

Algorithms: written in python

## Descirption of the video:

1) After clicking on the connection, the radar starts working. The plot will starts after it collects a data length of 15s. 

2) At the beginning, the radar faces an empty chair, so there is no signal to show, when the person sits down, the data starts to show changes.

3) When the person is not moving, the plot starts to show regular vital signs. The result is more reliable when the breath plot is stable and regular.

4) To show the result vividly, the heart and wind picture changes its color accordingly. 

5) The values displayed on LCDs = frequency * 60 times/min. Two values are displayed: 

- Var_cal = Variability = Calculation based on the distance between adjacent peaks, showing the true variation.

- Fre_cal = Calculation based on FFT result of the entire data length(15s), not the true variation, but the average result of this data segment.


[![Watch the video](https://i9.ytimg.com/vi_webp/AHYHygv3Vs8/mqdefault.webp?sqp=CPyL8fsF&rs=AOn4CLCGie0GfQXQQ2QiMIauX15EkvrukQ)](https://youtu.be/AHYHygv3Vs8)
