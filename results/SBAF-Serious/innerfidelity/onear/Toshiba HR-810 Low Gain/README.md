# Toshiba HR-810 Low Gain
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 5.3; 109 4.6; 117 3.7; 125 2.7; 134 1.8; 143 1.2; 153 0.7; 164 0.3; 175 -0.1; 188 -0.4; 201 -0.5; 215 -0.5; 230 -0.5; 246 -0.5; 263 -0.5; 282 -0.4; 301 -0.4; 323 -0.3; 345 -0.1; 369 0.0; 395 0.1; 423 0.3; 452 0.5; 484 0.5; 518 0.5; 554 0.7; 593 0.9; 635 0.9; 679 0.8; 726 0.8; 777 0.9; 832 0.8; 890 0.3; 952 0.1; 1019 0.0; 1090 0.7; 1167 0.8; 1248 -0.8; 1336 -2.3; 1429 -2.9; 1529 -3.3; 1636 -3.7; 1751 -3.7; 1873 -3.5; 2004 -3.4; 2145 -4.0; 2295 -3.9; 2455 -2.9; 2627 -2.7; 2811 -2.2; 3008 -0.8; 3219 -0.0; 3444 0.7; 3685 1.5; 3943 2.2; 4219 2.5; 4514 3.4; 4830 5.1; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 5.3; 109 4.6; 117 3.7; 125 2.7; 134 1.8; 143 1.2; 153 0.7; 164 0.3; 175 -0.1; 188 -0.4; 201 -0.5; 215 -0.5; 230 -0.5; 246 -0.5; 263 -0.5; 282 -0.4; 301 -0.4; 323 -0.3; 345 -0.1; 369 0.0; 395 0.1; 423 0.3; 452 0.5; 484 0.5; 518 0.5; 554 0.7; 593 0.9; 635 0.9; 679 0.8; 726 0.8; 777 0.9; 832 0.8; 890 0.3; 952 0.1; 1019 0.0; 1090 0.7; 1167 0.8; 1248 -0.8; 1336 -2.3; 1429 -2.9; 1529 -3.3; 1636 -3.7; 1751 -3.7; 1873 -3.5; 2004 -3.4; 2145 -4.0; 2295 -3.9; 2455 -2.9; 2627 -2.7; 2811 -2.2; 3008 -0.8; 3219 -0.0; 3444 0.7; 3685 1.5; 3943 2.2; 4219 2.5; 4514 3.4; 4830 5.1; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/Toshiba%20HR-810%20Low%20Gain/Toshiba%20HR-810%20Low%20Gain.png)