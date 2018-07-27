# Grado SR225i Comfy Pads
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 5.9; 32 5.6; 35 4.8; 37 4.2; 40 3.4; 42 3.0; 45 2.4; 49 1.6; 52 1.2; 56 0.7; 59 0.5; 64 0.1; 68 -0.3; 73 -0.6; 78 -0.8; 83 -1.1; 89 -1.5; 95 -1.8; 102 -2.1; 109 -2.3; 117 -2.6; 125 -2.9; 134 -3.1; 143 -3.2; 153 -3.2; 164 -3.2; 175 -3.1; 188 -3.0; 201 -2.9; 215 -2.7; 230 -2.6; 246 -2.5; 263 -2.3; 282 -2.2; 301 -2.4; 323 -2.4; 345 -2.3; 369 -2.1; 395 -2.1; 423 -2.0; 452 -2.0; 484 -2.1; 518 -2.0; 554 -1.5; 593 -1.0; 635 -0.6; 679 -0.6; 726 -0.5; 777 -0.2; 832 -0.0; 890 -0.0; 952 -0.0; 1019 -0.0; 1090 -0.1; 1167 -0.5; 1248 -0.8; 1336 -1.1; 1429 -1.7; 1529 -2.4; 1636 -2.9; 1751 -3.6; 1873 -5.3; 2004 -8.4; 2145 -9.8; 2295 -8.5; 2455 -5.9; 2627 -4.1; 2811 -2.3; 3008 -1.0; 3219 0.2; 3444 0.0; 3685 0.2; 3943 2.5; 4219 5.5; 4514 6.0; 4830 4.9; 5168 2.5; 5530 2.4; 5917 3.6; 6331 2.7; 6775 0.4; 7249 -1.5; 7756 -2.1; 8299 -2.5; 8880 -2.8; 9502 -1.5; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 5.9; 32 5.6; 35 4.8; 37 4.2; 40 3.4; 42 3.0; 45 2.4; 49 1.6; 52 1.2; 56 0.7; 59 0.5; 64 0.1; 68 -0.3; 73 -0.6; 78 -0.8; 83 -1.1; 89 -1.5; 95 -1.8; 102 -2.1; 109 -2.3; 117 -2.6; 125 -2.9; 134 -3.1; 143 -3.2; 153 -3.2; 164 -3.2; 175 -3.1; 188 -3.0; 201 -2.9; 215 -2.7; 230 -2.6; 246 -2.5; 263 -2.3; 282 -2.2; 301 -2.4; 323 -2.4; 345 -2.3; 369 -2.1; 395 -2.1; 423 -2.0; 452 -2.0; 484 -2.1; 518 -2.0; 554 -1.5; 593 -1.0; 635 -0.6; 679 -0.6; 726 -0.5; 777 -0.2; 832 -0.0; 890 -0.0; 952 -0.0; 1019 -0.0; 1090 -0.1; 1167 -0.5; 1248 -0.8; 1336 -1.1; 1429 -1.7; 1529 -2.4; 1636 -2.9; 1751 -3.6; 1873 -5.3; 2004 -8.4; 2145 -9.8; 2295 -8.5; 2455 -5.9; 2627 -4.1; 2811 -2.3; 3008 -1.0; 3219 0.2; 3444 0.0; 3685 0.2; 3943 2.5; 4219 5.5; 4514 6.0; 4830 4.9; 5168 2.5; 5530 2.4; 5917 3.6; 6331 2.7; 6775 0.4; 7249 -1.5; 7756 -2.1; 8299 -2.5; 8880 -2.8; 9502 -1.5; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Grado%20SR225i%20Comfy%20Pads/Grado%20SR225i%20Comfy%20Pads.png)