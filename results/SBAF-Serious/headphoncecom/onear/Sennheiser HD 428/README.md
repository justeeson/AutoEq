# Sennheiser HD 428
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 5.7; 95 4.6; 102 3.3; 109 2.5; 117 1.7; 125 1.0; 134 0.7; 143 0.5; 153 0.4; 164 0.6; 175 0.9; 188 1.1; 201 1.3; 215 1.5; 230 2.2; 246 2.2; 263 1.5; 282 1.7; 301 1.8; 323 1.7; 345 1.5; 369 1.6; 395 1.7; 423 1.8; 452 1.8; 484 1.8; 518 1.9; 554 2.2; 593 2.4; 635 2.1; 679 1.3; 726 0.9; 777 0.5; 832 0.1; 890 -0.1; 952 -0.1; 1019 0.1; 1090 1.7; 1167 1.6; 1248 0.1; 1336 -0.6; 1429 -0.8; 1529 -1.1; 1636 -1.8; 1751 -2.1; 1873 -1.8; 2004 -1.2; 2145 -0.0; 2295 1.7; 2455 2.7; 2627 2.5; 2811 2.9; 3008 3.2; 3219 3.2; 3444 3.0; 3685 2.4; 3943 3.6; 4219 6.0; 4514 6.0; 4830 6.0; 5168 4.4; 5530 3.4; 5917 4.8; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 5.7; 95 4.6; 102 3.3; 109 2.5; 117 1.7; 125 1.0; 134 0.7; 143 0.5; 153 0.4; 164 0.6; 175 0.9; 188 1.1; 201 1.3; 215 1.5; 230 2.2; 246 2.2; 263 1.5; 282 1.7; 301 1.8; 323 1.7; 345 1.5; 369 1.6; 395 1.7; 423 1.8; 452 1.8; 484 1.8; 518 1.9; 554 2.2; 593 2.4; 635 2.1; 679 1.3; 726 0.9; 777 0.5; 832 0.1; 890 -0.1; 952 -0.1; 1019 0.1; 1090 1.7; 1167 1.6; 1248 0.1; 1336 -0.6; 1429 -0.8; 1529 -1.1; 1636 -1.8; 1751 -2.1; 1873 -1.8; 2004 -1.2; 2145 -0.0; 2295 1.7; 2455 2.7; 2627 2.5; 2811 2.9; 3008 3.2; 3219 3.2; 3444 3.0; 3685 2.4; 3943 3.6; 4219 6.0; 4514 6.0; 4830 6.0; 5168 4.4; 5530 3.4; 5917 4.8; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/headphoncecom/onear/Sennheiser%20HD%20428/Sennheiser%20HD%20428.png)