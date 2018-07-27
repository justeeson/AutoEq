# Sennheiser Urbanite XL
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 0.5; 22 -0.2; 23 -0.5; 25 -1.1; 26 -1.3; 28 -1.7; 30 -2.1; 32 -2.4; 35 -2.8; 37 -3.1; 40 -3.4; 42 -3.6; 45 -3.9; 49 -4.1; 52 -4.3; 56 -4.5; 59 -4.7; 64 -4.9; 68 -5.0; 73 -5.2; 78 -5.5; 83 -5.8; 89 -6.2; 95 -6.6; 102 -7.0; 109 -7.2; 117 -7.3; 125 -7.4; 134 -7.6; 143 -8.3; 153 -8.7; 164 -8.0; 175 -7.5; 188 -7.8; 201 -7.6; 215 -7.2; 230 -6.7; 246 -6.3; 263 -6.2; 282 -6.5; 301 -6.8; 323 -6.9; 345 -6.8; 369 -6.3; 395 -5.5; 423 -4.6; 452 -4.2; 484 -3.8; 518 -3.1; 554 -2.4; 593 -1.9; 635 -1.5; 679 -1.3; 726 -1.1; 777 -0.9; 832 -0.7; 890 -0.5; 952 -0.2; 1019 0.1; 1090 0.1; 1167 0.1; 1248 0.3; 1336 0.6; 1429 1.0; 1529 1.2; 1636 1.2; 1751 1.0; 1873 0.7; 2004 0.8; 2145 1.3; 2295 2.4; 2455 3.3; 2627 3.8; 2811 4.4; 3008 5.0; 3219 4.9; 3444 5.2; 3685 5.9; 3943 6.0; 4219 6.0; 4514 6.0; 4830 5.0; 5168 4.3; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 0.5; 22 -0.2; 23 -0.5; 25 -1.1; 26 -1.3; 28 -1.7; 30 -2.1; 32 -2.4; 35 -2.8; 37 -3.1; 40 -3.4; 42 -3.6; 45 -3.9; 49 -4.1; 52 -4.3; 56 -4.5; 59 -4.7; 64 -4.9; 68 -5.0; 73 -5.2; 78 -5.5; 83 -5.8; 89 -6.2; 95 -6.6; 102 -7.0; 109 -7.2; 117 -7.3; 125 -7.4; 134 -7.6; 143 -8.3; 153 -8.7; 164 -8.0; 175 -7.5; 188 -7.8; 201 -7.6; 215 -7.2; 230 -6.7; 246 -6.3; 263 -6.2; 282 -6.5; 301 -6.8; 323 -6.9; 345 -6.8; 369 -6.3; 395 -5.5; 423 -4.6; 452 -4.2; 484 -3.8; 518 -3.1; 554 -2.4; 593 -1.9; 635 -1.5; 679 -1.3; 726 -1.1; 777 -0.9; 832 -0.7; 890 -0.5; 952 -0.2; 1019 0.1; 1090 0.1; 1167 0.1; 1248 0.3; 1336 0.6; 1429 1.0; 1529 1.2; 1636 1.2; 1751 1.0; 1873 0.7; 2004 0.8; 2145 1.3; 2295 2.4; 2455 3.3; 2627 3.8; 2811 4.4; 3008 5.0; 3219 4.9; 3444 5.2; 3685 5.9; 3943 6.0; 4219 6.0; 4514 6.0; 4830 5.0; 5168 4.3; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/Sennheiser%20Urbanite%20XL/Sennheiser%20Urbanite%20XL.png)