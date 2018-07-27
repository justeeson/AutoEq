# beyerdynamic T50P
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 5.9; 28 5.7; 30 5.3; 32 4.8; 35 4.2; 37 3.8; 40 3.2; 42 2.9; 45 2.5; 49 1.9; 52 1.5; 56 0.9; 59 0.6; 64 1.2; 68 2.0; 73 1.5; 78 0.6; 83 0.1; 89 -0.5; 95 -0.5; 102 -0.6; 109 -1.1; 117 -1.2; 125 -1.1; 134 -0.9; 143 -0.3; 153 1.1; 164 2.5; 175 1.7; 188 -0.4; 201 -2.1; 215 -2.8; 230 -3.0; 246 -3.5; 263 -4.6; 282 -6.0; 301 -7.0; 323 -6.9; 345 -6.6; 369 -6.3; 395 -5.8; 423 -5.5; 452 -5.2; 484 -4.7; 518 -4.2; 554 -3.7; 593 -3.3; 635 -2.9; 679 -2.2; 726 -0.7; 777 -0.7; 832 -0.7; 890 -0.4; 952 -0.3; 1019 0.0; 1090 0.4; 1167 0.8; 1248 1.4; 1336 2.0; 1429 2.6; 1529 3.1; 1636 3.2; 1751 3.1; 1873 3.2; 2004 3.7; 2145 4.6; 2295 5.5; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 4.7; 6775 3.6; 7249 1.1; 7756 -3.0; 8299 -5.4; 8880 -5.1; 9502 -2.6; 10167 -0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 5.9; 28 5.7; 30 5.3; 32 4.8; 35 4.2; 37 3.8; 40 3.2; 42 2.9; 45 2.5; 49 1.9; 52 1.5; 56 0.9; 59 0.6; 64 1.2; 68 2.0; 73 1.5; 78 0.6; 83 0.1; 89 -0.5; 95 -0.5; 102 -0.6; 109 -1.1; 117 -1.2; 125 -1.1; 134 -0.9; 143 -0.3; 153 1.1; 164 2.5; 175 1.7; 188 -0.4; 201 -2.1; 215 -2.8; 230 -3.0; 246 -3.5; 263 -4.6; 282 -6.0; 301 -7.0; 323 -6.9; 345 -6.6; 369 -6.3; 395 -5.8; 423 -5.5; 452 -5.2; 484 -4.7; 518 -4.2; 554 -3.7; 593 -3.3; 635 -2.9; 679 -2.2; 726 -0.7; 777 -0.7; 832 -0.7; 890 -0.4; 952 -0.3; 1019 0.0; 1090 0.4; 1167 0.8; 1248 1.4; 1336 2.0; 1429 2.6; 1529 3.1; 1636 3.2; 1751 3.1; 1873 3.2; 2004 3.7; 2145 4.6; 2295 5.5; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 4.7; 6775 3.6; 7249 1.1; 7756 -3.0; 8299 -5.4; 8880 -5.1; 9502 -2.6; 10167 -0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/headphoncecom/onear/beyerdynamic%20T50P/beyerdynamic%20T50P.png)