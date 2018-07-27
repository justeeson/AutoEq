# Sennheiser RS 220
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 5.8; 45 5.4; 49 4.9; 52 4.5; 56 4.1; 59 3.9; 64 4.1; 68 5.1; 73 5.7; 78 4.9; 83 4.2; 89 3.4; 95 2.4; 102 1.5; 109 0.8; 117 0.2; 125 -0.5; 134 -1.1; 143 -1.6; 153 -1.8; 164 -1.8; 175 -2.0; 188 -2.1; 201 -2.2; 215 -2.1; 230 -1.7; 246 -1.6; 263 -1.6; 282 -1.5; 301 -1.4; 323 -1.3; 345 -1.0; 369 -1.0; 395 -1.1; 423 -0.9; 452 -0.7; 484 -0.3; 518 -0.1; 554 0.0; 593 0.2; 635 0.6; 679 0.9; 726 1.3; 777 1.5; 832 1.3; 890 0.8; 952 0.3; 1019 -0.0; 1090 0.7; 1167 1.1; 1248 1.6; 1336 2.8; 1429 5.0; 1529 6.0; 1636 6.0; 1751 5.9; 1873 5.2; 2004 3.4; 2145 0.7; 2295 -1.9; 2455 -2.8; 2627 -2.1; 2811 -0.5; 3008 0.8; 3219 1.3; 3444 2.1; 3685 4.0; 3943 5.9; 4219 6.0; 4514 6.0; 4830 6.0; 5168 4.9; 5530 0.2; 5917 -0.2; 6331 3.4; 6775 0.8; 7249 -1.8; 7756 -1.5; 8299 -0.6; 8880 -0.5; 9502 -2.3; 10167 -4.5; 10879 -4.1; 11640 -0.9; 12455 0.0; 13327 0.0; 14260 -0.9; 15258 -1.9; 16326 -0.2; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 5.8; 45 5.4; 49 4.9; 52 4.5; 56 4.1; 59 3.9; 64 4.1; 68 5.1; 73 5.7; 78 4.9; 83 4.2; 89 3.4; 95 2.4; 102 1.5; 109 0.8; 117 0.2; 125 -0.5; 134 -1.1; 143 -1.6; 153 -1.8; 164 -1.8; 175 -2.0; 188 -2.1; 201 -2.2; 215 -2.1; 230 -1.7; 246 -1.6; 263 -1.6; 282 -1.5; 301 -1.4; 323 -1.3; 345 -1.0; 369 -1.0; 395 -1.1; 423 -0.9; 452 -0.7; 484 -0.3; 518 -0.1; 554 0.0; 593 0.2; 635 0.6; 679 0.9; 726 1.3; 777 1.5; 832 1.3; 890 0.8; 952 0.3; 1019 -0.0; 1090 0.7; 1167 1.1; 1248 1.6; 1336 2.8; 1429 5.0; 1529 6.0; 1636 6.0; 1751 5.9; 1873 5.2; 2004 3.4; 2145 0.7; 2295 -1.9; 2455 -2.8; 2627 -2.1; 2811 -0.5; 3008 0.8; 3219 1.3; 3444 2.1; 3685 4.0; 3943 5.9; 4219 6.0; 4514 6.0; 4830 6.0; 5168 4.9; 5530 0.2; 5917 -0.2; 6331 3.4; 6775 0.8; 7249 -1.8; 7756 -1.5; 8299 -0.6; 8880 -0.5; 9502 -2.3; 10167 -4.5; 10879 -4.1; 11640 -0.9; 12455 0.0; 13327 0.0; 14260 -0.9; 15258 -1.9; 16326 -0.2; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/headphoncecom/onear/Sennheiser%20RS%20220/Sennheiser%20RS%20220.png)