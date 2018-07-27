# Beyerdynamic T 51 i
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 3.0; 22 2.5; 23 2.2; 25 1.7; 26 1.5; 28 1.1; 30 0.7; 32 0.3; 35 -0.2; 37 -0.5; 40 -0.9; 42 -1.2; 45 -1.5; 49 -2.1; 52 -2.6; 56 -3.1; 59 -3.3; 64 -3.3; 68 -3.0; 73 -2.7; 78 -2.6; 83 -2.8; 89 -3.3; 95 -4.1; 102 -5.0; 109 -5.9; 117 -6.4; 125 -6.7; 134 -7.1; 143 -7.8; 153 -8.0; 164 -7.3; 175 -7.4; 188 -6.9; 201 -6.4; 215 -5.8; 230 -5.1; 246 -4.6; 263 -4.0; 282 -3.3; 301 -3.1; 323 -3.1; 345 -3.3; 369 -3.8; 395 -4.0; 423 -3.8; 452 -3.4; 484 -3.2; 518 -3.1; 554 -2.8; 593 -2.4; 635 -1.8; 679 -1.2; 726 -0.6; 777 0.3; 832 0.6; 890 0.4; 952 -0.0; 1019 0.1; 1090 0.8; 1167 1.8; 1248 2.8; 1336 3.5; 1429 4.1; 1529 4.5; 1636 4.6; 1751 4.7; 1873 5.2; 2004 5.8; 2145 5.4; 2295 3.9; 2455 2.8; 2627 2.7; 2811 3.4; 3008 4.7; 3219 5.7; 3444 6.0; 3685 5.9; 3943 5.5; 4219 4.3; 4514 2.7; 4830 2.3; 5168 3.2; 5530 3.2; 5917 3.2; 6331 3.5; 6775 3.6; 7249 1.3; 7756 -0.1; 8299 -2.5; 8880 -5.1; 9502 -6.7; 10167 -5.1; 10879 -0.6; 11640 0.0; 12455 0.0; 13327 0.0; 14260 -0.0; 15258 -0.5; 16326 -0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 3.0; 22 2.5; 23 2.2; 25 1.7; 26 1.5; 28 1.1; 30 0.7; 32 0.3; 35 -0.2; 37 -0.5; 40 -0.9; 42 -1.2; 45 -1.5; 49 -2.1; 52 -2.6; 56 -3.1; 59 -3.3; 64 -3.3; 68 -3.0; 73 -2.7; 78 -2.6; 83 -2.8; 89 -3.3; 95 -4.1; 102 -5.0; 109 -5.9; 117 -6.4; 125 -6.7; 134 -7.1; 143 -7.8; 153 -8.0; 164 -7.3; 175 -7.4; 188 -6.9; 201 -6.4; 215 -5.8; 230 -5.1; 246 -4.6; 263 -4.0; 282 -3.3; 301 -3.1; 323 -3.1; 345 -3.3; 369 -3.8; 395 -4.0; 423 -3.8; 452 -3.4; 484 -3.2; 518 -3.1; 554 -2.8; 593 -2.4; 635 -1.8; 679 -1.2; 726 -0.6; 777 0.3; 832 0.6; 890 0.4; 952 -0.0; 1019 0.1; 1090 0.8; 1167 1.8; 1248 2.8; 1336 3.5; 1429 4.1; 1529 4.5; 1636 4.6; 1751 4.7; 1873 5.2; 2004 5.8; 2145 5.4; 2295 3.9; 2455 2.8; 2627 2.7; 2811 3.4; 3008 4.7; 3219 5.7; 3444 6.0; 3685 5.9; 3943 5.5; 4219 4.3; 4514 2.7; 4830 2.3; 5168 3.2; 5530 3.2; 5917 3.2; 6331 3.5; 6775 3.6; 7249 1.3; 7756 -0.1; 8299 -2.5; 8880 -5.1; 9502 -6.7; 10167 -5.1; 10879 -0.6; 11640 0.0; 12455 0.0; 13327 0.0; 14260 -0.0; 15258 -0.5; 16326 -0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Beyerdynamic%20T%2051%20i/Beyerdynamic%20T%2051%20i.png)