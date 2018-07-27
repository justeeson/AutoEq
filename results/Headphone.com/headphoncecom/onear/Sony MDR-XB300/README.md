# Sony MDR-XB300
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 5.6; 22 4.4; 23 3.8; 25 2.8; 26 2.4; 28 1.5; 30 0.8; 32 0.1; 35 -0.9; 37 -1.6; 40 -2.5; 42 -3.1; 45 -3.9; 49 -4.6; 52 -5.0; 56 -5.2; 59 -5.0; 64 -5.0; 68 -5.5; 73 -6.2; 78 -6.8; 83 -7.2; 89 -7.6; 95 -7.9; 102 -8.3; 109 -8.5; 117 -8.6; 125 -8.6; 134 -8.4; 143 -8.4; 153 -8.5; 164 -8.6; 175 -8.7; 188 -8.5; 201 -8.4; 215 -8.0; 230 -6.7; 246 -5.2; 263 -5.3; 282 -5.2; 301 -4.6; 323 -3.8; 345 -3.1; 369 -2.3; 395 -1.5; 423 -0.6; 452 0.3; 484 1.0; 518 1.7; 554 2.2; 593 2.7; 635 3.2; 679 3.4; 726 3.6; 777 3.5; 832 3.0; 890 2.0; 952 0.8; 1019 -0.2; 1090 -1.2; 1167 -1.3; 1248 -1.3; 1336 -2.0; 1429 -1.7; 1529 -1.4; 1636 -1.2; 1751 -1.4; 1873 -1.7; 2004 -1.8; 2145 -2.0; 2295 -1.7; 2455 -1.1; 2627 -0.2; 2811 0.8; 3008 2.1; 3219 3.2; 3444 4.3; 3685 5.4; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.8; 6331 3.1; 6775 3.6; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 5.6; 22 4.4; 23 3.8; 25 2.8; 26 2.4; 28 1.5; 30 0.8; 32 0.1; 35 -0.9; 37 -1.6; 40 -2.5; 42 -3.1; 45 -3.9; 49 -4.6; 52 -5.0; 56 -5.2; 59 -5.0; 64 -5.0; 68 -5.5; 73 -6.2; 78 -6.8; 83 -7.2; 89 -7.6; 95 -7.9; 102 -8.3; 109 -8.5; 117 -8.6; 125 -8.6; 134 -8.4; 143 -8.4; 153 -8.5; 164 -8.6; 175 -8.7; 188 -8.5; 201 -8.4; 215 -8.0; 230 -6.7; 246 -5.2; 263 -5.3; 282 -5.2; 301 -4.6; 323 -3.8; 345 -3.1; 369 -2.3; 395 -1.5; 423 -0.6; 452 0.3; 484 1.0; 518 1.7; 554 2.2; 593 2.7; 635 3.2; 679 3.4; 726 3.6; 777 3.5; 832 3.0; 890 2.0; 952 0.8; 1019 -0.2; 1090 -1.2; 1167 -1.3; 1248 -1.3; 1336 -2.0; 1429 -1.7; 1529 -1.4; 1636 -1.2; 1751 -1.4; 1873 -1.7; 2004 -1.8; 2145 -2.0; 2295 -1.7; 2455 -1.1; 2627 -0.2; 2811 0.8; 3008 2.1; 3219 3.2; 3444 4.3; 3685 5.4; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.8; 6331 3.1; 6775 3.6; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/headphoncecom/onear/Sony%20MDR-XB300/Sony%20MDR-XB300.png)