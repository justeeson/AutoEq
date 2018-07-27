# 1More MK801
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 5.9; 28 5.6; 30 5.2; 32 4.8; 35 4.3; 37 4.0; 40 3.5; 42 3.2; 45 2.8; 49 2.3; 52 2.0; 56 1.7; 59 1.6; 64 1.7; 68 2.0; 73 2.3; 78 2.4; 83 2.1; 89 1.4; 95 0.6; 102 -0.2; 109 -0.6; 117 -1.0; 125 -1.7; 134 -2.4; 143 -2.8; 153 -3.2; 164 -3.2; 175 -3.0; 188 -3.4; 201 -3.6; 215 -3.6; 230 -3.6; 246 -3.6; 263 -3.4; 282 -3.1; 301 -2.6; 323 -2.0; 345 -1.6; 369 -1.2; 395 -0.7; 423 -0.1; 452 0.9; 484 1.7; 518 2.0; 554 2.0; 593 2.1; 635 2.3; 679 2.3; 726 2.2; 777 2.6; 832 3.2; 890 2.0; 952 0.6; 1019 -0.1; 1090 0.3; 1167 1.3; 1248 2.4; 1336 3.5; 1429 4.3; 1529 4.9; 1636 5.0; 1751 5.0; 1873 5.0; 2004 5.4; 2145 5.6; 2295 5.6; 2455 5.9; 2627 6.0; 2811 5.7; 3008 5.7; 3219 5.5; 3444 5.6; 3685 5.6; 3943 4.7; 4219 2.3; 4514 2.9; 4830 3.4; 5168 4.3; 5530 4.2; 5917 4.1; 6331 5.3; 6775 3.9; 7249 1.3; 7756 0.2; 8299 -1.0; 8880 -1.2; 9502 -0.2; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 -0.7; 16326 -0.5; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 5.9; 28 5.6; 30 5.2; 32 4.8; 35 4.3; 37 4.0; 40 3.5; 42 3.2; 45 2.8; 49 2.3; 52 2.0; 56 1.7; 59 1.6; 64 1.7; 68 2.0; 73 2.3; 78 2.4; 83 2.1; 89 1.4; 95 0.6; 102 -0.2; 109 -0.6; 117 -1.0; 125 -1.7; 134 -2.4; 143 -2.8; 153 -3.2; 164 -3.2; 175 -3.0; 188 -3.4; 201 -3.6; 215 -3.6; 230 -3.6; 246 -3.6; 263 -3.4; 282 -3.1; 301 -2.6; 323 -2.0; 345 -1.6; 369 -1.2; 395 -0.7; 423 -0.1; 452 0.9; 484 1.7; 518 2.0; 554 2.0; 593 2.1; 635 2.3; 679 2.3; 726 2.2; 777 2.6; 832 3.2; 890 2.0; 952 0.6; 1019 -0.1; 1090 0.3; 1167 1.3; 1248 2.4; 1336 3.5; 1429 4.3; 1529 4.9; 1636 5.0; 1751 5.0; 1873 5.0; 2004 5.4; 2145 5.6; 2295 5.6; 2455 5.9; 2627 6.0; 2811 5.7; 3008 5.7; 3219 5.5; 3444 5.6; 3685 5.6; 3943 4.7; 4219 2.3; 4514 2.9; 4830 3.4; 5168 4.3; 5530 4.2; 5917 4.1; 6331 5.3; 6775 3.9; 7249 1.3; 7756 0.2; 8299 -1.0; 8880 -1.2; 9502 -0.2; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 -0.7; 16326 -0.5; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/1More%20MK801/1More%20MK801.png)