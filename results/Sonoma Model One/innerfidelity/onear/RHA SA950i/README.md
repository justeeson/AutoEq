# RHA SA950i
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -2.7; 22 -3.1; 23 -3.3; 25 -3.6; 26 -3.8; 28 -3.9; 30 -4.1; 32 -4.1; 35 -4.2; 37 -4.3; 40 -4.4; 42 -4.5; 45 -4.6; 49 -4.7; 52 -4.8; 56 -4.8; 59 -4.7; 64 -4.3; 68 -3.9; 73 -3.4; 78 -3.1; 83 -3.2; 89 -3.5; 95 -4.0; 102 -4.7; 109 -5.3; 117 -5.6; 125 -6.2; 134 -6.9; 143 -7.5; 153 -7.9; 164 -7.9; 175 -8.0; 188 -8.2; 201 -8.1; 215 -7.9; 230 -7.8; 246 -7.8; 263 -7.8; 282 -7.7; 301 -7.8; 323 -8.1; 345 -8.2; 369 -8.4; 395 -8.4; 423 -8.2; 452 -7.9; 484 -7.8; 518 -7.5; 554 -7.2; 593 -6.5; 635 -5.6; 679 -4.3; 726 -2.8; 777 -1.7; 832 -0.8; 890 -0.5; 952 -0.4; 1019 0.1; 1090 -0.0; 1167 -0.2; 1248 -1.0; 1336 -1.9; 1429 -2.7; 1529 -2.9; 1636 -3.2; 1751 -3.3; 1873 -2.6; 2004 -1.3; 2145 -0.0; 2295 0.8; 2455 2.1; 2627 3.2; 2811 3.9; 3008 4.6; 3219 5.7; 3444 5.2; 3685 4.9; 3943 5.8; 4219 6.0; 4514 6.0; 4830 2.0; 5168 -1.9; 5530 -3.3; 5917 -0.1; 6331 2.8; 6775 3.1; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -2.7; 22 -3.1; 23 -3.3; 25 -3.6; 26 -3.8; 28 -3.9; 30 -4.1; 32 -4.1; 35 -4.2; 37 -4.3; 40 -4.4; 42 -4.5; 45 -4.6; 49 -4.7; 52 -4.8; 56 -4.8; 59 -4.7; 64 -4.3; 68 -3.9; 73 -3.4; 78 -3.1; 83 -3.2; 89 -3.5; 95 -4.0; 102 -4.7; 109 -5.3; 117 -5.6; 125 -6.2; 134 -6.9; 143 -7.5; 153 -7.9; 164 -7.9; 175 -8.0; 188 -8.2; 201 -8.1; 215 -7.9; 230 -7.8; 246 -7.8; 263 -7.8; 282 -7.7; 301 -7.8; 323 -8.1; 345 -8.2; 369 -8.4; 395 -8.4; 423 -8.2; 452 -7.9; 484 -7.8; 518 -7.5; 554 -7.2; 593 -6.5; 635 -5.6; 679 -4.3; 726 -2.8; 777 -1.7; 832 -0.8; 890 -0.5; 952 -0.4; 1019 0.1; 1090 -0.0; 1167 -0.2; 1248 -1.0; 1336 -1.9; 1429 -2.7; 1529 -2.9; 1636 -3.2; 1751 -3.3; 1873 -2.6; 2004 -1.3; 2145 -0.0; 2295 0.8; 2455 2.1; 2627 3.2; 2811 3.9; 3008 4.6; 3219 5.7; 3444 5.2; 3685 4.9; 3943 5.8; 4219 6.0; 4514 6.0; 4830 2.0; 5168 -1.9; 5530 -3.3; 5917 -0.1; 6331 2.8; 6775 3.1; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/RHA%20SA950i/RHA%20SA950i.png)