# Sennheiser HD 219
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 3.8; 22 3.0; 23 2.7; 25 2.1; 26 1.8; 28 1.2; 30 0.7; 32 0.2; 35 -0.5; 37 -0.9; 40 -1.4; 42 -1.7; 45 -2.1; 49 -2.5; 52 -2.8; 56 -3.2; 59 -3.4; 64 -3.7; 68 -3.9; 73 -4.1; 78 -4.3; 83 -4.5; 89 -4.8; 95 -5.1; 102 -5.5; 109 -5.9; 117 -6.2; 125 -6.1; 134 -6.0; 143 -5.7; 153 -5.5; 164 -5.8; 175 -5.3; 188 -5.3; 201 -4.7; 215 -3.9; 230 -3.6; 246 -3.5; 263 -3.2; 282 -2.5; 301 -1.6; 323 -0.8; 345 -0.1; 369 0.3; 395 0.6; 423 0.9; 452 1.1; 484 1.2; 518 1.1; 554 1.1; 593 1.0; 635 1.0; 679 1.2; 726 1.7; 777 1.6; 832 1.1; 890 0.6; 952 0.2; 1019 -0.0; 1090 -0.1; 1167 0.2; 1248 0.7; 1336 1.6; 1429 2.5; 1529 3.5; 1636 3.2; 1751 1.8; 1873 1.8; 2004 2.2; 2145 2.6; 2295 3.0; 2455 3.4; 2627 3.5; 2811 3.4; 3008 3.1; 3219 2.8; 3444 2.7; 3685 2.5; 3943 2.5; 4219 2.3; 4514 3.1; 4830 5.1; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 3.8; 22 3.0; 23 2.7; 25 2.1; 26 1.8; 28 1.2; 30 0.7; 32 0.2; 35 -0.5; 37 -0.9; 40 -1.4; 42 -1.7; 45 -2.1; 49 -2.5; 52 -2.8; 56 -3.2; 59 -3.4; 64 -3.7; 68 -3.9; 73 -4.1; 78 -4.3; 83 -4.5; 89 -4.8; 95 -5.1; 102 -5.5; 109 -5.9; 117 -6.2; 125 -6.1; 134 -6.0; 143 -5.7; 153 -5.5; 164 -5.8; 175 -5.3; 188 -5.3; 201 -4.7; 215 -3.9; 230 -3.6; 246 -3.5; 263 -3.2; 282 -2.5; 301 -1.6; 323 -0.8; 345 -0.1; 369 0.3; 395 0.6; 423 0.9; 452 1.1; 484 1.2; 518 1.1; 554 1.1; 593 1.0; 635 1.0; 679 1.2; 726 1.7; 777 1.6; 832 1.1; 890 0.6; 952 0.2; 1019 -0.0; 1090 -0.1; 1167 0.2; 1248 0.7; 1336 1.6; 1429 2.5; 1529 3.5; 1636 3.2; 1751 1.8; 1873 1.8; 2004 2.2; 2145 2.6; 2295 3.0; 2455 3.4; 2627 3.5; 2811 3.4; 3008 3.1; 3219 2.8; 3444 2.7; 3685 2.5; 3943 2.5; 4219 2.3; 4514 3.1; 4830 5.1; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/Sennheiser%20HD%20219/Sennheiser%20HD%20219.png)