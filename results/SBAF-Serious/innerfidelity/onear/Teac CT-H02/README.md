# Teac CT-H02
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 2.4; 22 2.2; 23 2.1; 25 1.9; 26 1.9; 28 1.8; 30 1.7; 32 1.7; 35 1.6; 37 1.6; 40 1.7; 42 1.7; 45 1.7; 49 1.8; 52 1.8; 56 1.8; 59 1.8; 64 1.9; 68 1.9; 73 1.8; 78 1.7; 83 1.7; 89 1.5; 95 1.4; 102 1.1; 109 0.6; 117 0.2; 125 0.1; 134 0.3; 143 0.5; 153 -0.2; 164 -0.4; 175 0.1; 188 -0.6; 201 -1.3; 215 -1.6; 230 -1.7; 246 -1.6; 263 -1.4; 282 -1.5; 301 -1.6; 323 -1.6; 345 -1.4; 369 -1.4; 395 -1.4; 423 -1.3; 452 -1.3; 484 -1.4; 518 -1.4; 554 -1.3; 593 -1.2; 635 -1.3; 679 -1.2; 726 -0.8; 777 -0.5; 832 -0.7; 890 -0.6; 952 -0.2; 1019 -0.1; 1090 -0.4; 1167 -0.3; 1248 -0.2; 1336 -0.2; 1429 -0.2; 1529 -0.3; 1636 -0.4; 1751 -0.2; 1873 0.4; 2004 1.3; 2145 1.8; 2295 2.9; 2455 4.4; 2627 5.1; 2811 5.8; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 5.0; 4514 5.9; 4830 6.0; 5168 5.9; 5530 5.7; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 -1.7; 8299 -4.9; 8880 -6.5; 9502 -5.9; 10167 -3.1; 10879 -0.1; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 2.4; 22 2.2; 23 2.1; 25 1.9; 26 1.9; 28 1.8; 30 1.7; 32 1.7; 35 1.6; 37 1.6; 40 1.7; 42 1.7; 45 1.7; 49 1.8; 52 1.8; 56 1.8; 59 1.8; 64 1.9; 68 1.9; 73 1.8; 78 1.7; 83 1.7; 89 1.5; 95 1.4; 102 1.1; 109 0.6; 117 0.2; 125 0.1; 134 0.3; 143 0.5; 153 -0.2; 164 -0.4; 175 0.1; 188 -0.6; 201 -1.3; 215 -1.6; 230 -1.7; 246 -1.6; 263 -1.4; 282 -1.5; 301 -1.6; 323 -1.6; 345 -1.4; 369 -1.4; 395 -1.4; 423 -1.3; 452 -1.3; 484 -1.4; 518 -1.4; 554 -1.3; 593 -1.2; 635 -1.3; 679 -1.2; 726 -0.8; 777 -0.5; 832 -0.7; 890 -0.6; 952 -0.2; 1019 -0.1; 1090 -0.4; 1167 -0.3; 1248 -0.2; 1336 -0.2; 1429 -0.2; 1529 -0.3; 1636 -0.4; 1751 -0.2; 1873 0.4; 2004 1.3; 2145 1.8; 2295 2.9; 2455 4.4; 2627 5.1; 2811 5.8; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 5.0; 4514 5.9; 4830 6.0; 5168 5.9; 5530 5.7; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 -1.7; 8299 -4.9; 8880 -6.5; 9502 -5.9; 10167 -3.1; 10879 -0.1; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/Teac%20CT-H02/Teac%20CT-H02.png)