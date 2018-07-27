# Grado PS500
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 5.9; 28 5.7; 30 5.2; 32 4.6; 35 3.7; 37 3.1; 40 2.4; 42 1.9; 45 1.1; 49 0.3; 52 -0.3; 56 -1.0; 59 -1.5; 64 -2.1; 68 -2.6; 73 -2.9; 78 -3.1; 83 -3.2; 89 -3.5; 95 -3.9; 102 -4.1; 109 -4.2; 117 -4.3; 125 -4.4; 134 -4.3; 143 -4.2; 153 -4.1; 164 -3.7; 175 -3.4; 188 -3.2; 201 -3.0; 215 -2.7; 230 -2.4; 246 -2.1; 263 -1.8; 282 -1.4; 301 -1.1; 323 -0.8; 345 -0.5; 369 -0.2; 395 0.1; 423 0.2; 452 0.3; 484 0.5; 518 0.5; 554 0.8; 593 1.1; 635 1.1; 679 0.8; 726 0.8; 777 0.9; 832 0.7; 890 0.5; 952 0.3; 1019 0.0; 1090 -0.3; 1167 -0.6; 1248 -1.1; 1336 -1.9; 1429 -2.8; 1529 -3.5; 1636 -3.8; 1751 -2.9; 1873 -2.7; 2004 -4.3; 2145 -5.2; 2295 -1.7; 2455 0.6; 2627 2.3; 2811 4.5; 3008 6.0; 3219 6.0; 3444 6.0; 3685 5.9; 3943 4.1; 4219 4.3; 4514 4.3; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.4; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -2.6; 9502 -3.9; 10167 -1.4; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 5.9; 28 5.7; 30 5.2; 32 4.6; 35 3.7; 37 3.1; 40 2.4; 42 1.9; 45 1.1; 49 0.3; 52 -0.3; 56 -1.0; 59 -1.5; 64 -2.1; 68 -2.6; 73 -2.9; 78 -3.1; 83 -3.2; 89 -3.5; 95 -3.9; 102 -4.1; 109 -4.2; 117 -4.3; 125 -4.4; 134 -4.3; 143 -4.2; 153 -4.1; 164 -3.7; 175 -3.4; 188 -3.2; 201 -3.0; 215 -2.7; 230 -2.4; 246 -2.1; 263 -1.8; 282 -1.4; 301 -1.1; 323 -0.8; 345 -0.5; 369 -0.2; 395 0.1; 423 0.2; 452 0.3; 484 0.5; 518 0.5; 554 0.8; 593 1.1; 635 1.1; 679 0.8; 726 0.8; 777 0.9; 832 0.7; 890 0.5; 952 0.3; 1019 0.0; 1090 -0.3; 1167 -0.6; 1248 -1.1; 1336 -1.9; 1429 -2.8; 1529 -3.5; 1636 -3.8; 1751 -2.9; 1873 -2.7; 2004 -4.3; 2145 -5.2; 2295 -1.7; 2455 0.6; 2627 2.3; 2811 4.5; 3008 6.0; 3219 6.0; 3444 6.0; 3685 5.9; 3943 4.1; 4219 4.3; 4514 4.3; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.4; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -2.6; 9502 -3.9; 10167 -1.4; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/headphoncecom/onear/Grado%20PS500/Grado%20PS500.png)