# Sennheiser RS 170
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-67**.
```
GraphicEQ: 10 -84; 20 6.7; 22 5.6; 23 5.2; 25 4.3; 26 3.9; 28 3.1; 30 2.5; 32 1.9; 35 1.2; 37 0.8; 40 0.2; 42 -0.2; 45 -0.7; 49 -1.2; 52 -1.5; 56 -1.9; 59 -2.1; 64 -2.3; 68 -2.6; 73 -3.0; 78 -3.2; 83 -3.0; 89 -3.0; 95 -2.7; 102 -2.8; 109 -3.3; 117 -4.2; 125 -5.2; 134 -5.8; 143 -6.1; 153 -6.3; 164 -6.0; 175 -5.8; 188 -6.2; 201 -6.0; 215 -5.3; 230 -4.4; 246 -4.0; 263 -3.6; 282 -3.3; 301 -2.7; 323 -2.1; 345 -1.7; 369 -1.4; 395 -1.5; 423 -1.7; 452 -1.8; 484 -1.7; 518 -1.3; 554 -0.6; 593 0.0; 635 0.4; 679 0.5; 726 0.7; 777 1.6; 832 2.6; 890 1.6; 952 0.4; 1019 -0.0; 1090 0.9; 1167 -0.1; 1248 -1.3; 1336 -2.2; 1429 -3.2; 1529 -4.2; 1636 -5.5; 1751 -4.3; 1873 -1.3; 2004 -3.2; 2145 -4.0; 2295 -4.4; 2455 -4.3; 2627 -4.2; 2811 -4.3; 3008 -3.6; 3219 -3.7; 3444 -3.5; 3685 -3.0; 3943 -1.4; 4219 0.3; 4514 4.5; 4830 6.0; 5168 2.5; 5530 2.0; 5917 2.1; 6331 0.3; 6775 -1.0; 7249 1.1; 7756 0.3; 8299 -1.3; 8880 -3.8; 9502 -4.8; 10167 -3.6; 10879 -0.8; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.7; 22 5.6; 23 5.2; 25 4.3; 26 3.9; 28 3.1; 30 2.5; 32 1.9; 35 1.2; 37 0.8; 40 0.2; 42 -0.2; 45 -0.7; 49 -1.2; 52 -1.5; 56 -1.9; 59 -2.1; 64 -2.3; 68 -2.6; 73 -3.0; 78 -3.2; 83 -3.0; 89 -3.0; 95 -2.7; 102 -2.8; 109 -3.3; 117 -4.2; 125 -5.2; 134 -5.8; 143 -6.1; 153 -6.3; 164 -6.0; 175 -5.8; 188 -6.2; 201 -6.0; 215 -5.3; 230 -4.4; 246 -4.0; 263 -3.6; 282 -3.3; 301 -2.7; 323 -2.1; 345 -1.7; 369 -1.4; 395 -1.5; 423 -1.7; 452 -1.8; 484 -1.7; 518 -1.3; 554 -0.6; 593 0.0; 635 0.4; 679 0.5; 726 0.7; 777 1.6; 832 2.6; 890 1.6; 952 0.4; 1019 -0.0; 1090 0.9; 1167 -0.1; 1248 -1.3; 1336 -2.2; 1429 -3.2; 1529 -4.2; 1636 -5.5; 1751 -4.3; 1873 -1.3; 2004 -3.2; 2145 -4.0; 2295 -4.4; 2455 -4.3; 2627 -4.2; 2811 -4.3; 3008 -3.6; 3219 -3.7; 3444 -3.5; 3685 -3.0; 3943 -1.4; 4219 0.3; 4514 4.5; 4830 6.0; 5168 2.5; 5530 2.0; 5917 2.1; 6331 0.3; 6775 -1.0; 7249 1.1; 7756 0.3; 8299 -1.3; 8880 -3.8; 9502 -4.8; 10167 -3.6; 10879 -0.8; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.7dB*l, R=-6.7dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/headphoncecom/onear/Sennheiser%20RS%20170/Sennheiser%20RS%20170.png)