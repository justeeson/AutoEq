# Denon AH-D2000 B2012
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 4.7; 22 4.0; 23 3.6; 25 3.1; 26 2.9; 28 2.5; 30 2.3; 32 2.1; 35 2.0; 37 1.9; 40 1.8; 42 1.7; 45 1.7; 49 1.7; 52 1.7; 56 1.6; 59 1.6; 64 2.0; 68 2.4; 73 2.9; 78 3.1; 83 2.8; 89 2.1; 95 1.3; 102 0.5; 109 0.0; 117 -0.6; 125 -1.2; 134 -1.8; 143 -2.3; 153 -2.4; 164 -2.5; 175 -2.6; 188 -2.7; 201 -2.7; 215 -2.7; 230 -2.7; 246 -2.6; 263 -2.5; 282 -2.4; 301 -2.3; 323 -2.2; 345 -2.0; 369 -1.8; 395 -1.6; 423 -1.4; 452 -1.1; 484 -1.1; 518 -1.4; 554 -1.6; 593 -1.4; 635 -1.2; 679 0.2; 726 2.4; 777 1.8; 832 0.8; 890 0.2; 952 -0.1; 1019 0.0; 1090 0.7; 1167 1.9; 1248 2.9; 1336 3.6; 1429 3.9; 1529 3.8; 1636 3.2; 1751 2.7; 1873 2.3; 2004 2.4; 2145 2.5; 2295 2.5; 2455 2.7; 2627 2.8; 2811 4.5; 3008 6.0; 3219 5.7; 3444 3.5; 3685 1.8; 3943 1.1; 4219 1.3; 4514 2.5; 4830 3.7; 5168 2.4; 5530 1.0; 5917 -1.2; 6331 -1.3; 6775 -0.8; 7249 -1.0; 7756 -0.2; 8299 0.0; 8880 0.0; 9502 -1.6; 10167 -4.7; 10879 -5.2; 11640 -3.4; 12455 -1.8; 13327 -1.6; 14260 -1.8; 15258 -1.5; 16326 -1.3; 17469 -1.8; 18692 -2.1; 20000 -0.9
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 4.7; 22 4.0; 23 3.6; 25 3.1; 26 2.9; 28 2.5; 30 2.3; 32 2.1; 35 2.0; 37 1.9; 40 1.8; 42 1.7; 45 1.7; 49 1.7; 52 1.7; 56 1.6; 59 1.6; 64 2.0; 68 2.4; 73 2.9; 78 3.1; 83 2.8; 89 2.1; 95 1.3; 102 0.5; 109 0.0; 117 -0.6; 125 -1.2; 134 -1.8; 143 -2.3; 153 -2.4; 164 -2.5; 175 -2.6; 188 -2.7; 201 -2.7; 215 -2.7; 230 -2.7; 246 -2.6; 263 -2.5; 282 -2.4; 301 -2.3; 323 -2.2; 345 -2.0; 369 -1.8; 395 -1.6; 423 -1.4; 452 -1.1; 484 -1.1; 518 -1.4; 554 -1.6; 593 -1.4; 635 -1.2; 679 0.2; 726 2.4; 777 1.8; 832 0.8; 890 0.2; 952 -0.1; 1019 0.0; 1090 0.7; 1167 1.9; 1248 2.9; 1336 3.6; 1429 3.9; 1529 3.8; 1636 3.2; 1751 2.7; 1873 2.3; 2004 2.4; 2145 2.5; 2295 2.5; 2455 2.7; 2627 2.8; 2811 4.5; 3008 6.0; 3219 5.7; 3444 3.5; 3685 1.8; 3943 1.1; 4219 1.3; 4514 2.5; 4830 3.7; 5168 2.4; 5530 1.0; 5917 -1.2; 6331 -1.3; 6775 -0.8; 7249 -1.0; 7756 -0.2; 8299 0.0; 8880 0.0; 9502 -1.6; 10167 -4.7; 10879 -5.2; 11640 -3.4; 12455 -1.8; 13327 -1.6; 14260 -1.8; 15258 -1.5; 16326 -1.3; 17469 -1.8; 18692 -2.1; 20000 -0.9
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Denon%20AH-D2000%20B2012/Denon%20AH-D2000%20B2012.png)