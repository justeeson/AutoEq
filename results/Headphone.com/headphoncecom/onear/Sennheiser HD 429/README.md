# Sennheiser HD 429
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -1.7; 22 -1.9; 23 -2.0; 25 -2.1; 26 -2.2; 28 -2.2; 30 -2.3; 32 -2.4; 35 -2.5; 37 -2.5; 40 -2.5; 42 -2.5; 45 -2.5; 49 -2.4; 52 -2.3; 56 -2.2; 59 -2.1; 64 -1.9; 68 -1.8; 73 -1.5; 78 -1.2; 83 -0.8; 89 -0.1; 95 0.8; 102 0.4; 109 -1.6; 117 -2.6; 125 -3.3; 134 -3.7; 143 -3.9; 153 -3.5; 164 -3.2; 175 -3.9; 188 -3.8; 201 -3.6; 215 -3.8; 230 -3.6; 246 -3.2; 263 -2.4; 282 -1.6; 301 -1.1; 323 -0.9; 345 -0.6; 369 -0.6; 395 -0.8; 423 -0.8; 452 -0.8; 484 -1.0; 518 -1.1; 554 -1.1; 593 -1.0; 635 -0.8; 679 -0.9; 726 -0.9; 777 -0.8; 832 -0.6; 890 -0.4; 952 -0.1; 1019 -0.1; 1090 -0.3; 1167 -0.7; 1248 -0.3; 1336 0.9; 1429 1.1; 1529 1.5; 1636 1.8; 1751 2.3; 1873 3.0; 2004 3.7; 2145 4.9; 2295 5.9; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -1.7; 22 -1.9; 23 -2.0; 25 -2.1; 26 -2.2; 28 -2.2; 30 -2.3; 32 -2.4; 35 -2.5; 37 -2.5; 40 -2.5; 42 -2.5; 45 -2.5; 49 -2.4; 52 -2.3; 56 -2.2; 59 -2.1; 64 -1.9; 68 -1.8; 73 -1.5; 78 -1.2; 83 -0.8; 89 -0.1; 95 0.8; 102 0.4; 109 -1.6; 117 -2.6; 125 -3.3; 134 -3.7; 143 -3.9; 153 -3.5; 164 -3.2; 175 -3.9; 188 -3.8; 201 -3.6; 215 -3.8; 230 -3.6; 246 -3.2; 263 -2.4; 282 -1.6; 301 -1.1; 323 -0.9; 345 -0.6; 369 -0.6; 395 -0.8; 423 -0.8; 452 -0.8; 484 -1.0; 518 -1.1; 554 -1.1; 593 -1.0; 635 -0.8; 679 -0.9; 726 -0.9; 777 -0.8; 832 -0.6; 890 -0.4; 952 -0.1; 1019 -0.1; 1090 -0.3; 1167 -0.7; 1248 -0.3; 1336 0.9; 1429 1.1; 1529 1.5; 1636 1.8; 1751 2.3; 1873 3.0; 2004 3.7; 2145 4.9; 2295 5.9; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/headphoncecom/onear/Sennheiser%20HD%20429/Sennheiser%20HD%20429.png)