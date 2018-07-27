# Denon AH-D1001K Silver
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 5.8; 45 5.4; 49 4.9; 52 4.7; 56 4.6; 59 4.5; 64 4.2; 68 3.9; 73 3.5; 78 3.1; 83 2.8; 89 2.6; 95 2.2; 102 1.8; 109 1.5; 117 1.4; 125 1.1; 134 1.1; 143 1.2; 153 1.2; 164 1.2; 175 1.3; 188 1.6; 201 1.9; 215 2.1; 230 2.1; 246 2.1; 263 2.2; 282 2.5; 301 2.6; 323 2.9; 345 3.2; 369 3.4; 395 3.7; 423 3.9; 452 4.0; 484 3.9; 518 4.0; 554 4.0; 593 3.9; 635 3.3; 679 2.5; 726 1.7; 777 1.0; 832 0.4; 890 0.0; 952 -0.1; 1019 0.0; 1090 0.3; 1167 0.7; 1248 0.9; 1336 0.9; 1429 1.0; 1529 1.1; 1636 1.3; 1751 1.6; 1873 2.3; 2004 3.0; 2145 3.6; 2295 4.3; 2455 4.7; 2627 4.5; 2811 3.7; 3008 3.4; 3219 2.5; 3444 2.3; 3685 5.3; 3943 3.6; 4219 0.0; 4514 -0.5; 4830 0.2; 5168 2.9; 5530 5.7; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.4; 9502 -2.7; 10167 -2.9; 10879 -0.4; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 5.8; 45 5.4; 49 4.9; 52 4.7; 56 4.6; 59 4.5; 64 4.2; 68 3.9; 73 3.5; 78 3.1; 83 2.8; 89 2.6; 95 2.2; 102 1.8; 109 1.5; 117 1.4; 125 1.1; 134 1.1; 143 1.2; 153 1.2; 164 1.2; 175 1.3; 188 1.6; 201 1.9; 215 2.1; 230 2.1; 246 2.1; 263 2.2; 282 2.5; 301 2.6; 323 2.9; 345 3.2; 369 3.4; 395 3.7; 423 3.9; 452 4.0; 484 3.9; 518 4.0; 554 4.0; 593 3.9; 635 3.3; 679 2.5; 726 1.7; 777 1.0; 832 0.4; 890 0.0; 952 -0.1; 1019 0.0; 1090 0.3; 1167 0.7; 1248 0.9; 1336 0.9; 1429 1.0; 1529 1.1; 1636 1.3; 1751 1.6; 1873 2.3; 2004 3.0; 2145 3.6; 2295 4.3; 2455 4.7; 2627 4.5; 2811 3.7; 3008 3.4; 3219 2.5; 3444 2.3; 3685 5.3; 3943 3.6; 4219 0.0; 4514 -0.5; 4830 0.2; 5168 2.9; 5530 5.7; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.4; 9502 -2.7; 10167 -2.9; 10879 -0.4; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/headphoncecom/onear/Denon%20AH-D1001K%20Silver/Denon%20AH-D1001K%20Silver.png)