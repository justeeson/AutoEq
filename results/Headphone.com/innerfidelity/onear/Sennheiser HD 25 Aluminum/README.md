# Sennheiser HD 25 Aluminum
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -3.8; 22 -4.1; 23 -4.3; 25 -4.5; 26 -4.6; 28 -4.8; 30 -4.9; 32 -5.0; 35 -5.2; 37 -5.2; 40 -5.3; 42 -5.3; 45 -5.3; 49 -5.2; 52 -5.1; 56 -5.0; 59 -4.9; 64 -4.8; 68 -4.7; 73 -4.5; 78 -4.1; 83 -3.8; 89 -4.2; 95 -5.2; 102 -6.7; 109 -7.6; 117 -8.3; 125 -8.5; 134 -8.3; 143 -8.1; 153 -7.6; 164 -6.8; 175 -7.0; 188 -6.1; 201 -5.3; 215 -4.8; 230 -4.0; 246 -3.1; 263 -2.0; 282 -1.1; 301 -0.4; 323 0.1; 345 0.5; 369 0.9; 395 1.2; 423 1.4; 452 1.4; 484 1.3; 518 1.3; 554 1.2; 593 1.2; 635 1.2; 679 1.1; 726 1.0; 777 0.8; 832 0.6; 890 0.4; 952 0.1; 1019 -0.1; 1090 -0.2; 1167 -0.2; 1248 -0.2; 1336 -0.0; 1429 0.0; 1529 -0.2; 1636 -0.6; 1751 -1.0; 1873 -1.4; 2004 -1.6; 2145 -1.2; 2295 -0.5; 2455 0.5; 2627 1.7; 2811 2.6; 3008 3.0; 3219 3.1; 3444 2.7; 3685 2.5; 3943 2.8; 4219 4.6; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 -1.3; 8299 -4.3; 8880 -4.5; 9502 -1.5; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -3.8; 22 -4.1; 23 -4.3; 25 -4.5; 26 -4.6; 28 -4.8; 30 -4.9; 32 -5.0; 35 -5.2; 37 -5.2; 40 -5.3; 42 -5.3; 45 -5.3; 49 -5.2; 52 -5.1; 56 -5.0; 59 -4.9; 64 -4.8; 68 -4.7; 73 -4.5; 78 -4.1; 83 -3.8; 89 -4.2; 95 -5.2; 102 -6.7; 109 -7.6; 117 -8.3; 125 -8.5; 134 -8.3; 143 -8.1; 153 -7.6; 164 -6.8; 175 -7.0; 188 -6.1; 201 -5.3; 215 -4.8; 230 -4.0; 246 -3.1; 263 -2.0; 282 -1.1; 301 -0.4; 323 0.1; 345 0.5; 369 0.9; 395 1.2; 423 1.4; 452 1.4; 484 1.3; 518 1.3; 554 1.2; 593 1.2; 635 1.2; 679 1.1; 726 1.0; 777 0.8; 832 0.6; 890 0.4; 952 0.1; 1019 -0.1; 1090 -0.2; 1167 -0.2; 1248 -0.2; 1336 -0.0; 1429 0.0; 1529 -0.2; 1636 -0.6; 1751 -1.0; 1873 -1.4; 2004 -1.6; 2145 -1.2; 2295 -0.5; 2455 0.5; 2627 1.7; 2811 2.6; 3008 3.0; 3219 3.1; 3444 2.7; 3685 2.5; 3943 2.8; 4219 4.6; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 -1.3; 8299 -4.3; 8880 -4.5; 9502 -1.5; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/Sennheiser%20HD%2025%20Aluminum/Sennheiser%20HD%2025%20Aluminum.png)