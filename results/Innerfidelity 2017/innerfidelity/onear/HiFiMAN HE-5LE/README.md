# HiFiMAN HE-5LE
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-55**.
```
GraphicEQ: 10 -84; 20 3.8; 22 2.3; 23 1.7; 25 0.8; 26 0.5; 28 0.1; 30 -0.0; 32 0.0; 35 0.2; 37 0.3; 40 0.5; 42 0.6; 45 0.8; 49 1.0; 52 1.2; 56 1.3; 59 1.2; 64 1.1; 68 1.1; 73 1.1; 78 1.2; 83 1.1; 89 0.8; 95 0.5; 102 0.2; 109 -0.1; 117 -0.5; 125 -1.3; 134 -2.0; 143 -2.6; 153 -3.2; 164 -3.6; 175 -3.8; 188 -3.9; 201 -4.1; 215 -4.1; 230 -4.2; 246 -4.4; 263 -4.5; 282 -4.6; 301 -4.6; 323 -4.6; 345 -4.7; 369 -4.7; 395 -4.7; 423 -4.6; 452 -4.8; 484 -4.9; 518 -4.8; 554 -4.7; 593 -4.0; 635 -2.3; 679 -1.6; 726 -0.1; 777 0.9; 832 0.8; 890 0.4; 952 0.0; 1019 -0.1; 1090 0.3; 1167 0.9; 1248 1.6; 1336 2.3; 1429 3.4; 1529 4.1; 1636 4.4; 1751 5.0; 1873 5.4; 2004 4.2; 2145 3.3; 2295 3.0; 2455 4.2; 2627 3.9; 2811 3.4; 3008 3.2; 3219 2.9; 3444 3.1; 3685 3.6; 3943 3.4; 4219 2.7; 4514 3.5; 4830 0.2; 5168 1.7; 5530 1.7; 5917 -2.8; 6331 -4.0; 6775 -4.1; 7249 -3.9; 7756 -4.4; 8299 -5.9; 8880 -7.2; 9502 -6.7; 10167 -4.4; 10879 -2.2; 11640 -1.0; 12455 -0.2; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 -0.2; 20000 -0.4
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 3.8; 22 2.3; 23 1.7; 25 0.8; 26 0.5; 28 0.1; 30 -0.0; 32 0.0; 35 0.2; 37 0.3; 40 0.5; 42 0.6; 45 0.8; 49 1.0; 52 1.2; 56 1.3; 59 1.2; 64 1.1; 68 1.1; 73 1.1; 78 1.2; 83 1.1; 89 0.8; 95 0.5; 102 0.2; 109 -0.1; 117 -0.5; 125 -1.3; 134 -2.0; 143 -2.6; 153 -3.2; 164 -3.6; 175 -3.8; 188 -3.9; 201 -4.1; 215 -4.1; 230 -4.2; 246 -4.4; 263 -4.5; 282 -4.6; 301 -4.6; 323 -4.6; 345 -4.7; 369 -4.7; 395 -4.7; 423 -4.6; 452 -4.8; 484 -4.9; 518 -4.8; 554 -4.7; 593 -4.0; 635 -2.3; 679 -1.6; 726 -0.1; 777 0.9; 832 0.8; 890 0.4; 952 0.0; 1019 -0.1; 1090 0.3; 1167 0.9; 1248 1.6; 1336 2.3; 1429 3.4; 1529 4.1; 1636 4.4; 1751 5.0; 1873 5.4; 2004 4.2; 2145 3.3; 2295 3.0; 2455 4.2; 2627 3.9; 2811 3.4; 3008 3.2; 3219 2.9; 3444 3.1; 3685 3.6; 3943 3.4; 4219 2.7; 4514 3.5; 4830 0.2; 5168 1.7; 5530 1.7; 5917 -2.8; 6331 -4.0; 6775 -4.1; 7249 -3.9; 7756 -4.4; 8299 -5.9; 8880 -7.2; 9502 -6.7; 10167 -4.4; 10879 -2.2; 11640 -1.0; 12455 -0.2; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 -0.2; 20000 -0.4
Copy: L=-5.5dB*l, R=-5.5dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/HiFiMAN%20HE-5LE/HiFiMAN%20HE-5LE.png)