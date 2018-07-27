# Bose Quiet Comfort 20
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-67**.
```
GraphicEQ: 10 -84; 20 6.7; 22 5.0; 23 4.3; 25 3.3; 26 2.9; 28 2.3; 30 2.0; 32 1.8; 35 1.7; 37 1.8; 40 1.8; 42 1.8; 45 1.9; 49 1.8; 52 1.8; 56 1.8; 59 1.8; 64 2.0; 68 2.3; 73 2.5; 78 2.5; 83 2.1; 89 1.2; 95 0.3; 102 -0.7; 109 -1.1; 117 -1.6; 125 -2.2; 134 -2.6; 143 -2.9; 153 -3.1; 164 -3.3; 175 -3.2; 188 -3.3; 201 -3.4; 215 -3.3; 230 -3.3; 246 -3.2; 263 -3.2; 282 -2.9; 301 -2.9; 323 -2.8; 345 -2.7; 369 -2.7; 395 -2.8; 423 -2.7; 452 -2.5; 484 -2.2; 518 -2.1; 554 -1.8; 593 -1.4; 635 -1.0; 679 -0.7; 726 -0.2; 777 0.4; 832 0.6; 890 0.6; 952 0.3; 1019 -0.1; 1090 -0.2; 1167 0.0; 1248 -0.1; 1336 -0.6; 1429 -1.3; 1529 -2.4; 1636 -3.4; 1751 -3.7; 1873 -3.4; 2004 -2.7; 2145 -1.9; 2295 -1.4; 2455 -0.6; 2627 -0.0; 2811 0.9; 3008 2.4; 3219 3.3; 3444 3.3; 3685 1.8; 3943 -0.5; 4219 -2.6; 4514 -1.5; 4830 1.9; 5168 4.8; 5530 5.3; 5917 4.9; 6331 4.2; 6775 1.0; 7249 -3.4; 7756 -3.4; 8299 -1.7; 8880 -0.9; 9502 -2.5; 10167 -3.1; 10879 -0.3; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.7; 22 5.0; 23 4.3; 25 3.3; 26 2.9; 28 2.3; 30 2.0; 32 1.8; 35 1.7; 37 1.8; 40 1.8; 42 1.8; 45 1.9; 49 1.8; 52 1.8; 56 1.8; 59 1.8; 64 2.0; 68 2.3; 73 2.5; 78 2.5; 83 2.1; 89 1.2; 95 0.3; 102 -0.7; 109 -1.1; 117 -1.6; 125 -2.2; 134 -2.6; 143 -2.9; 153 -3.1; 164 -3.3; 175 -3.2; 188 -3.3; 201 -3.4; 215 -3.3; 230 -3.3; 246 -3.2; 263 -3.2; 282 -2.9; 301 -2.9; 323 -2.8; 345 -2.7; 369 -2.7; 395 -2.8; 423 -2.7; 452 -2.5; 484 -2.2; 518 -2.1; 554 -1.8; 593 -1.4; 635 -1.0; 679 -0.7; 726 -0.2; 777 0.4; 832 0.6; 890 0.6; 952 0.3; 1019 -0.1; 1090 -0.2; 1167 0.0; 1248 -0.1; 1336 -0.6; 1429 -1.3; 1529 -2.4; 1636 -3.4; 1751 -3.7; 1873 -3.4; 2004 -2.7; 2145 -1.9; 2295 -1.4; 2455 -0.6; 2627 -0.0; 2811 0.9; 3008 2.4; 3219 3.3; 3444 3.3; 3685 1.8; 3943 -0.5; 4219 -2.6; 4514 -1.5; 4830 1.9; 5168 4.8; 5530 5.3; 5917 4.9; 6331 4.2; 6775 1.0; 7249 -3.4; 7756 -3.4; 8299 -1.7; 8880 -0.9; 9502 -2.5; 10167 -3.1; 10879 -0.3; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.7dB*l, R=-6.7dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Bose%20Quiet%20Comfort%2020/Bose%20Quiet%20Comfort%2020.png)