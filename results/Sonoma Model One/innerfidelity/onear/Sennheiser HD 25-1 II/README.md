# Sennheiser HD 25-1 II
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 5.8; 102 4.3; 109 2.9; 117 1.9; 125 0.7; 134 -0.7; 143 -1.6; 153 -1.9; 164 -1.9; 175 -2.4; 188 -2.5; 201 -2.4; 215 -2.3; 230 -2.2; 246 -2.1; 263 -1.9; 282 -1.6; 301 -1.6; 323 -1.6; 345 -1.4; 369 -1.2; 395 -0.9; 423 -0.7; 452 -0.5; 484 -0.3; 518 -0.3; 554 -0.2; 593 -0.0; 635 0.4; 679 0.9; 726 1.2; 777 1.4; 832 1.1; 890 0.6; 952 0.2; 1019 0.0; 1090 0.4; 1167 1.0; 1248 1.4; 1336 1.6; 1429 1.5; 1529 1.1; 1636 0.1; 1751 -1.1; 1873 -1.7; 2004 -1.9; 2145 -1.8; 2295 -1.4; 2455 -0.1; 2627 1.4; 2811 2.9; 3008 3.9; 3219 3.7; 3444 3.3; 3685 2.7; 3943 2.7; 4219 2.5; 4514 2.8; 4830 4.6; 5168 5.0; 5530 3.0; 5917 3.2; 6331 5.3; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -2.4; 8880 -4.7; 9502 -3.8; 10167 -2.2; 10879 -1.7; 11640 -2.0; 12455 -1.4; 13327 -0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 5.8; 102 4.3; 109 2.9; 117 1.9; 125 0.7; 134 -0.7; 143 -1.6; 153 -1.9; 164 -1.9; 175 -2.4; 188 -2.5; 201 -2.4; 215 -2.3; 230 -2.2; 246 -2.1; 263 -1.9; 282 -1.6; 301 -1.6; 323 -1.6; 345 -1.4; 369 -1.2; 395 -0.9; 423 -0.7; 452 -0.5; 484 -0.3; 518 -0.3; 554 -0.2; 593 -0.0; 635 0.4; 679 0.9; 726 1.2; 777 1.4; 832 1.1; 890 0.6; 952 0.2; 1019 0.0; 1090 0.4; 1167 1.0; 1248 1.4; 1336 1.6; 1429 1.5; 1529 1.1; 1636 0.1; 1751 -1.1; 1873 -1.7; 2004 -1.9; 2145 -1.8; 2295 -1.4; 2455 -0.1; 2627 1.4; 2811 2.9; 3008 3.9; 3219 3.7; 3444 3.3; 3685 2.7; 3943 2.7; 4219 2.5; 4514 2.8; 4830 4.6; 5168 5.0; 5530 3.0; 5917 3.2; 6331 5.3; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -2.4; 8880 -4.7; 9502 -3.8; 10167 -2.2; 10879 -1.7; 11640 -2.0; 12455 -1.4; 13327 -0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Sennheiser%20HD%2025-1%20II/Sennheiser%20HD%2025-1%20II.png)