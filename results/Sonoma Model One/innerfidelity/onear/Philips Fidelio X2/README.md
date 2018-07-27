# Philips Fidelio X2
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-69**.
```
GraphicEQ: 10 -84; 20 6.9; 22 6.0; 23 5.6; 25 4.7; 26 4.4; 28 3.6; 30 3.0; 32 2.3; 35 1.4; 37 0.9; 40 0.1; 42 -0.4; 45 -1.0; 49 -1.7; 52 -2.2; 56 -2.6; 59 -2.7; 64 -2.5; 68 -2.2; 73 -1.7; 78 -1.4; 83 -1.5; 89 -1.8; 95 -2.3; 102 -2.7; 109 -2.8; 117 -2.8; 125 -3.0; 134 -3.3; 143 -3.5; 153 -3.6; 164 -3.5; 175 -3.1; 188 -3.1; 201 -3.4; 215 -4.2; 230 -4.6; 246 -4.0; 263 -3.6; 282 -3.3; 301 -3.1; 323 -3.0; 345 -2.8; 369 -2.8; 395 -2.8; 423 -2.6; 452 -2.4; 484 -2.4; 518 -2.5; 554 -2.4; 593 -2.4; 635 -2.0; 679 -1.7; 726 -1.2; 777 -0.8; 832 -0.9; 890 -0.5; 952 -0.2; 1019 0.1; 1090 1.1; 1167 2.6; 1248 3.2; 1336 2.8; 1429 1.9; 1529 0.7; 1636 -0.1; 1751 -0.8; 1873 -0.9; 2004 -0.6; 2145 -0.5; 2295 -0.7; 2455 0.1; 2627 1.7; 2811 5.0; 3008 4.4; 3219 2.7; 3444 2.5; 3685 1.0; 3943 -0.1; 4219 -1.7; 4514 -3.9; 4830 -3.0; 5168 0.8; 5530 5.2; 5917 3.2; 6331 5.0; 6775 3.9; 7249 1.3; 7756 -0.9; 8299 -5.2; 8880 -8.2; 9502 -8.2; 10167 -4.9; 10879 -0.6; 11640 0.0; 12455 0.0; 13327 0.0; 14260 -0.7; 15258 -0.9; 16326 -0.9; 17469 -1.3; 18692 -0.6; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.9; 22 6.0; 23 5.6; 25 4.7; 26 4.4; 28 3.6; 30 3.0; 32 2.3; 35 1.4; 37 0.9; 40 0.1; 42 -0.4; 45 -1.0; 49 -1.7; 52 -2.2; 56 -2.6; 59 -2.7; 64 -2.5; 68 -2.2; 73 -1.7; 78 -1.4; 83 -1.5; 89 -1.8; 95 -2.3; 102 -2.7; 109 -2.8; 117 -2.8; 125 -3.0; 134 -3.3; 143 -3.5; 153 -3.6; 164 -3.5; 175 -3.1; 188 -3.1; 201 -3.4; 215 -4.2; 230 -4.6; 246 -4.0; 263 -3.6; 282 -3.3; 301 -3.1; 323 -3.0; 345 -2.8; 369 -2.8; 395 -2.8; 423 -2.6; 452 -2.4; 484 -2.4; 518 -2.5; 554 -2.4; 593 -2.4; 635 -2.0; 679 -1.7; 726 -1.2; 777 -0.8; 832 -0.9; 890 -0.5; 952 -0.2; 1019 0.1; 1090 1.1; 1167 2.6; 1248 3.2; 1336 2.8; 1429 1.9; 1529 0.7; 1636 -0.1; 1751 -0.8; 1873 -0.9; 2004 -0.6; 2145 -0.5; 2295 -0.7; 2455 0.1; 2627 1.7; 2811 5.0; 3008 4.4; 3219 2.7; 3444 2.5; 3685 1.0; 3943 -0.1; 4219 -1.7; 4514 -3.9; 4830 -3.0; 5168 0.8; 5530 5.2; 5917 3.2; 6331 5.0; 6775 3.9; 7249 1.3; 7756 -0.9; 8299 -5.2; 8880 -8.2; 9502 -8.2; 10167 -4.9; 10879 -0.6; 11640 0.0; 12455 0.0; 13327 0.0; 14260 -0.7; 15258 -0.9; 16326 -0.9; 17469 -1.3; 18692 -0.6; 20000 0.0
Copy: L=-6.9dB*l, R=-6.9dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Philips%20Fidelio%20X2/Philips%20Fidelio%20X2.png)