# Grado SR325i
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 5.6; 52 5.0; 56 4.2; 59 3.7; 64 3.2; 68 3.1; 73 3.1; 78 2.9; 83 2.4; 89 1.5; 95 0.6; 102 -0.2; 109 -0.7; 117 -1.2; 125 -1.8; 134 -2.2; 143 -2.4; 153 -2.6; 164 -2.6; 175 -2.4; 188 -2.3; 201 -2.0; 215 -1.9; 230 -1.7; 246 -1.7; 263 -1.6; 282 -1.3; 301 -1.4; 323 -1.3; 345 -1.1; 369 -1.0; 395 -0.8; 423 -0.4; 452 0.0; 484 -0.1; 518 -0.3; 554 -0.2; 593 0.1; 635 0.5; 679 0.9; 726 1.2; 777 1.4; 832 1.1; 890 0.6; 952 0.1; 1019 0.0; 1090 0.4; 1167 0.9; 1248 1.2; 1336 1.1; 1429 0.7; 1529 -0.1; 1636 -1.1; 1751 -2.2; 1873 -4.7; 2004 -7.6; 2145 -7.3; 2295 -5.9; 2455 -4.2; 2627 -2.9; 2811 -1.1; 3008 0.3; 3219 1.3; 3444 1.8; 3685 1.1; 3943 -2.0; 4219 -7.6; 4514 -7.6; 4830 -3.8; 5168 -2.4; 5530 -3.1; 5917 -4.4; 6331 -3.9; 6775 -3.9; 7249 -5.6; 7756 -6.4; 8299 -7.9; 8880 -10.6; 9502 -12.6; 10167 -11.4; 10879 -6.7; 11640 -1.4; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 5.6; 52 5.0; 56 4.2; 59 3.7; 64 3.2; 68 3.1; 73 3.1; 78 2.9; 83 2.4; 89 1.5; 95 0.6; 102 -0.2; 109 -0.7; 117 -1.2; 125 -1.8; 134 -2.2; 143 -2.4; 153 -2.6; 164 -2.6; 175 -2.4; 188 -2.3; 201 -2.0; 215 -1.9; 230 -1.7; 246 -1.7; 263 -1.6; 282 -1.3; 301 -1.4; 323 -1.3; 345 -1.1; 369 -1.0; 395 -0.8; 423 -0.4; 452 0.0; 484 -0.1; 518 -0.3; 554 -0.2; 593 0.1; 635 0.5; 679 0.9; 726 1.2; 777 1.4; 832 1.1; 890 0.6; 952 0.1; 1019 0.0; 1090 0.4; 1167 0.9; 1248 1.2; 1336 1.1; 1429 0.7; 1529 -0.1; 1636 -1.1; 1751 -2.2; 1873 -4.7; 2004 -7.6; 2145 -7.3; 2295 -5.9; 2455 -4.2; 2627 -2.9; 2811 -1.1; 3008 0.3; 3219 1.3; 3444 1.8; 3685 1.1; 3943 -2.0; 4219 -7.6; 4514 -7.6; 4830 -3.8; 5168 -2.4; 5530 -3.1; 5917 -4.4; 6331 -3.9; 6775 -3.9; 7249 -5.6; 7756 -6.4; 8299 -7.9; 8880 -10.6; 9502 -12.6; 10167 -11.4; 10879 -6.7; 11640 -1.4; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Grado%20SR325i/Grado%20SR325i.png)