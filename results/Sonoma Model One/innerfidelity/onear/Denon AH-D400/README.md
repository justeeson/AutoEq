# Denon AH-D400
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 5.8; 45 5.5; 49 5.0; 52 4.7; 56 4.4; 59 4.3; 64 4.5; 68 4.8; 73 5.1; 78 5.2; 83 5.0; 89 4.3; 95 3.4; 102 2.3; 109 1.6; 117 0.9; 125 0.1; 134 -0.6; 143 -1.1; 153 -1.5; 164 -1.8; 175 -1.8; 188 -1.9; 201 -2.0; 215 -2.1; 230 -2.1; 246 -2.1; 263 -2.1; 282 -2.1; 301 -1.7; 323 -1.1; 345 -0.6; 369 0.3; 395 1.2; 423 2.4; 452 3.5; 484 4.4; 518 5.1; 554 5.4; 593 5.5; 635 5.3; 679 4.9; 726 4.2; 777 3.7; 832 2.6; 890 1.5; 952 0.6; 1019 -0.1; 1090 0.2; 1167 1.1; 1248 2.2; 1336 2.7; 1429 3.1; 1529 3.8; 1636 3.4; 1751 1.8; 1873 1.4; 2004 1.9; 2145 2.3; 2295 2.6; 2455 2.8; 2627 3.2; 2811 3.3; 3008 4.0; 3219 4.6; 3444 6.0; 3685 6.0; 3943 5.4; 4219 4.7; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 5.8; 45 5.5; 49 5.0; 52 4.7; 56 4.4; 59 4.3; 64 4.5; 68 4.8; 73 5.1; 78 5.2; 83 5.0; 89 4.3; 95 3.4; 102 2.3; 109 1.6; 117 0.9; 125 0.1; 134 -0.6; 143 -1.1; 153 -1.5; 164 -1.8; 175 -1.8; 188 -1.9; 201 -2.0; 215 -2.1; 230 -2.1; 246 -2.1; 263 -2.1; 282 -2.1; 301 -1.7; 323 -1.1; 345 -0.6; 369 0.3; 395 1.2; 423 2.4; 452 3.5; 484 4.4; 518 5.1; 554 5.4; 593 5.5; 635 5.3; 679 4.9; 726 4.2; 777 3.7; 832 2.6; 890 1.5; 952 0.6; 1019 -0.1; 1090 0.2; 1167 1.1; 1248 2.2; 1336 2.7; 1429 3.1; 1529 3.8; 1636 3.4; 1751 1.8; 1873 1.4; 2004 1.9; 2145 2.3; 2295 2.6; 2455 2.8; 2627 3.2; 2811 3.3; 3008 4.0; 3219 4.6; 3444 6.0; 3685 6.0; 3943 5.4; 4219 4.7; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Denon%20AH-D400/Denon%20AH-D400.png)