# Oppo PM1 2014 PM2 Pad
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 2.4; 22 2.2; 23 2.0; 25 1.9; 26 1.8; 28 1.7; 30 1.6; 32 1.5; 35 1.4; 37 1.4; 40 1.3; 42 1.3; 45 1.4; 49 1.5; 52 1.7; 56 1.9; 59 2.0; 64 1.7; 68 1.4; 73 0.9; 78 0.6; 83 0.3; 89 -0.1; 95 -0.4; 102 -0.9; 109 -1.2; 117 -1.5; 125 -1.9; 134 -2.3; 143 -2.5; 153 -2.6; 164 -2.5; 175 -2.7; 188 -2.8; 201 -2.7; 215 -2.7; 230 -2.4; 246 -2.7; 263 -3.1; 282 -3.2; 301 -3.4; 323 -3.3; 345 -2.8; 369 -1.1; 395 -0.0; 423 -0.0; 452 -0.7; 484 -1.2; 518 -1.6; 554 -1.6; 593 -1.5; 635 -1.7; 679 -2.0; 726 -2.1; 777 -2.1; 832 -2.4; 890 -1.8; 952 -0.4; 1019 -0.0; 1090 -0.5; 1167 -0.7; 1248 -1.0; 1336 -1.3; 1429 -1.7; 1529 -2.1; 1636 -2.4; 1751 -2.3; 1873 -2.2; 2004 -1.9; 2145 -1.7; 2295 -1.3; 2455 -0.6; 2627 0.2; 2811 1.0; 3008 1.8; 3219 2.1; 3444 2.1; 3685 2.0; 3943 2.4; 4219 2.5; 4514 2.9; 4830 3.9; 5168 5.6; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -0.1; 8880 -1.9; 9502 -1.5; 10167 -0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 2.4; 22 2.2; 23 2.0; 25 1.9; 26 1.8; 28 1.7; 30 1.6; 32 1.5; 35 1.4; 37 1.4; 40 1.3; 42 1.3; 45 1.4; 49 1.5; 52 1.7; 56 1.9; 59 2.0; 64 1.7; 68 1.4; 73 0.9; 78 0.6; 83 0.3; 89 -0.1; 95 -0.4; 102 -0.9; 109 -1.2; 117 -1.5; 125 -1.9; 134 -2.3; 143 -2.5; 153 -2.6; 164 -2.5; 175 -2.7; 188 -2.8; 201 -2.7; 215 -2.7; 230 -2.4; 246 -2.7; 263 -3.1; 282 -3.2; 301 -3.4; 323 -3.3; 345 -2.8; 369 -1.1; 395 -0.0; 423 -0.0; 452 -0.7; 484 -1.2; 518 -1.6; 554 -1.6; 593 -1.5; 635 -1.7; 679 -2.0; 726 -2.1; 777 -2.1; 832 -2.4; 890 -1.8; 952 -0.4; 1019 -0.0; 1090 -0.5; 1167 -0.7; 1248 -1.0; 1336 -1.3; 1429 -1.7; 1529 -2.1; 1636 -2.4; 1751 -2.3; 1873 -2.2; 2004 -1.9; 2145 -1.7; 2295 -1.3; 2455 -0.6; 2627 0.2; 2811 1.0; 3008 1.8; 3219 2.1; 3444 2.1; 3685 2.0; 3943 2.4; 4219 2.5; 4514 2.9; 4830 3.9; 5168 5.6; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -0.1; 8880 -1.9; 9502 -1.5; 10167 -0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/Oppo%20PM1%202014%20PM2%20Pad/Oppo%20PM1%202014%20PM2%20Pad.png)