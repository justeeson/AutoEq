# HiFiMAN HE-4
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 3.1; 22 2.9; 23 2.7; 25 2.5; 26 2.4; 28 2.2; 30 2.1; 32 2.0; 35 1.8; 37 1.7; 40 1.6; 42 1.6; 45 1.6; 49 1.6; 52 1.6; 56 1.6; 59 1.6; 64 1.5; 68 1.5; 73 1.4; 78 1.2; 83 0.9; 89 0.5; 95 0.3; 102 -0.4; 109 -0.8; 117 -1.2; 125 -1.5; 134 -1.9; 143 -2.1; 153 -2.4; 164 -2.6; 175 -2.7; 188 -3.0; 201 -3.1; 215 -3.3; 230 -3.4; 246 -3.5; 263 -3.5; 282 -3.3; 301 -2.9; 323 -2.3; 345 -1.8; 369 -1.6; 395 -1.4; 423 -1.5; 452 -1.6; 484 -1.5; 518 -1.3; 554 -0.8; 593 -0.7; 635 -0.5; 679 1.1; 726 2.4; 777 2.3; 832 1.7; 890 1.3; 952 0.7; 1019 0.2; 1090 1.6; 1167 2.4; 1248 2.2; 1336 2.8; 1429 3.8; 1529 4.5; 1636 5.2; 1751 5.9; 1873 5.9; 2004 5.8; 2145 5.1; 2295 5.0; 2455 5.2; 2627 4.5; 2811 3.8; 3008 2.6; 3219 1.3; 3444 0.6; 3685 0.1; 3943 -0.6; 4219 -0.9; 4514 -0.2; 4830 1.3; 5168 5.7; 5530 6.0; 5917 2.1; 6331 -3.1; 6775 -3.9; 7249 -4.1; 7756 -4.2; 8299 -5.4; 8880 -6.7; 9502 -5.5; 10167 -1.5; 10879 0.0; 11640 0.0; 12455 -0.0; 13327 -0.4; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 -0.2; 20000 -5.1
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 3.1; 22 2.9; 23 2.7; 25 2.5; 26 2.4; 28 2.2; 30 2.1; 32 2.0; 35 1.8; 37 1.7; 40 1.6; 42 1.6; 45 1.6; 49 1.6; 52 1.6; 56 1.6; 59 1.6; 64 1.5; 68 1.5; 73 1.4; 78 1.2; 83 0.9; 89 0.5; 95 0.3; 102 -0.4; 109 -0.8; 117 -1.2; 125 -1.5; 134 -1.9; 143 -2.1; 153 -2.4; 164 -2.6; 175 -2.7; 188 -3.0; 201 -3.1; 215 -3.3; 230 -3.4; 246 -3.5; 263 -3.5; 282 -3.3; 301 -2.9; 323 -2.3; 345 -1.8; 369 -1.6; 395 -1.4; 423 -1.5; 452 -1.6; 484 -1.5; 518 -1.3; 554 -0.8; 593 -0.7; 635 -0.5; 679 1.1; 726 2.4; 777 2.3; 832 1.7; 890 1.3; 952 0.7; 1019 0.2; 1090 1.6; 1167 2.4; 1248 2.2; 1336 2.8; 1429 3.8; 1529 4.5; 1636 5.2; 1751 5.9; 1873 5.9; 2004 5.8; 2145 5.1; 2295 5.0; 2455 5.2; 2627 4.5; 2811 3.8; 3008 2.6; 3219 1.3; 3444 0.6; 3685 0.1; 3943 -0.6; 4219 -0.9; 4514 -0.2; 4830 1.3; 5168 5.7; 5530 6.0; 5917 2.1; 6331 -3.1; 6775 -3.9; 7249 -4.1; 7756 -4.2; 8299 -5.4; 8880 -6.7; 9502 -5.5; 10167 -1.5; 10879 0.0; 11640 0.0; 12455 -0.0; 13327 -0.4; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 -0.2; 20000 -5.1
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/HiFiMAN%20HE-4/HiFiMAN%20HE-4.png)