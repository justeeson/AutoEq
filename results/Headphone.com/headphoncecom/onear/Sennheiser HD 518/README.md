# Sennheiser HD 518
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 5.7; 22 5.0; 23 4.6; 25 4.0; 26 3.7; 28 3.1; 30 2.6; 32 2.1; 35 1.5; 37 1.2; 40 0.7; 42 0.4; 45 0.1; 49 -0.3; 52 -0.6; 56 -1.0; 59 -1.2; 64 -1.6; 68 -1.8; 73 -2.0; 78 -2.3; 83 -2.5; 89 -2.1; 95 -1.8; 102 -2.8; 109 -3.8; 117 -4.5; 125 -5.2; 134 -5.6; 143 -5.8; 153 -6.2; 164 -6.0; 175 -6.0; 188 -6.2; 201 -6.1; 215 -5.9; 230 -5.9; 246 -5.9; 263 -5.8; 282 -5.5; 301 -5.4; 323 -5.2; 345 -4.9; 369 -4.8; 395 -4.4; 423 -4.1; 452 -3.7; 484 -3.4; 518 -2.7; 554 -2.2; 593 -1.9; 635 -1.8; 679 -1.7; 726 -1.5; 777 -0.6; 832 -0.8; 890 -0.7; 952 -0.1; 1019 0.1; 1090 0.8; 1167 1.7; 1248 2.4; 1336 4.0; 1429 5.5; 1529 6.0; 1636 6.0; 1751 6.0; 1873 6.0; 2004 5.9; 2145 5.1; 2295 5.2; 2455 5.3; 2627 4.6; 2811 3.8; 3008 2.8; 3219 1.9; 3444 2.7; 3685 3.6; 3943 4.0; 4219 2.5; 4514 2.3; 4830 3.7; 5168 4.8; 5530 5.2; 5917 5.5; 6331 5.4; 6775 3.8; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 5.7; 22 5.0; 23 4.6; 25 4.0; 26 3.7; 28 3.1; 30 2.6; 32 2.1; 35 1.5; 37 1.2; 40 0.7; 42 0.4; 45 0.1; 49 -0.3; 52 -0.6; 56 -1.0; 59 -1.2; 64 -1.6; 68 -1.8; 73 -2.0; 78 -2.3; 83 -2.5; 89 -2.1; 95 -1.8; 102 -2.8; 109 -3.8; 117 -4.5; 125 -5.2; 134 -5.6; 143 -5.8; 153 -6.2; 164 -6.0; 175 -6.0; 188 -6.2; 201 -6.1; 215 -5.9; 230 -5.9; 246 -5.9; 263 -5.8; 282 -5.5; 301 -5.4; 323 -5.2; 345 -4.9; 369 -4.8; 395 -4.4; 423 -4.1; 452 -3.7; 484 -3.4; 518 -2.7; 554 -2.2; 593 -1.9; 635 -1.8; 679 -1.7; 726 -1.5; 777 -0.6; 832 -0.8; 890 -0.7; 952 -0.1; 1019 0.1; 1090 0.8; 1167 1.7; 1248 2.4; 1336 4.0; 1429 5.5; 1529 6.0; 1636 6.0; 1751 6.0; 1873 6.0; 2004 5.9; 2145 5.1; 2295 5.2; 2455 5.3; 2627 4.6; 2811 3.8; 3008 2.8; 3219 1.9; 3444 2.7; 3685 3.6; 3943 4.0; 4219 2.5; 4514 2.3; 4830 3.7; 5168 4.8; 5530 5.2; 5917 5.5; 6331 5.4; 6775 3.8; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/headphoncecom/onear/Sennheiser%20HD%20518/Sennheiser%20HD%20518.png)