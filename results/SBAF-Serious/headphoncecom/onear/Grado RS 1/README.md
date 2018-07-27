# Grado RS 1
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 5.9; 42 5.5; 45 4.8; 49 3.9; 52 3.3; 56 2.4; 59 1.7; 64 0.8; 68 0.1; 73 -0.6; 78 -1.2; 83 -1.6; 89 -2.1; 95 -2.5; 102 -3.0; 109 -3.3; 117 -3.6; 125 -3.8; 134 -3.9; 143 -3.8; 153 -3.7; 164 -3.4; 175 -3.1; 188 -3.0; 201 -3.0; 215 -2.7; 230 -2.4; 246 -2.1; 263 -1.8; 282 -1.4; 301 -0.6; 323 -0.3; 345 -1.6; 369 -1.6; 395 -1.3; 423 -0.9; 452 -0.8; 484 -0.6; 518 -0.6; 554 -0.3; 593 -0.0; 635 0.1; 679 0.1; 726 0.1; 777 0.3; 832 0.3; 890 0.1; 952 0.1; 1019 -0.0; 1090 -0.2; 1167 -0.4; 1248 -0.6; 1336 -1.1; 1429 -1.8; 1529 -2.5; 1636 -3.9; 1751 -7.0; 1873 -9.4; 2004 -8.4; 2145 -7.7; 2295 -7.0; 2455 -6.1; 2627 -5.1; 2811 -4.0; 3008 -2.3; 3219 -1.1; 3444 0.0; 3685 0.6; 3943 -0.5; 4219 -5.6; 4514 -11.7; 4830 -13.7; 5168 -10.1; 5530 -9.3; 5917 -8.1; 6331 -4.0; 6775 -0.2; 7249 -0.6; 7756 -3.7; 8299 -8.4; 8880 -12.0; 9502 -12.7; 10167 -10.5; 10879 -6.7; 11640 -3.5; 12455 -2.6; 13327 -3.9; 14260 -5.1; 15258 -3.6; 16326 -0.3; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 5.9; 42 5.5; 45 4.8; 49 3.9; 52 3.3; 56 2.4; 59 1.7; 64 0.8; 68 0.1; 73 -0.6; 78 -1.2; 83 -1.6; 89 -2.1; 95 -2.5; 102 -3.0; 109 -3.3; 117 -3.6; 125 -3.8; 134 -3.9; 143 -3.8; 153 -3.7; 164 -3.4; 175 -3.1; 188 -3.0; 201 -3.0; 215 -2.7; 230 -2.4; 246 -2.1; 263 -1.8; 282 -1.4; 301 -0.6; 323 -0.3; 345 -1.6; 369 -1.6; 395 -1.3; 423 -0.9; 452 -0.8; 484 -0.6; 518 -0.6; 554 -0.3; 593 -0.0; 635 0.1; 679 0.1; 726 0.1; 777 0.3; 832 0.3; 890 0.1; 952 0.1; 1019 -0.0; 1090 -0.2; 1167 -0.4; 1248 -0.6; 1336 -1.1; 1429 -1.8; 1529 -2.5; 1636 -3.9; 1751 -7.0; 1873 -9.4; 2004 -8.4; 2145 -7.7; 2295 -7.0; 2455 -6.1; 2627 -5.1; 2811 -4.0; 3008 -2.3; 3219 -1.1; 3444 0.0; 3685 0.6; 3943 -0.5; 4219 -5.6; 4514 -11.7; 4830 -13.7; 5168 -10.1; 5530 -9.3; 5917 -8.1; 6331 -4.0; 6775 -0.2; 7249 -0.6; 7756 -3.7; 8299 -8.4; 8880 -12.0; 9502 -12.7; 10167 -10.5; 10879 -6.7; 11640 -3.5; 12455 -2.6; 13327 -3.9; 14260 -5.1; 15258 -3.6; 16326 -0.3; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/headphoncecom/onear/Grado%20RS%201/Grado%20RS%201.png)