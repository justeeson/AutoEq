# Bose QC3
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -4.6; 22 -4.8; 23 -5.0; 25 -5.1; 26 -5.2; 28 -5.2; 30 -5.2; 32 -5.2; 35 -5.1; 37 -5.0; 40 -4.9; 42 -4.8; 45 -4.7; 49 -4.5; 52 -4.4; 56 -4.3; 59 -4.2; 64 -4.2; 68 -4.2; 73 -4.1; 78 -4.2; 83 -4.4; 89 -4.6; 95 -4.9; 102 -5.3; 109 -5.5; 117 -6.0; 125 -6.3; 134 -6.5; 143 -6.5; 153 -6.6; 164 -6.4; 175 -6.2; 188 -6.1; 201 -5.8; 215 -5.4; 230 -5.1; 246 -4.7; 263 -4.3; 282 -3.9; 301 -3.6; 323 -3.3; 345 -2.9; 369 -2.6; 395 -2.3; 423 -1.9; 452 -1.6; 484 -1.4; 518 -1.1; 554 -0.8; 593 -0.6; 635 -0.6; 679 -0.6; 726 -0.6; 777 -0.6; 832 -0.3; 890 -0.1; 952 0.1; 1019 -0.1; 1090 -0.2; 1167 -0.2; 1248 0.0; 1336 0.6; 1429 2.1; 1529 3.7; 1636 4.1; 1751 5.2; 1873 6.0; 2004 6.0; 2145 6.0; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 5.7; 3943 5.1; 4219 5.0; 4514 5.9; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -4.6; 22 -4.8; 23 -5.0; 25 -5.1; 26 -5.2; 28 -5.2; 30 -5.2; 32 -5.2; 35 -5.1; 37 -5.0; 40 -4.9; 42 -4.8; 45 -4.7; 49 -4.5; 52 -4.4; 56 -4.3; 59 -4.2; 64 -4.2; 68 -4.2; 73 -4.1; 78 -4.2; 83 -4.4; 89 -4.6; 95 -4.9; 102 -5.3; 109 -5.5; 117 -6.0; 125 -6.3; 134 -6.5; 143 -6.5; 153 -6.6; 164 -6.4; 175 -6.2; 188 -6.1; 201 -5.8; 215 -5.4; 230 -5.1; 246 -4.7; 263 -4.3; 282 -3.9; 301 -3.6; 323 -3.3; 345 -2.9; 369 -2.6; 395 -2.3; 423 -1.9; 452 -1.6; 484 -1.4; 518 -1.1; 554 -0.8; 593 -0.6; 635 -0.6; 679 -0.6; 726 -0.6; 777 -0.6; 832 -0.3; 890 -0.1; 952 0.1; 1019 -0.1; 1090 -0.2; 1167 -0.2; 1248 0.0; 1336 0.6; 1429 2.1; 1529 3.7; 1636 4.1; 1751 5.2; 1873 6.0; 2004 6.0; 2145 6.0; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 5.7; 3943 5.1; 4219 5.0; 4514 5.9; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/headphoncecom/onear/Bose%20QC3/Bose%20QC3.png)