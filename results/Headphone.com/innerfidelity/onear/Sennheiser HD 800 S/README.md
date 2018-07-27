# Sennheiser HD 800 S
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-55**.
```
GraphicEQ: 10 -84; 20 4.3; 22 3.7; 23 3.4; 25 2.9; 26 2.7; 28 2.4; 30 2.0; 32 1.7; 35 1.4; 37 1.2; 40 1.0; 42 0.9; 45 0.8; 49 0.7; 52 0.7; 56 0.5; 59 0.5; 64 0.5; 68 0.5; 73 0.3; 78 -0.1; 83 -0.6; 89 -1.1; 95 -1.7; 102 -2.5; 109 -3.0; 117 -3.5; 125 -3.9; 134 -4.3; 143 -4.5; 153 -4.7; 164 -4.7; 175 -4.8; 188 -5.0; 201 -5.0; 215 -4.9; 230 -4.9; 246 -4.9; 263 -4.8; 282 -4.6; 301 -4.6; 323 -4.5; 345 -4.4; 369 -4.2; 395 -4.0; 423 -3.7; 452 -3.4; 484 -3.0; 518 -2.7; 554 -2.4; 593 -2.1; 635 -1.8; 679 -1.5; 726 -1.2; 777 -1.0; 832 -0.8; 890 -0.5; 952 -0.3; 1019 0.1; 1090 0.5; 1167 0.8; 1248 1.6; 1336 2.8; 1429 3.9; 1529 4.8; 1636 5.1; 1751 4.9; 1873 4.6; 2004 4.9; 2145 5.0; 2295 4.9; 2455 5.1; 2627 5.3; 2811 5.0; 3008 4.4; 3219 4.0; 3444 3.9; 3685 3.4; 3943 3.1; 4219 3.8; 4514 4.9; 4830 5.5; 5168 4.7; 5530 3.2; 5917 2.4; 6331 -1.6; 6775 -3.2; 7249 -2.4; 7756 -1.4; 8299 -0.1; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 4.3; 22 3.7; 23 3.4; 25 2.9; 26 2.7; 28 2.4; 30 2.0; 32 1.7; 35 1.4; 37 1.2; 40 1.0; 42 0.9; 45 0.8; 49 0.7; 52 0.7; 56 0.5; 59 0.5; 64 0.5; 68 0.5; 73 0.3; 78 -0.1; 83 -0.6; 89 -1.1; 95 -1.7; 102 -2.5; 109 -3.0; 117 -3.5; 125 -3.9; 134 -4.3; 143 -4.5; 153 -4.7; 164 -4.7; 175 -4.8; 188 -5.0; 201 -5.0; 215 -4.9; 230 -4.9; 246 -4.9; 263 -4.8; 282 -4.6; 301 -4.6; 323 -4.5; 345 -4.4; 369 -4.2; 395 -4.0; 423 -3.7; 452 -3.4; 484 -3.0; 518 -2.7; 554 -2.4; 593 -2.1; 635 -1.8; 679 -1.5; 726 -1.2; 777 -1.0; 832 -0.8; 890 -0.5; 952 -0.3; 1019 0.1; 1090 0.5; 1167 0.8; 1248 1.6; 1336 2.8; 1429 3.9; 1529 4.8; 1636 5.1; 1751 4.9; 1873 4.6; 2004 4.9; 2145 5.0; 2295 4.9; 2455 5.1; 2627 5.3; 2811 5.0; 3008 4.4; 3219 4.0; 3444 3.9; 3685 3.4; 3943 3.1; 4219 3.8; 4514 4.9; 4830 5.5; 5168 4.7; 5530 3.2; 5917 2.4; 6331 -1.6; 6775 -3.2; 7249 -2.4; 7756 -1.4; 8299 -0.1; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-5.5dB*l, R=-5.5dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/Sennheiser%20HD%20800%20S/Sennheiser%20HD%20800%20S.png)