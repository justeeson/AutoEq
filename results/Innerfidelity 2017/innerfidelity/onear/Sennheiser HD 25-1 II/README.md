# Sennheiser HD 25-1 II
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 5.6; 59 5.1; 64 4.6; 68 4.2; 73 3.6; 78 3.3; 83 3.1; 89 3.1; 95 3.1; 102 1.9; 109 0.7; 117 -0.0; 125 -1.0; 134 -2.2; 143 -2.8; 153 -3.0; 164 -2.9; 175 -3.2; 188 -3.4; 201 -3.3; 215 -3.2; 230 -3.1; 246 -3.0; 263 -2.8; 282 -2.5; 301 -2.6; 323 -2.7; 345 -2.6; 369 -2.4; 395 -2.1; 423 -2.0; 452 -2.1; 484 -2.2; 518 -2.1; 554 -1.6; 593 -1.1; 635 -0.7; 679 -0.7; 726 -0.6; 777 -0.2; 832 -0.2; 890 -0.1; 952 -0.1; 1019 -0.0; 1090 -0.2; 1167 -0.4; 1248 -0.7; 1336 -1.0; 1429 -1.2; 1529 -1.5; 1636 -2.1; 1751 -2.7; 1873 -2.8; 2004 -2.9; 2145 -2.9; 2295 -2.4; 2455 -1.2; 2627 0.3; 2811 1.9; 3008 3.1; 3219 3.1; 3444 3.1; 3685 3.6; 3943 5.2; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -1.7; 8880 -3.2; 9502 -1.2; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 5.6; 59 5.1; 64 4.6; 68 4.2; 73 3.6; 78 3.3; 83 3.1; 89 3.1; 95 3.1; 102 1.9; 109 0.7; 117 -0.0; 125 -1.0; 134 -2.2; 143 -2.8; 153 -3.0; 164 -2.9; 175 -3.2; 188 -3.4; 201 -3.3; 215 -3.2; 230 -3.1; 246 -3.0; 263 -2.8; 282 -2.5; 301 -2.6; 323 -2.7; 345 -2.6; 369 -2.4; 395 -2.1; 423 -2.0; 452 -2.1; 484 -2.2; 518 -2.1; 554 -1.6; 593 -1.1; 635 -0.7; 679 -0.7; 726 -0.6; 777 -0.2; 832 -0.2; 890 -0.1; 952 -0.1; 1019 -0.0; 1090 -0.2; 1167 -0.4; 1248 -0.7; 1336 -1.0; 1429 -1.2; 1529 -1.5; 1636 -2.1; 1751 -2.7; 1873 -2.8; 2004 -2.9; 2145 -2.9; 2295 -2.4; 2455 -1.2; 2627 0.3; 2811 1.9; 3008 3.1; 3219 3.1; 3444 3.1; 3685 3.6; 3943 5.2; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -1.7; 8880 -3.2; 9502 -1.2; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Sennheiser%20HD%2025-1%20II/Sennheiser%20HD%2025-1%20II.png)