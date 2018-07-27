# KRK KNS 8400
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-29**.
```
GraphicEQ: 10 -84; 20 2.3; 22 1.9; 23 1.7; 25 1.4; 26 1.3; 28 1.2; 30 1.1; 32 1.1; 35 1.2; 37 1.3; 40 1.6; 42 1.7; 45 1.9; 49 1.9; 52 1.8; 56 1.9; 59 2.0; 64 2.2; 68 2.0; 73 1.3; 78 0.2; 83 -1.0; 89 -2.4; 95 -3.7; 102 -5.2; 109 -6.2; 117 -7.1; 125 -8.0; 134 -8.3; 143 -8.1; 153 -7.7; 164 -7.3; 175 -8.7; 188 -8.7; 201 -8.3; 215 -7.8; 230 -7.0; 246 -6.4; 263 -5.9; 282 -5.3; 301 -4.5; 323 -3.6; 345 -2.7; 369 -1.8; 395 -0.9; 423 -0.0; 452 0.2; 484 -0.2; 518 -0.9; 554 -1.5; 593 -1.8; 635 -1.6; 679 -1.1; 726 -0.1; 777 -0.5; 832 -1.1; 890 -0.6; 952 -0.3; 1019 0.0; 1090 -0.0; 1167 -0.3; 1248 -0.6; 1336 -1.2; 1429 -1.6; 1529 -2.4; 1636 -3.6; 1751 -4.9; 1873 -5.5; 2004 -6.0; 2145 -6.6; 2295 -6.9; 2455 -7.1; 2627 -7.1; 2811 -6.4; 3008 -4.5; 3219 -4.3; 3444 -4.5; 3685 -3.6; 3943 -2.1; 4219 -0.4; 4514 1.5; 4830 2.8; 5168 2.3; 5530 1.5; 5917 0.4; 6331 -0.7; 6775 -1.0; 7249 -0.3; 7756 -0.2; 8299 -1.8; 8880 -4.1; 9502 -5.1; 10167 -3.9; 10879 -1.4; 11640 -0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 -0.7; 20000 -2.1
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 2.3; 22 1.9; 23 1.7; 25 1.4; 26 1.3; 28 1.2; 30 1.1; 32 1.1; 35 1.2; 37 1.3; 40 1.6; 42 1.7; 45 1.9; 49 1.9; 52 1.8; 56 1.9; 59 2.0; 64 2.2; 68 2.0; 73 1.3; 78 0.2; 83 -1.0; 89 -2.4; 95 -3.7; 102 -5.2; 109 -6.2; 117 -7.1; 125 -8.0; 134 -8.3; 143 -8.1; 153 -7.7; 164 -7.3; 175 -8.7; 188 -8.7; 201 -8.3; 215 -7.8; 230 -7.0; 246 -6.4; 263 -5.9; 282 -5.3; 301 -4.5; 323 -3.6; 345 -2.7; 369 -1.8; 395 -0.9; 423 -0.0; 452 0.2; 484 -0.2; 518 -0.9; 554 -1.5; 593 -1.8; 635 -1.6; 679 -1.1; 726 -0.1; 777 -0.5; 832 -1.1; 890 -0.6; 952 -0.3; 1019 0.0; 1090 -0.0; 1167 -0.3; 1248 -0.6; 1336 -1.2; 1429 -1.6; 1529 -2.4; 1636 -3.6; 1751 -4.9; 1873 -5.5; 2004 -6.0; 2145 -6.6; 2295 -6.9; 2455 -7.1; 2627 -7.1; 2811 -6.4; 3008 -4.5; 3219 -4.3; 3444 -4.5; 3685 -3.6; 3943 -2.1; 4219 -0.4; 4514 1.5; 4830 2.8; 5168 2.3; 5530 1.5; 5917 0.4; 6331 -0.7; 6775 -1.0; 7249 -0.3; 7756 -0.2; 8299 -1.8; 8880 -4.1; 9502 -5.1; 10167 -3.9; 10879 -1.4; 11640 -0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 -0.7; 20000 -2.1
Copy: L=-2.9dB*l, R=-2.9dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/KRK%20KNS%208400/KRK%20KNS%208400.png)