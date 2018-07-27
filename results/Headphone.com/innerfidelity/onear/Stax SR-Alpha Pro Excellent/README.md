# Stax SR-Alpha Pro Excellent
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 5.6; 52 4.6; 56 3.3; 59 2.6; 64 1.6; 68 0.4; 73 -1.5; 78 -2.8; 83 -3.3; 89 -3.2; 95 -3.3; 102 -3.6; 109 -3.4; 117 -3.1; 125 -2.8; 134 -2.6; 143 -2.5; 153 -2.3; 164 -2.1; 175 -1.9; 188 -1.7; 201 -1.5; 215 -1.4; 230 -1.2; 246 -1.1; 263 -1.0; 282 -0.8; 301 -0.8; 323 -0.7; 345 -0.7; 369 -0.6; 395 -0.5; 423 -0.3; 452 0.1; 484 0.3; 518 0.5; 554 0.6; 593 0.7; 635 0.8; 679 0.9; 726 0.9; 777 0.8; 832 0.6; 890 0.5; 952 0.2; 1019 -0.0; 1090 -0.1; 1167 -0.3; 1248 -0.4; 1336 -0.2; 1429 -0.0; 1529 0.1; 1636 -0.0; 1751 -0.2; 1873 -0.0; 2004 0.9; 2145 1.8; 2295 1.9; 2455 2.2; 2627 2.9; 2811 3.5; 3008 3.9; 3219 4.1; 3444 4.5; 3685 4.8; 3943 5.8; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 3.6; 6775 1.9; 7249 1.1; 7756 -0.2; 8299 -1.9; 8880 -2.9; 9502 -1.9; 10167 -0.1; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 5.6; 52 4.6; 56 3.3; 59 2.6; 64 1.6; 68 0.4; 73 -1.5; 78 -2.8; 83 -3.3; 89 -3.2; 95 -3.3; 102 -3.6; 109 -3.4; 117 -3.1; 125 -2.8; 134 -2.6; 143 -2.5; 153 -2.3; 164 -2.1; 175 -1.9; 188 -1.7; 201 -1.5; 215 -1.4; 230 -1.2; 246 -1.1; 263 -1.0; 282 -0.8; 301 -0.8; 323 -0.7; 345 -0.7; 369 -0.6; 395 -0.5; 423 -0.3; 452 0.1; 484 0.3; 518 0.5; 554 0.6; 593 0.7; 635 0.8; 679 0.9; 726 0.9; 777 0.8; 832 0.6; 890 0.5; 952 0.2; 1019 -0.0; 1090 -0.1; 1167 -0.3; 1248 -0.4; 1336 -0.2; 1429 -0.0; 1529 0.1; 1636 -0.0; 1751 -0.2; 1873 -0.0; 2004 0.9; 2145 1.8; 2295 1.9; 2455 2.2; 2627 2.9; 2811 3.5; 3008 3.9; 3219 4.1; 3444 4.5; 3685 4.8; 3943 5.8; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 3.6; 6775 1.9; 7249 1.1; 7756 -0.2; 8299 -1.9; 8880 -2.9; 9502 -1.9; 10167 -0.1; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/Stax%20SR-Alpha%20Pro%20Excellent/Stax%20SR-Alpha%20Pro%20Excellent.png)