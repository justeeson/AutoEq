# Focal Listen
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 4.5; 22 4.2; 23 4.1; 25 3.9; 26 3.9; 28 3.8; 30 3.7; 32 3.7; 35 3.6; 37 3.6; 40 3.6; 42 3.6; 45 3.6; 49 3.7; 52 3.8; 56 4.1; 59 4.5; 64 5.4; 68 5.9; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 6.0; 109 6.0; 117 5.4; 125 3.8; 134 2.4; 143 1.5; 153 0.9; 164 0.8; 175 -0.2; 188 -1.3; 201 -1.9; 215 -2.2; 230 -2.4; 246 -2.6; 263 -2.7; 282 -2.7; 301 -2.6; 323 -2.5; 345 -2.3; 369 -2.0; 395 -1.9; 423 -1.7; 452 -1.4; 484 -1.3; 518 -1.4; 554 -1.3; 593 -0.9; 635 -0.4; 679 0.1; 726 0.5; 777 1.0; 832 1.3; 890 1.0; 952 0.3; 1019 -0.0; 1090 0.3; 1167 1.2; 1248 1.9; 1336 2.2; 1429 2.4; 1529 2.1; 1636 1.4; 1751 0.6; 1873 0.2; 2004 0.4; 2145 1.0; 2295 1.8; 2455 3.0; 2627 4.1; 2811 5.2; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 4.9; 4514 1.4; 4830 2.2; 5168 4.5; 5530 4.4; 5917 4.5; 6331 5.2; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -0.8; 8880 -2.7; 9502 -3.0; 10167 -1.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 4.5; 22 4.2; 23 4.1; 25 3.9; 26 3.9; 28 3.8; 30 3.7; 32 3.7; 35 3.6; 37 3.6; 40 3.6; 42 3.6; 45 3.6; 49 3.7; 52 3.8; 56 4.1; 59 4.5; 64 5.4; 68 5.9; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 6.0; 109 6.0; 117 5.4; 125 3.8; 134 2.4; 143 1.5; 153 0.9; 164 0.8; 175 -0.2; 188 -1.3; 201 -1.9; 215 -2.2; 230 -2.4; 246 -2.6; 263 -2.7; 282 -2.7; 301 -2.6; 323 -2.5; 345 -2.3; 369 -2.0; 395 -1.9; 423 -1.7; 452 -1.4; 484 -1.3; 518 -1.4; 554 -1.3; 593 -0.9; 635 -0.4; 679 0.1; 726 0.5; 777 1.0; 832 1.3; 890 1.0; 952 0.3; 1019 -0.0; 1090 0.3; 1167 1.2; 1248 1.9; 1336 2.2; 1429 2.4; 1529 2.1; 1636 1.4; 1751 0.6; 1873 0.2; 2004 0.4; 2145 1.0; 2295 1.8; 2455 3.0; 2627 4.1; 2811 5.2; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 4.9; 4514 1.4; 4830 2.2; 5168 4.5; 5530 4.4; 5917 4.5; 6331 5.2; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -0.8; 8880 -2.7; 9502 -3.0; 10167 -1.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Focal%20Listen/Focal%20Listen.png)