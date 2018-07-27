# SMS DJ Pro
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -4.2; 22 -4.4; 23 -4.5; 25 -4.6; 26 -4.7; 28 -4.7; 30 -4.7; 32 -4.7; 35 -4.6; 37 -4.5; 40 -4.3; 42 -4.2; 45 -4.0; 49 -3.6; 52 -3.3; 56 -2.9; 59 -2.6; 64 -1.9; 68 -1.4; 73 -1.2; 78 -1.3; 83 -1.9; 89 -3.2; 95 -4.4; 102 -4.8; 109 -4.2; 117 -3.4; 125 -2.7; 134 -2.4; 143 -2.2; 153 -1.5; 164 -0.8; 175 -1.2; 188 -1.3; 201 -1.5; 215 -1.4; 230 -1.5; 246 -1.7; 263 -1.9; 282 -2.3; 301 -2.2; 323 -2.3; 345 -2.5; 369 -3.9; 395 -4.5; 423 -3.9; 452 -3.5; 484 -3.5; 518 -3.1; 554 -2.7; 593 -2.0; 635 -1.6; 679 -1.1; 726 -0.2; 777 0.6; 832 -0.4; 890 -0.3; 952 -0.0; 1019 0.0; 1090 0.3; 1167 0.4; 1248 0.3; 1336 0.1; 1429 -0.5; 1529 -0.9; 1636 -1.1; 1751 -1.1; 1873 -0.7; 2004 0.2; 2145 1.1; 2295 1.6; 2455 2.6; 2627 3.4; 2811 4.0; 3008 4.7; 3219 4.7; 3444 4.5; 3685 4.2; 3943 3.2; 4219 3.6; 4514 2.9; 4830 2.0; 5168 3.4; 5530 5.8; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -4.2; 22 -4.4; 23 -4.5; 25 -4.6; 26 -4.7; 28 -4.7; 30 -4.7; 32 -4.7; 35 -4.6; 37 -4.5; 40 -4.3; 42 -4.2; 45 -4.0; 49 -3.6; 52 -3.3; 56 -2.9; 59 -2.6; 64 -1.9; 68 -1.4; 73 -1.2; 78 -1.3; 83 -1.9; 89 -3.2; 95 -4.4; 102 -4.8; 109 -4.2; 117 -3.4; 125 -2.7; 134 -2.4; 143 -2.2; 153 -1.5; 164 -0.8; 175 -1.2; 188 -1.3; 201 -1.5; 215 -1.4; 230 -1.5; 246 -1.7; 263 -1.9; 282 -2.3; 301 -2.2; 323 -2.3; 345 -2.5; 369 -3.9; 395 -4.5; 423 -3.9; 452 -3.5; 484 -3.5; 518 -3.1; 554 -2.7; 593 -2.0; 635 -1.6; 679 -1.1; 726 -0.2; 777 0.6; 832 -0.4; 890 -0.3; 952 -0.0; 1019 0.0; 1090 0.3; 1167 0.4; 1248 0.3; 1336 0.1; 1429 -0.5; 1529 -0.9; 1636 -1.1; 1751 -1.1; 1873 -0.7; 2004 0.2; 2145 1.1; 2295 1.6; 2455 2.6; 2627 3.4; 2811 4.0; 3008 4.7; 3219 4.7; 3444 4.5; 3685 4.2; 3943 3.2; 4219 3.6; 4514 2.9; 4830 2.0; 5168 3.4; 5530 5.8; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/SMS%20DJ%20Pro/SMS%20DJ%20Pro.png)