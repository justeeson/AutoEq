# AKG K240 Sextett
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 5.8; 35 5.1; 37 4.4; 40 3.5; 42 2.9; 45 2.1; 49 1.3; 52 0.7; 56 0.2; 59 0.1; 64 0.6; 68 0.4; 73 -1.1; 78 -2.9; 83 -4.3; 89 -5.4; 95 -6.2; 102 -6.9; 109 -7.5; 117 -8.0; 125 -8.2; 134 -8.1; 143 -8.2; 153 -8.0; 164 -7.0; 175 -6.1; 188 -6.6; 201 -7.1; 215 -6.9; 230 -6.6; 246 -6.3; 263 -5.9; 282 -5.5; 301 -5.3; 323 -5.0; 345 -4.5; 369 -4.2; 395 -4.0; 423 -3.6; 452 -3.0; 484 -2.3; 518 -2.3; 554 -2.5; 593 -2.3; 635 -1.8; 679 -1.4; 726 -1.1; 777 -0.8; 832 -0.5; 890 -0.2; 952 -0.0; 1019 -0.1; 1090 -0.2; 1167 -0.1; 1248 0.1; 1336 0.3; 1429 0.4; 1529 0.4; 1636 0.2; 1751 -0.1; 1873 -0.5; 2004 -0.8; 2145 -0.6; 2295 0.5; 2455 0.5; 2627 1.9; 2811 4.5; 3008 5.9; 3219 4.4; 3444 4.5; 3685 2.9; 3943 1.2; 4219 -1.6; 4514 -2.4; 4830 1.3; 5168 5.2; 5530 6.0; 5917 5.4; 6331 2.8; 6775 -0.7; 7249 -3.1; 7756 -5.2; 8299 -7.2; 8880 -8.3; 9502 -7.3; 10167 -3.1; 10879 -0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 5.8; 35 5.1; 37 4.4; 40 3.5; 42 2.9; 45 2.1; 49 1.3; 52 0.7; 56 0.2; 59 0.1; 64 0.6; 68 0.4; 73 -1.1; 78 -2.9; 83 -4.3; 89 -5.4; 95 -6.2; 102 -6.9; 109 -7.5; 117 -8.0; 125 -8.2; 134 -8.1; 143 -8.2; 153 -8.0; 164 -7.0; 175 -6.1; 188 -6.6; 201 -7.1; 215 -6.9; 230 -6.6; 246 -6.3; 263 -5.9; 282 -5.5; 301 -5.3; 323 -5.0; 345 -4.5; 369 -4.2; 395 -4.0; 423 -3.6; 452 -3.0; 484 -2.3; 518 -2.3; 554 -2.5; 593 -2.3; 635 -1.8; 679 -1.4; 726 -1.1; 777 -0.8; 832 -0.5; 890 -0.2; 952 -0.0; 1019 -0.1; 1090 -0.2; 1167 -0.1; 1248 0.1; 1336 0.3; 1429 0.4; 1529 0.4; 1636 0.2; 1751 -0.1; 1873 -0.5; 2004 -0.8; 2145 -0.6; 2295 0.5; 2455 0.5; 2627 1.9; 2811 4.5; 3008 5.9; 3219 4.4; 3444 4.5; 3685 2.9; 3943 1.2; 4219 -1.6; 4514 -2.4; 4830 1.3; 5168 5.2; 5530 6.0; 5917 5.4; 6331 2.8; 6775 -0.7; 7249 -3.1; 7756 -5.2; 8299 -7.2; 8880 -8.3; 9502 -7.3; 10167 -3.1; 10879 -0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/AKG%20K240%20Sextett/AKG%20K240%20Sextett.png)