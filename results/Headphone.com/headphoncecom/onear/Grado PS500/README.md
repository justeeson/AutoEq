# Grado PS500
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 5.9; 26 5.8; 28 5.3; 30 4.7; 32 4.0; 35 3.1; 37 2.5; 40 1.8; 42 1.3; 45 0.5; 49 -0.3; 52 -0.9; 56 -1.6; 59 -2.1; 64 -2.7; 68 -3.1; 73 -3.6; 78 -3.8; 83 -3.9; 89 -4.3; 95 -4.7; 102 -5.1; 109 -5.3; 117 -5.6; 125 -5.7; 134 -5.6; 143 -5.5; 153 -5.4; 164 -5.1; 175 -4.8; 188 -4.6; 201 -4.3; 215 -4.1; 230 -3.8; 246 -3.5; 263 -3.2; 282 -2.8; 301 -2.5; 323 -2.2; 345 -1.9; 369 -1.6; 395 -1.2; 423 -1.0; 452 -0.7; 484 -0.3; 518 0.0; 554 0.3; 593 0.6; 635 0.8; 679 0.8; 726 0.8; 777 0.8; 832 0.6; 890 0.5; 952 0.3; 1019 0.0; 1090 -0.2; 1167 -0.3; 1248 -0.5; 1336 -0.5; 1429 -0.6; 1529 -0.8; 1636 -0.8; 1751 0.1; 1873 0.2; 2004 -1.4; 2145 -2.2; 2295 1.4; 2455 3.5; 2627 5.3; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.8; 9502 -1.3; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 5.9; 26 5.8; 28 5.3; 30 4.7; 32 4.0; 35 3.1; 37 2.5; 40 1.8; 42 1.3; 45 0.5; 49 -0.3; 52 -0.9; 56 -1.6; 59 -2.1; 64 -2.7; 68 -3.1; 73 -3.6; 78 -3.8; 83 -3.9; 89 -4.3; 95 -4.7; 102 -5.1; 109 -5.3; 117 -5.6; 125 -5.7; 134 -5.6; 143 -5.5; 153 -5.4; 164 -5.1; 175 -4.8; 188 -4.6; 201 -4.3; 215 -4.1; 230 -3.8; 246 -3.5; 263 -3.2; 282 -2.8; 301 -2.5; 323 -2.2; 345 -1.9; 369 -1.6; 395 -1.2; 423 -1.0; 452 -0.7; 484 -0.3; 518 0.0; 554 0.3; 593 0.6; 635 0.8; 679 0.8; 726 0.8; 777 0.8; 832 0.6; 890 0.5; 952 0.3; 1019 0.0; 1090 -0.2; 1167 -0.3; 1248 -0.5; 1336 -0.5; 1429 -0.6; 1529 -0.8; 1636 -0.8; 1751 0.1; 1873 0.2; 2004 -1.4; 2145 -2.2; 2295 1.4; 2455 3.5; 2627 5.3; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.8; 9502 -1.3; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/headphoncecom/onear/Grado%20PS500/Grado%20PS500.png)