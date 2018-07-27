# HiFiMAN HE-500
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-55**.
```
GraphicEQ: 10 -84; 20 5.5; 22 5.1; 23 4.9; 25 4.7; 26 4.5; 28 4.3; 30 4.1; 32 4.0; 35 3.8; 37 3.7; 40 3.6; 42 3.6; 45 3.5; 49 3.3; 52 3.2; 56 3.0; 59 2.7; 64 2.9; 68 3.4; 73 3.9; 78 4.2; 83 4.1; 89 3.3; 95 2.7; 102 2.0; 109 1.4; 117 1.1; 125 0.4; 134 -0.2; 143 -0.6; 153 -0.8; 164 -1.2; 175 -1.1; 188 -1.3; 201 -1.2; 215 -1.3; 230 -1.5; 246 -1.6; 263 -1.8; 282 -1.7; 301 -1.6; 323 -1.5; 345 -1.5; 369 -1.6; 395 -1.4; 423 -1.2; 452 -1.3; 484 -1.4; 518 -1.0; 554 -1.2; 593 -1.1; 635 -0.5; 679 -0.1; 726 1.1; 777 1.7; 832 1.2; 890 0.2; 952 0.3; 1019 -0.1; 1090 0.2; 1167 1.4; 1248 2.3; 1336 3.5; 1429 3.9; 1529 3.6; 1636 3.4; 1751 3.6; 1873 3.7; 2004 3.8; 2145 2.7; 2295 1.9; 2455 3.6; 2627 3.7; 2811 3.0; 3008 2.2; 3219 1.7; 3444 1.0; 3685 1.1; 3943 0.4; 4219 -1.2; 4514 -1.6; 4830 -0.6; 5168 1.1; 5530 0.6; 5917 -1.2; 6331 -2.0; 6775 -1.6; 7249 -1.2; 7756 -1.7; 8299 -4.1; 8880 -7.0; 9502 -7.7; 10167 -5.1; 10879 -1.4; 11640 -0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 -0.2; 16326 -2.8; 17469 -5.5; 18692 -6.0; 20000 -4.1
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 5.5; 22 5.1; 23 4.9; 25 4.7; 26 4.5; 28 4.3; 30 4.1; 32 4.0; 35 3.8; 37 3.7; 40 3.6; 42 3.6; 45 3.5; 49 3.3; 52 3.2; 56 3.0; 59 2.7; 64 2.9; 68 3.4; 73 3.9; 78 4.2; 83 4.1; 89 3.3; 95 2.7; 102 2.0; 109 1.4; 117 1.1; 125 0.4; 134 -0.2; 143 -0.6; 153 -0.8; 164 -1.2; 175 -1.1; 188 -1.3; 201 -1.2; 215 -1.3; 230 -1.5; 246 -1.6; 263 -1.8; 282 -1.7; 301 -1.6; 323 -1.5; 345 -1.5; 369 -1.6; 395 -1.4; 423 -1.2; 452 -1.3; 484 -1.4; 518 -1.0; 554 -1.2; 593 -1.1; 635 -0.5; 679 -0.1; 726 1.1; 777 1.7; 832 1.2; 890 0.2; 952 0.3; 1019 -0.1; 1090 0.2; 1167 1.4; 1248 2.3; 1336 3.5; 1429 3.9; 1529 3.6; 1636 3.4; 1751 3.6; 1873 3.7; 2004 3.8; 2145 2.7; 2295 1.9; 2455 3.6; 2627 3.7; 2811 3.0; 3008 2.2; 3219 1.7; 3444 1.0; 3685 1.1; 3943 0.4; 4219 -1.2; 4514 -1.6; 4830 -0.6; 5168 1.1; 5530 0.6; 5917 -1.2; 6331 -2.0; 6775 -1.6; 7249 -1.2; 7756 -1.7; 8299 -4.1; 8880 -7.0; 9502 -7.7; 10167 -5.1; 10879 -1.4; 11640 -0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 -0.2; 16326 -2.8; 17469 -5.5; 18692 -6.0; 20000 -4.1
Copy: L=-5.5dB*l, R=-5.5dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/headphoncecom/onear/HiFiMAN%20HE-500/HiFiMAN%20HE-500.png)