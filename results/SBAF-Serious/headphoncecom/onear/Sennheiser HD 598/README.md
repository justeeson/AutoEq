# Sennheiser HD 598
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 5.8; 35 5.4; 37 5.1; 40 4.6; 42 4.4; 45 4.0; 49 3.6; 52 3.4; 56 3.0; 59 2.9; 64 3.0; 68 2.8; 73 2.3; 78 2.5; 83 3.0; 89 2.2; 95 1.3; 102 0.6; 109 0.2; 117 -0.3; 125 -0.9; 134 -1.3; 143 -1.5; 153 -1.9; 164 -2.0; 175 -2.0; 188 -2.1; 201 -2.1; 215 -2.0; 230 -1.9; 246 -2.0; 263 -2.1; 282 -2.1; 301 -2.0; 323 -1.9; 345 -1.7; 369 -1.6; 395 -1.5; 423 -1.3; 452 -1.3; 484 -1.3; 518 -1.2; 554 -0.8; 593 -0.8; 635 -1.0; 679 0.7; 726 0.0; 777 -0.2; 832 -0.4; 890 -0.2; 952 0.1; 1019 -0.0; 1090 -0.1; 1167 0.1; 1248 -0.2; 1336 -0.1; 1429 -0.0; 1529 0.2; 1636 1.1; 1751 1.2; 1873 1.2; 2004 1.0; 2145 0.6; 2295 1.2; 2455 2.0; 2627 1.0; 2811 0.0; 3008 0.4; 3219 -0.4; 3444 -0.5; 3685 -0.1; 3943 0.1; 4219 -2.4; 4514 -4.0; 4830 -3.2; 5168 -1.4; 5530 -0.5; 5917 -0.1; 6331 -0.1; 6775 0.2; 7249 0.7; 7756 0.3; 8299 -0.5; 8880 -1.4; 9502 -0.2; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 -0.0; 17469 -2.2; 18692 -4.8; 20000 -5.4
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 5.8; 35 5.4; 37 5.1; 40 4.6; 42 4.4; 45 4.0; 49 3.6; 52 3.4; 56 3.0; 59 2.9; 64 3.0; 68 2.8; 73 2.3; 78 2.5; 83 3.0; 89 2.2; 95 1.3; 102 0.6; 109 0.2; 117 -0.3; 125 -0.9; 134 -1.3; 143 -1.5; 153 -1.9; 164 -2.0; 175 -2.0; 188 -2.1; 201 -2.1; 215 -2.0; 230 -1.9; 246 -2.0; 263 -2.1; 282 -2.1; 301 -2.0; 323 -1.9; 345 -1.7; 369 -1.6; 395 -1.5; 423 -1.3; 452 -1.3; 484 -1.3; 518 -1.2; 554 -0.8; 593 -0.8; 635 -1.0; 679 0.7; 726 0.0; 777 -0.2; 832 -0.4; 890 -0.2; 952 0.1; 1019 -0.0; 1090 -0.1; 1167 0.1; 1248 -0.2; 1336 -0.1; 1429 -0.0; 1529 0.2; 1636 1.1; 1751 1.2; 1873 1.2; 2004 1.0; 2145 0.6; 2295 1.2; 2455 2.0; 2627 1.0; 2811 0.0; 3008 0.4; 3219 -0.4; 3444 -0.5; 3685 -0.1; 3943 0.1; 4219 -2.4; 4514 -4.0; 4830 -3.2; 5168 -1.4; 5530 -0.5; 5917 -0.1; 6331 -0.1; 6775 0.2; 7249 0.7; 7756 0.3; 8299 -0.5; 8880 -1.4; 9502 -0.2; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 -0.0; 17469 -2.2; 18692 -4.8; 20000 -5.4
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/headphoncecom/onear/Sennheiser%20HD%20598/Sennheiser%20HD%20598.png)