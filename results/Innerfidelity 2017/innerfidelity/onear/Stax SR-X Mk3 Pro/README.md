# Stax SR-X Mk3 Pro
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 5.9; 23 5.8; 25 5.5; 26 5.3; 28 5.0; 30 4.6; 32 4.3; 35 3.8; 37 3.6; 40 3.4; 42 3.3; 45 3.2; 49 3.1; 52 3.0; 56 2.9; 59 2.9; 64 3.0; 68 2.9; 73 2.8; 78 2.7; 83 2.5; 89 2.3; 95 2.0; 102 1.6; 109 1.3; 117 1.0; 125 0.7; 134 0.3; 143 0.0; 153 -0.1; 164 -0.2; 175 -0.3; 188 -0.4; 201 -0.5; 215 -0.5; 230 -0.5; 246 -0.5; 263 -0.6; 282 -0.6; 301 -0.7; 323 -0.7; 345 -0.7; 369 -0.7; 395 -0.7; 423 -0.8; 452 -1.0; 484 -1.2; 518 -1.7; 554 -0.7; 593 -0.1; 635 -0.1; 679 -0.2; 726 -0.2; 777 0.1; 832 0.1; 890 0.1; 952 -0.1; 1019 0.0; 1090 0.0; 1167 0.0; 1248 -0.1; 1336 0.3; 1429 0.9; 1529 1.2; 1636 1.5; 1751 1.9; 1873 2.2; 2004 2.0; 2145 1.7; 2295 1.2; 2455 0.5; 2627 -0.2; 2811 -0.9; 3008 -1.5; 3219 -1.7; 3444 -1.8; 3685 -2.0; 3943 -1.3; 4219 -0.2; 4514 1.7; 4830 3.1; 5168 3.1; 5530 1.9; 5917 0.2; 6331 -1.4; 6775 -2.5; 7249 -3.2; 7756 -3.1; 8299 -3.0; 8880 -2.5; 9502 -0.6; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 -1.3; 20000 -4.4
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 5.9; 23 5.8; 25 5.5; 26 5.3; 28 5.0; 30 4.6; 32 4.3; 35 3.8; 37 3.6; 40 3.4; 42 3.3; 45 3.2; 49 3.1; 52 3.0; 56 2.9; 59 2.9; 64 3.0; 68 2.9; 73 2.8; 78 2.7; 83 2.5; 89 2.3; 95 2.0; 102 1.6; 109 1.3; 117 1.0; 125 0.7; 134 0.3; 143 0.0; 153 -0.1; 164 -0.2; 175 -0.3; 188 -0.4; 201 -0.5; 215 -0.5; 230 -0.5; 246 -0.5; 263 -0.6; 282 -0.6; 301 -0.7; 323 -0.7; 345 -0.7; 369 -0.7; 395 -0.7; 423 -0.8; 452 -1.0; 484 -1.2; 518 -1.7; 554 -0.7; 593 -0.1; 635 -0.1; 679 -0.2; 726 -0.2; 777 0.1; 832 0.1; 890 0.1; 952 -0.1; 1019 0.0; 1090 0.0; 1167 0.0; 1248 -0.1; 1336 0.3; 1429 0.9; 1529 1.2; 1636 1.5; 1751 1.9; 1873 2.2; 2004 2.0; 2145 1.7; 2295 1.2; 2455 0.5; 2627 -0.2; 2811 -0.9; 3008 -1.5; 3219 -1.7; 3444 -1.8; 3685 -2.0; 3943 -1.3; 4219 -0.2; 4514 1.7; 4830 3.1; 5168 3.1; 5530 1.9; 5917 0.2; 6331 -1.4; 6775 -2.5; 7249 -3.2; 7756 -3.1; 8299 -3.0; 8880 -2.5; 9502 -0.6; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 -1.3; 20000 -4.4
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Stax%20SR-X%20Mk3%20Pro/Stax%20SR-X%20Mk3%20Pro.png)