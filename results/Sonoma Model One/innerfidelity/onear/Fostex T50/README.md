# Fostex T50
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 6.0; 109 6.0; 117 6.0; 125 6.0; 134 4.7; 143 3.7; 153 3.2; 164 3.0; 175 3.1; 188 3.0; 201 2.8; 215 2.7; 230 2.4; 246 2.3; 263 2.1; 282 2.0; 301 1.8; 323 1.7; 345 1.6; 369 1.0; 395 0.0; 423 0.1; 452 0.5; 484 0.9; 518 0.8; 554 0.6; 593 0.6; 635 0.9; 679 1.0; 726 1.2; 777 1.4; 832 1.2; 890 0.8; 952 0.4; 1019 0.0; 1090 0.5; 1167 1.6; 1248 2.4; 1336 2.8; 1429 3.0; 1529 2.6; 1636 1.9; 1751 1.0; 1873 0.5; 2004 0.0; 2145 0.1; 2295 0.8; 2455 1.4; 2627 2.3; 2811 2.7; 3008 3.4; 3219 4.8; 3444 5.0; 3685 4.1; 3943 3.0; 4219 3.8; 4514 4.8; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 6.0; 109 6.0; 117 6.0; 125 6.0; 134 4.7; 143 3.7; 153 3.2; 164 3.0; 175 3.1; 188 3.0; 201 2.8; 215 2.7; 230 2.4; 246 2.3; 263 2.1; 282 2.0; 301 1.8; 323 1.7; 345 1.6; 369 1.0; 395 0.0; 423 0.1; 452 0.5; 484 0.9; 518 0.8; 554 0.6; 593 0.6; 635 0.9; 679 1.0; 726 1.2; 777 1.4; 832 1.2; 890 0.8; 952 0.4; 1019 0.0; 1090 0.5; 1167 1.6; 1248 2.4; 1336 2.8; 1429 3.0; 1529 2.6; 1636 1.9; 1751 1.0; 1873 0.5; 2004 0.0; 2145 0.1; 2295 0.8; 2455 1.4; 2627 2.3; 2811 2.7; 3008 3.4; 3219 4.8; 3444 5.0; 3685 4.1; 3943 3.0; 4219 3.8; 4514 4.8; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Fostex%20T50/Fostex%20T50.png)