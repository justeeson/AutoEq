# Denon AH-D2000 B2012
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 1.4; 22 0.6; 23 0.2; 25 -0.4; 26 -0.6; 28 -1.0; 30 -1.2; 32 -1.4; 35 -1.4; 37 -1.5; 40 -1.5; 42 -1.5; 45 -1.4; 49 -1.1; 52 -1.0; 56 -0.9; 59 -0.9; 64 -0.8; 68 -0.7; 73 -0.7; 78 -0.9; 83 -1.0; 89 -1.3; 95 -1.6; 102 -1.9; 109 -2.1; 117 -2.5; 125 -2.9; 134 -3.3; 143 -3.5; 153 -3.5; 164 -3.4; 175 -3.5; 188 -3.6; 201 -3.6; 215 -3.6; 230 -3.5; 246 -3.4; 263 -3.4; 282 -3.4; 301 -3.3; 323 -3.2; 345 -3.1; 369 -3.0; 395 -2.8; 423 -2.7; 452 -2.7; 484 -3.0; 518 -3.2; 554 -2.9; 593 -2.5; 635 -2.4; 679 -1.3; 726 0.6; 777 0.2; 832 -0.4; 890 -0.6; 952 -0.3; 1019 -0.0; 1090 0.2; 1167 0.5; 1248 0.8; 1336 1.1; 1429 1.2; 1529 1.2; 1636 1.1; 1751 1.1; 1873 1.2; 2004 1.3; 2145 1.5; 2295 1.4; 2455 1.6; 2627 1.7; 2811 3.5; 3008 5.9; 3219 5.3; 3444 3.3; 3685 2.7; 3943 3.6; 4219 5.0; 4514 6.0; 4830 6.0; 5168 4.8; 5530 3.9; 5917 2.1; 6331 1.0; 6775 0.1; 7249 -0.6; 7756 -0.0; 8299 0.0; 8880 0.0; 9502 -0.0; 10167 -1.5; 10879 -2.4; 11640 -1.4; 12455 -0.1; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 -0.2
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 1.4; 22 0.6; 23 0.2; 25 -0.4; 26 -0.6; 28 -1.0; 30 -1.2; 32 -1.4; 35 -1.4; 37 -1.5; 40 -1.5; 42 -1.5; 45 -1.4; 49 -1.1; 52 -1.0; 56 -0.9; 59 -0.9; 64 -0.8; 68 -0.7; 73 -0.7; 78 -0.9; 83 -1.0; 89 -1.3; 95 -1.6; 102 -1.9; 109 -2.1; 117 -2.5; 125 -2.9; 134 -3.3; 143 -3.5; 153 -3.5; 164 -3.4; 175 -3.5; 188 -3.6; 201 -3.6; 215 -3.6; 230 -3.5; 246 -3.4; 263 -3.4; 282 -3.4; 301 -3.3; 323 -3.2; 345 -3.1; 369 -3.0; 395 -2.8; 423 -2.7; 452 -2.7; 484 -3.0; 518 -3.2; 554 -2.9; 593 -2.5; 635 -2.4; 679 -1.3; 726 0.6; 777 0.2; 832 -0.4; 890 -0.6; 952 -0.3; 1019 -0.0; 1090 0.2; 1167 0.5; 1248 0.8; 1336 1.1; 1429 1.2; 1529 1.2; 1636 1.1; 1751 1.1; 1873 1.2; 2004 1.3; 2145 1.5; 2295 1.4; 2455 1.6; 2627 1.7; 2811 3.5; 3008 5.9; 3219 5.3; 3444 3.3; 3685 2.7; 3943 3.6; 4219 5.0; 4514 6.0; 4830 6.0; 5168 4.8; 5530 3.9; 5917 2.1; 6331 1.0; 6775 0.1; 7249 -0.6; 7756 -0.0; 8299 0.0; 8880 0.0; 9502 -0.0; 10167 -1.5; 10879 -2.4; 11640 -1.4; 12455 -0.1; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 -0.2
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Denon%20AH-D2000%20B2012/Denon%20AH-D2000%20B2012.png)