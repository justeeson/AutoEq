# Sennheiser HD 380 Pro
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-45**.
```
GraphicEQ: 10 -84; 20 -9.6; 22 -9.7; 23 -9.8; 25 -9.8; 26 -9.9; 28 -9.9; 30 -9.9; 32 -9.8; 35 -9.7; 37 -9.6; 40 -9.4; 42 -9.2; 45 -8.9; 49 -8.4; 52 -7.9; 56 -7.4; 59 -6.9; 64 -5.9; 68 -5.1; 73 -4.3; 78 -3.0; 83 -1.3; 89 0.6; 95 1.7; 102 -0.0; 109 -2.6; 117 -2.9; 125 -2.6; 134 -4.0; 143 -4.8; 153 -3.6; 164 -1.2; 175 -2.0; 188 -1.4; 201 -0.1; 215 1.0; 230 1.6; 246 1.7; 263 1.6; 282 1.2; 301 0.7; 323 -0.3; 345 -0.9; 369 -1.5; 395 -2.0; 423 -2.2; 452 -2.3; 484 -2.4; 518 -2.4; 554 -2.1; 593 -1.6; 635 -1.3; 679 -1.1; 726 -0.9; 777 -0.5; 832 -0.4; 890 -0.1; 952 -0.1; 1019 0.0; 1090 0.1; 1167 0.4; 1248 0.4; 1336 0.4; 1429 0.3; 1529 0.0; 1636 -0.5; 1751 -1.6; 1873 -3.2; 2004 -4.0; 2145 -4.5; 2295 -4.0; 2455 -3.9; 2627 -2.5; 2811 -0.8; 3008 0.9; 3219 1.9; 3444 1.2; 3685 -1.0; 3943 -1.9; 4219 -2.8; 4514 -1.6; 4830 1.0; 5168 3.6; 5530 4.5; 5917 3.5; 6331 2.8; 6775 1.2; 7249 0.7; 7756 0.3; 8299 0.0; 8880 0.0; 9502 -0.2; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 -0.2; 20000 -0.4
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -9.6; 22 -9.7; 23 -9.8; 25 -9.8; 26 -9.9; 28 -9.9; 30 -9.9; 32 -9.8; 35 -9.7; 37 -9.6; 40 -9.4; 42 -9.2; 45 -8.9; 49 -8.4; 52 -7.9; 56 -7.4; 59 -6.9; 64 -5.9; 68 -5.1; 73 -4.3; 78 -3.0; 83 -1.3; 89 0.6; 95 1.7; 102 -0.0; 109 -2.6; 117 -2.9; 125 -2.6; 134 -4.0; 143 -4.8; 153 -3.6; 164 -1.2; 175 -2.0; 188 -1.4; 201 -0.1; 215 1.0; 230 1.6; 246 1.7; 263 1.6; 282 1.2; 301 0.7; 323 -0.3; 345 -0.9; 369 -1.5; 395 -2.0; 423 -2.2; 452 -2.3; 484 -2.4; 518 -2.4; 554 -2.1; 593 -1.6; 635 -1.3; 679 -1.1; 726 -0.9; 777 -0.5; 832 -0.4; 890 -0.1; 952 -0.1; 1019 0.0; 1090 0.1; 1167 0.4; 1248 0.4; 1336 0.4; 1429 0.3; 1529 0.0; 1636 -0.5; 1751 -1.6; 1873 -3.2; 2004 -4.0; 2145 -4.5; 2295 -4.0; 2455 -3.9; 2627 -2.5; 2811 -0.8; 3008 0.9; 3219 1.9; 3444 1.2; 3685 -1.0; 3943 -1.9; 4219 -2.8; 4514 -1.6; 4830 1.0; 5168 3.6; 5530 4.5; 5917 3.5; 6331 2.8; 6775 1.2; 7249 0.7; 7756 0.3; 8299 0.0; 8880 0.0; 9502 -0.2; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 -0.2; 20000 -0.4
Copy: L=-4.5dB*l, R=-4.5dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/Sennheiser%20HD%20380%20Pro/Sennheiser%20HD%20380%20Pro.png)