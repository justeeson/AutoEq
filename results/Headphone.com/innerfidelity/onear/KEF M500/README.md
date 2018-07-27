# KEF M500
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -3.5; 22 -3.5; 23 -3.5; 25 -3.6; 26 -3.6; 28 -3.6; 30 -3.6; 32 -3.6; 35 -3.6; 37 -3.6; 40 -3.6; 42 -3.6; 45 -3.5; 49 -3.4; 52 -3.3; 56 -3.3; 59 -3.4; 64 -3.4; 68 -3.4; 73 -3.5; 78 -3.6; 83 -3.7; 89 -3.7; 95 -3.9; 102 -4.4; 109 -4.9; 117 -5.6; 125 -6.3; 134 -6.9; 143 -7.1; 153 -7.0; 164 -6.7; 175 -6.9; 188 -6.8; 201 -6.5; 215 -6.4; 230 -6.7; 246 -5.9; 263 -5.3; 282 -4.6; 301 -4.0; 323 -3.4; 345 -2.8; 369 -2.6; 395 -2.2; 423 -2.0; 452 -2.4; 484 -2.8; 518 -3.2; 554 -3.2; 593 -2.8; 635 -2.7; 679 -2.4; 726 -2.0; 777 -1.9; 832 -1.3; 890 -0.8; 952 -0.2; 1019 0.3; 1090 0.8; 1167 1.4; 1248 1.8; 1336 2.5; 1429 3.0; 1529 3.5; 1636 3.8; 1751 4.1; 1873 3.7; 2004 3.7; 2145 3.4; 2295 3.0; 2455 2.7; 2627 2.2; 2811 1.6; 3008 0.8; 3219 0.1; 3444 0.1; 3685 1.1; 3943 2.6; 4219 4.9; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -3.5; 22 -3.5; 23 -3.5; 25 -3.6; 26 -3.6; 28 -3.6; 30 -3.6; 32 -3.6; 35 -3.6; 37 -3.6; 40 -3.6; 42 -3.6; 45 -3.5; 49 -3.4; 52 -3.3; 56 -3.3; 59 -3.4; 64 -3.4; 68 -3.4; 73 -3.5; 78 -3.6; 83 -3.7; 89 -3.7; 95 -3.9; 102 -4.4; 109 -4.9; 117 -5.6; 125 -6.3; 134 -6.9; 143 -7.1; 153 -7.0; 164 -6.7; 175 -6.9; 188 -6.8; 201 -6.5; 215 -6.4; 230 -6.7; 246 -5.9; 263 -5.3; 282 -4.6; 301 -4.0; 323 -3.4; 345 -2.8; 369 -2.6; 395 -2.2; 423 -2.0; 452 -2.4; 484 -2.8; 518 -3.2; 554 -3.2; 593 -2.8; 635 -2.7; 679 -2.4; 726 -2.0; 777 -1.9; 832 -1.3; 890 -0.8; 952 -0.2; 1019 0.3; 1090 0.8; 1167 1.4; 1248 1.8; 1336 2.5; 1429 3.0; 1529 3.5; 1636 3.8; 1751 4.1; 1873 3.7; 2004 3.7; 2145 3.4; 2295 3.0; 2455 2.7; 2627 2.2; 2811 1.6; 3008 0.8; 3219 0.1; 3444 0.1; 3685 1.1; 3943 2.6; 4219 4.9; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/KEF%20M500/KEF%20M500.png)