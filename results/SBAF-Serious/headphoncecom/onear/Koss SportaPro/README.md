# Koss SportaPro
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 5.6; 37 5.0; 40 4.0; 42 3.5; 45 2.6; 49 1.7; 52 1.0; 56 0.3; 59 -0.1; 64 -0.6; 68 -1.0; 73 -1.6; 78 -2.0; 83 -2.1; 89 -2.4; 95 -2.9; 102 -3.2; 109 -3.5; 117 -3.8; 125 -4.2; 134 -4.3; 143 -4.4; 153 -4.1; 164 -3.7; 175 -3.5; 188 -3.4; 201 -3.5; 215 -3.4; 230 -3.2; 246 -3.0; 263 -2.8; 282 -2.5; 301 -2.3; 323 -2.0; 345 -1.7; 369 -1.4; 395 -1.3; 423 -0.9; 452 -0.8; 484 -0.7; 518 -0.6; 554 -0.3; 593 -0.0; 635 0.1; 679 0.1; 726 0.2; 777 0.4; 832 0.3; 890 0.2; 952 0.1; 1019 -0.0; 1090 -0.1; 1167 -0.2; 1248 -0.5; 1336 -1.0; 1429 -1.6; 1529 -2.2; 1636 -2.8; 1751 -3.3; 1873 -3.7; 2004 -4.3; 2145 -4.7; 2295 -4.7; 2455 -4.0; 2627 -2.9; 2811 -1.9; 3008 -0.8; 3219 -1.0; 3444 -1.8; 3685 -3.7; 3943 -4.4; 4219 -1.9; 4514 -2.0; 4830 -4.6; 5168 -1.5; 5530 -0.4; 5917 2.8; 6331 5.4; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -2.0; 8880 -7.4; 9502 -8.4; 10167 -3.5; 10879 -0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 -1.9
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 5.6; 37 5.0; 40 4.0; 42 3.5; 45 2.6; 49 1.7; 52 1.0; 56 0.3; 59 -0.1; 64 -0.6; 68 -1.0; 73 -1.6; 78 -2.0; 83 -2.1; 89 -2.4; 95 -2.9; 102 -3.2; 109 -3.5; 117 -3.8; 125 -4.2; 134 -4.3; 143 -4.4; 153 -4.1; 164 -3.7; 175 -3.5; 188 -3.4; 201 -3.5; 215 -3.4; 230 -3.2; 246 -3.0; 263 -2.8; 282 -2.5; 301 -2.3; 323 -2.0; 345 -1.7; 369 -1.4; 395 -1.3; 423 -0.9; 452 -0.8; 484 -0.7; 518 -0.6; 554 -0.3; 593 -0.0; 635 0.1; 679 0.1; 726 0.2; 777 0.4; 832 0.3; 890 0.2; 952 0.1; 1019 -0.0; 1090 -0.1; 1167 -0.2; 1248 -0.5; 1336 -1.0; 1429 -1.6; 1529 -2.2; 1636 -2.8; 1751 -3.3; 1873 -3.7; 2004 -4.3; 2145 -4.7; 2295 -4.7; 2455 -4.0; 2627 -2.9; 2811 -1.9; 3008 -0.8; 3219 -1.0; 3444 -1.8; 3685 -3.7; 3943 -4.4; 4219 -1.9; 4514 -2.0; 4830 -4.6; 5168 -1.5; 5530 -0.4; 5917 2.8; 6331 5.4; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -2.0; 8880 -7.4; 9502 -8.4; 10167 -3.5; 10879 -0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 -1.9
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/headphoncecom/onear/Koss%20SportaPro/Koss%20SportaPro.png)