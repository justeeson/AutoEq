# Grado RS1e Bowl Pads
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 5.6; 68 4.7; 73 3.5; 78 2.6; 83 1.6; 89 0.6; 95 -0.4; 102 -1.3; 109 -1.7; 117 -2.1; 125 -2.6; 134 -2.9; 143 -2.9; 153 -2.9; 164 -2.7; 175 -2.4; 188 -2.1; 201 -1.8; 215 -1.3; 230 -0.9; 246 -0.6; 263 -0.2; 282 -0.8; 301 -1.1; 323 -0.6; 345 -0.4; 369 -0.1; 395 0.0; 423 0.3; 452 0.5; 484 0.5; 518 0.5; 554 0.7; 593 0.9; 635 0.9; 679 0.8; 726 0.7; 777 0.8; 832 0.6; 890 0.4; 952 0.2; 1019 -0.1; 1090 -0.3; 1167 -0.7; 1248 -1.0; 1336 -1.7; 1429 -2.3; 1529 -2.8; 1636 -3.8; 1751 -8.1; 1873 -11.0; 2004 -11.3; 2145 -9.8; 2295 -7.3; 2455 -4.1; 2627 -1.6; 2811 0.4; 3008 2.2; 3219 3.0; 3444 3.5; 3685 4.2; 3943 5.7; 4219 6.0; 4514 5.9; 4830 3.0; 5168 5.3; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 5.6; 68 4.7; 73 3.5; 78 2.6; 83 1.6; 89 0.6; 95 -0.4; 102 -1.3; 109 -1.7; 117 -2.1; 125 -2.6; 134 -2.9; 143 -2.9; 153 -2.9; 164 -2.7; 175 -2.4; 188 -2.1; 201 -1.8; 215 -1.3; 230 -0.9; 246 -0.6; 263 -0.2; 282 -0.8; 301 -1.1; 323 -0.6; 345 -0.4; 369 -0.1; 395 0.0; 423 0.3; 452 0.5; 484 0.5; 518 0.5; 554 0.7; 593 0.9; 635 0.9; 679 0.8; 726 0.7; 777 0.8; 832 0.6; 890 0.4; 952 0.2; 1019 -0.1; 1090 -0.3; 1167 -0.7; 1248 -1.0; 1336 -1.7; 1429 -2.3; 1529 -2.8; 1636 -3.8; 1751 -8.1; 1873 -11.0; 2004 -11.3; 2145 -9.8; 2295 -7.3; 2455 -4.1; 2627 -1.6; 2811 0.4; 3008 2.2; 3219 3.0; 3444 3.5; 3685 4.2; 3943 5.7; 4219 6.0; 4514 5.9; 4830 3.0; 5168 5.3; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/Grado%20RS1e%20Bowl%20Pads/Grado%20RS1e%20Bowl%20Pads.png)