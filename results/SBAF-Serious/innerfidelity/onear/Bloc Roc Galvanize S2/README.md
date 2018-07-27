# Bloc Roc Galvanize S2
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-37**.
```
GraphicEQ: 10 -84; 20 2.7; 22 1.7; 23 1.3; 25 0.4; 26 -0.0; 28 -0.9; 30 -1.6; 32 -2.3; 35 -3.2; 37 -3.8; 40 -4.5; 42 -5.0; 45 -5.5; 49 -6.1; 52 -6.4; 56 -6.8; 59 -6.9; 64 -7.0; 68 -7.0; 73 -7.0; 78 -6.9; 83 -6.6; 89 -6.3; 95 -6.3; 102 -6.6; 109 -6.9; 117 -7.1; 125 -7.3; 134 -7.4; 143 -7.3; 153 -7.3; 164 -6.8; 175 -6.8; 188 -6.6; 201 -6.4; 215 -6.0; 230 -5.5; 246 -5.0; 263 -4.6; 282 -4.0; 301 -4.4; 323 -4.4; 345 -4.0; 369 -3.6; 395 -3.3; 423 -2.8; 452 -2.7; 484 -2.5; 518 -2.0; 554 -1.2; 593 -0.3; 635 0.5; 679 1.0; 726 1.3; 777 1.2; 832 1.0; 890 0.7; 952 0.3; 1019 -0.1; 1090 -0.7; 1167 -1.1; 1248 -1.4; 1336 -2.4; 1429 -3.1; 1529 -4.2; 1636 -4.8; 1751 -5.0; 1873 -4.5; 2004 -4.3; 2145 -3.6; 2295 -2.8; 2455 -1.7; 2627 -0.5; 2811 0.9; 3008 1.3; 3219 0.7; 3444 2.3; 3685 3.5; 3943 3.5; 4219 3.2; 4514 0.6; 4830 -2.0; 5168 -1.8; 5530 -1.8; 5917 -0.3; 6331 -0.4; 6775 -0.9; 7249 0.9; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 2.7; 22 1.7; 23 1.3; 25 0.4; 26 -0.0; 28 -0.9; 30 -1.6; 32 -2.3; 35 -3.2; 37 -3.8; 40 -4.5; 42 -5.0; 45 -5.5; 49 -6.1; 52 -6.4; 56 -6.8; 59 -6.9; 64 -7.0; 68 -7.0; 73 -7.0; 78 -6.9; 83 -6.6; 89 -6.3; 95 -6.3; 102 -6.6; 109 -6.9; 117 -7.1; 125 -7.3; 134 -7.4; 143 -7.3; 153 -7.3; 164 -6.8; 175 -6.8; 188 -6.6; 201 -6.4; 215 -6.0; 230 -5.5; 246 -5.0; 263 -4.6; 282 -4.0; 301 -4.4; 323 -4.4; 345 -4.0; 369 -3.6; 395 -3.3; 423 -2.8; 452 -2.7; 484 -2.5; 518 -2.0; 554 -1.2; 593 -0.3; 635 0.5; 679 1.0; 726 1.3; 777 1.2; 832 1.0; 890 0.7; 952 0.3; 1019 -0.1; 1090 -0.7; 1167 -1.1; 1248 -1.4; 1336 -2.4; 1429 -3.1; 1529 -4.2; 1636 -4.8; 1751 -5.0; 1873 -4.5; 2004 -4.3; 2145 -3.6; 2295 -2.8; 2455 -1.7; 2627 -0.5; 2811 0.9; 3008 1.3; 3219 0.7; 3444 2.3; 3685 3.5; 3943 3.5; 4219 3.2; 4514 0.6; 4830 -2.0; 5168 -1.8; 5530 -1.8; 5917 -0.3; 6331 -0.4; 6775 -0.9; 7249 0.9; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-3.7dB*l, R=-3.7dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/Bloc%20Roc%20Galvanize%20S2/Bloc%20Roc%20Galvanize%20S2.png)