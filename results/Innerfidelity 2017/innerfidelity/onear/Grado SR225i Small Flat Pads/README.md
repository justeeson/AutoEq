# Grado SR225i Small Flat Pads
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 5.8; 42 5.4; 45 4.5; 49 3.5; 52 2.8; 56 1.9; 59 1.4; 64 0.7; 68 0.3; 73 -0.2; 78 -0.5; 83 -0.8; 89 -1.1; 95 -1.4; 102 -1.7; 109 -1.9; 117 -2.3; 125 -2.7; 134 -3.0; 143 -3.1; 153 -3.3; 164 -3.3; 175 -3.3; 188 -3.3; 201 -3.3; 215 -3.1; 230 -3.0; 246 -3.0; 263 -2.9; 282 -2.7; 301 -2.9; 323 -3.0; 345 -2.8; 369 -2.7; 395 -2.7; 423 -2.6; 452 -2.7; 484 -2.7; 518 -2.6; 554 -2.0; 593 -1.4; 635 -1.0; 679 -0.9; 726 -0.7; 777 -0.4; 832 -0.2; 890 -0.2; 952 -0.0; 1019 0.1; 1090 0.1; 1167 -0.0; 1248 -0.2; 1336 -0.4; 1429 -0.7; 1529 -0.8; 1636 -0.8; 1751 -1.0; 1873 -2.2; 2004 -4.9; 2145 -5.7; 2295 -3.9; 2455 -1.2; 2627 0.9; 2811 2.5; 3008 3.6; 3219 4.6; 3444 4.3; 3685 4.6; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 4.3; 6775 1.1; 7249 -1.0; 7756 -1.6; 8299 -1.6; 8880 -1.3; 9502 -0.1; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 5.8; 42 5.4; 45 4.5; 49 3.5; 52 2.8; 56 1.9; 59 1.4; 64 0.7; 68 0.3; 73 -0.2; 78 -0.5; 83 -0.8; 89 -1.1; 95 -1.4; 102 -1.7; 109 -1.9; 117 -2.3; 125 -2.7; 134 -3.0; 143 -3.1; 153 -3.3; 164 -3.3; 175 -3.3; 188 -3.3; 201 -3.3; 215 -3.1; 230 -3.0; 246 -3.0; 263 -2.9; 282 -2.7; 301 -2.9; 323 -3.0; 345 -2.8; 369 -2.7; 395 -2.7; 423 -2.6; 452 -2.7; 484 -2.7; 518 -2.6; 554 -2.0; 593 -1.4; 635 -1.0; 679 -0.9; 726 -0.7; 777 -0.4; 832 -0.2; 890 -0.2; 952 -0.0; 1019 0.1; 1090 0.1; 1167 -0.0; 1248 -0.2; 1336 -0.4; 1429 -0.7; 1529 -0.8; 1636 -0.8; 1751 -1.0; 1873 -2.2; 2004 -4.9; 2145 -5.7; 2295 -3.9; 2455 -1.2; 2627 0.9; 2811 2.5; 3008 3.6; 3219 4.6; 3444 4.3; 3685 4.6; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 4.3; 6775 1.1; 7249 -1.0; 7756 -1.6; 8299 -1.6; 8880 -1.3; 9502 -0.1; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Grado%20SR225i%20Small%20Flat%20Pads/Grado%20SR225i%20Small%20Flat%20Pads.png)