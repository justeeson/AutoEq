# Sennheiser PXC350
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 3.3; 22 2.5; 23 2.2; 25 1.6; 26 1.4; 28 1.0; 30 0.7; 32 0.6; 35 0.5; 37 0.5; 40 0.5; 42 0.5; 45 0.6; 49 0.8; 52 0.9; 56 1.1; 59 1.3; 64 1.5; 68 1.5; 73 1.7; 78 1.9; 83 1.9; 89 1.7; 95 1.2; 102 0.8; 109 0.6; 117 0.2; 125 -0.0; 134 -0.2; 143 -0.3; 153 -0.3; 164 0.1; 175 0.2; 188 0.3; 201 0.6; 215 0.9; 230 0.9; 246 0.7; 263 0.6; 282 0.5; 301 0.4; 323 0.2; 345 0.1; 369 -0.2; 395 -0.4; 423 -0.6; 452 -0.8; 484 -1.0; 518 -1.1; 554 -1.0; 593 -0.8; 635 -0.8; 679 -0.7; 726 -0.5; 777 -0.3; 832 0.0; 890 0.2; 952 -0.0; 1019 0.1; 1090 0.3; 1167 0.6; 1248 0.9; 1336 1.3; 1429 1.6; 1529 1.5; 1636 0.7; 1751 -0.5; 1873 -1.0; 2004 3.3; 2145 6.0; 2295 5.9; 2455 0.4; 2627 -2.3; 2811 -0.0; 3008 3.1; 3219 4.9; 3444 4.8; 3685 4.6; 3943 5.9; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.3; 6331 2.8; 6775 0.7; 7249 0.9; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 3.3; 22 2.5; 23 2.2; 25 1.6; 26 1.4; 28 1.0; 30 0.7; 32 0.6; 35 0.5; 37 0.5; 40 0.5; 42 0.5; 45 0.6; 49 0.8; 52 0.9; 56 1.1; 59 1.3; 64 1.5; 68 1.5; 73 1.7; 78 1.9; 83 1.9; 89 1.7; 95 1.2; 102 0.8; 109 0.6; 117 0.2; 125 -0.0; 134 -0.2; 143 -0.3; 153 -0.3; 164 0.1; 175 0.2; 188 0.3; 201 0.6; 215 0.9; 230 0.9; 246 0.7; 263 0.6; 282 0.5; 301 0.4; 323 0.2; 345 0.1; 369 -0.2; 395 -0.4; 423 -0.6; 452 -0.8; 484 -1.0; 518 -1.1; 554 -1.0; 593 -0.8; 635 -0.8; 679 -0.7; 726 -0.5; 777 -0.3; 832 0.0; 890 0.2; 952 -0.0; 1019 0.1; 1090 0.3; 1167 0.6; 1248 0.9; 1336 1.3; 1429 1.6; 1529 1.5; 1636 0.7; 1751 -0.5; 1873 -1.0; 2004 3.3; 2145 6.0; 2295 5.9; 2455 0.4; 2627 -2.3; 2811 -0.0; 3008 3.1; 3219 4.9; 3444 4.8; 3685 4.6; 3943 5.9; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.3; 6331 2.8; 6775 0.7; 7249 0.9; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/headphoncecom/onear/Sennheiser%20PXC350/Sennheiser%20PXC350.png)