# Bose Quiet Comfort 15
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -2.2; 22 -2.6; 23 -2.8; 25 -3.1; 26 -3.3; 28 -3.5; 30 -3.7; 32 -3.8; 35 -4.0; 37 -4.0; 40 -4.0; 42 -4.1; 45 -4.1; 49 -4.0; 52 -3.9; 56 -3.8; 59 -3.7; 64 -3.6; 68 -3.5; 73 -3.5; 78 -3.6; 83 -3.8; 89 -4.1; 95 -4.3; 102 -4.5; 109 -4.7; 117 -4.8; 125 -5.1; 134 -5.2; 143 -5.3; 153 -5.2; 164 -4.9; 175 -4.7; 188 -4.7; 201 -4.6; 215 -4.5; 230 -4.3; 246 -4.2; 263 -4.2; 282 -3.9; 301 -3.7; 323 -3.4; 345 -3.2; 369 -2.9; 395 -2.6; 423 -2.4; 452 -2.2; 484 -2.2; 518 -1.9; 554 -1.3; 593 -0.6; 635 -0.1; 679 -0.1; 726 0.2; 777 0.6; 832 0.5; 890 0.4; 952 0.2; 1019 -0.1; 1090 -0.5; 1167 -1.0; 1248 -1.4; 1336 -1.6; 1429 -1.2; 1529 -1.5; 1636 -2.0; 1751 -2.6; 1873 -2.9; 2004 -2.8; 2145 -2.3; 2295 -2.1; 2455 -1.8; 2627 -0.8; 2811 0.7; 3008 1.8; 3219 3.1; 3444 5.8; 3685 6.0; 3943 1.7; 4219 -1.7; 4514 -0.6; 4830 1.2; 5168 3.2; 5530 1.5; 5917 -3.9; 6331 -4.1; 6775 -2.2; 7249 0.6; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -2.2; 22 -2.6; 23 -2.8; 25 -3.1; 26 -3.3; 28 -3.5; 30 -3.7; 32 -3.8; 35 -4.0; 37 -4.0; 40 -4.0; 42 -4.1; 45 -4.1; 49 -4.0; 52 -3.9; 56 -3.8; 59 -3.7; 64 -3.6; 68 -3.5; 73 -3.5; 78 -3.6; 83 -3.8; 89 -4.1; 95 -4.3; 102 -4.5; 109 -4.7; 117 -4.8; 125 -5.1; 134 -5.2; 143 -5.3; 153 -5.2; 164 -4.9; 175 -4.7; 188 -4.7; 201 -4.6; 215 -4.5; 230 -4.3; 246 -4.2; 263 -4.2; 282 -3.9; 301 -3.7; 323 -3.4; 345 -3.2; 369 -2.9; 395 -2.6; 423 -2.4; 452 -2.2; 484 -2.2; 518 -1.9; 554 -1.3; 593 -0.6; 635 -0.1; 679 -0.1; 726 0.2; 777 0.6; 832 0.5; 890 0.4; 952 0.2; 1019 -0.1; 1090 -0.5; 1167 -1.0; 1248 -1.4; 1336 -1.6; 1429 -1.2; 1529 -1.5; 1636 -2.0; 1751 -2.6; 1873 -2.9; 2004 -2.8; 2145 -2.3; 2295 -2.1; 2455 -1.8; 2627 -0.8; 2811 0.7; 3008 1.8; 3219 3.1; 3444 5.8; 3685 6.0; 3943 1.7; 4219 -1.7; 4514 -0.6; 4830 1.2; 5168 3.2; 5530 1.5; 5917 -3.9; 6331 -4.1; 6775 -2.2; 7249 0.6; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Bose%20Quiet%20Comfort%2015/Bose%20Quiet%20Comfort%2015.png)