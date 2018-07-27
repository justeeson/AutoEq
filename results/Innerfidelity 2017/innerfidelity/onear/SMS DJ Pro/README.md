# SMS DJ Pro
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -5.0; 22 -5.3; 23 -5.4; 25 -5.5; 26 -5.6; 28 -5.6; 30 -5.6; 32 -5.6; 35 -5.4; 37 -5.3; 40 -5.2; 42 -5.0; 45 -4.8; 49 -4.4; 52 -4.1; 56 -3.8; 59 -3.4; 64 -2.7; 68 -2.3; 73 -2.1; 78 -2.2; 83 -2.7; 89 -4.1; 95 -5.3; 102 -5.6; 109 -5.0; 117 -4.2; 125 -3.6; 134 -3.4; 143 -3.2; 153 -2.5; 164 -1.8; 175 -2.3; 188 -2.4; 201 -2.6; 215 -2.6; 230 -2.7; 246 -3.0; 263 -3.3; 282 -3.8; 301 -3.8; 323 -3.9; 345 -4.1; 369 -5.5; 395 -6.2; 423 -5.7; 452 -5.4; 484 -5.6; 518 -5.0; 554 -4.3; 593 -3.3; 635 -2.7; 679 -2.1; 726 -1.0; 777 -0.0; 832 -0.8; 890 -0.5; 952 -0.1; 1019 0.0; 1090 0.3; 1167 0.3; 1248 0.1; 1336 0.0; 1429 -0.3; 1529 -0.5; 1636 -0.7; 1751 -0.8; 1873 -0.6; 2004 0.2; 2145 1.0; 2295 1.5; 2455 2.5; 2627 3.5; 2811 4.3; 3008 5.2; 3219 5.3; 3444 5.2; 3685 5.5; 3943 5.7; 4219 6.0; 4514 6.0; 4830 5.5; 5168 5.6; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -5.0; 22 -5.3; 23 -5.4; 25 -5.5; 26 -5.6; 28 -5.6; 30 -5.6; 32 -5.6; 35 -5.4; 37 -5.3; 40 -5.2; 42 -5.0; 45 -4.8; 49 -4.4; 52 -4.1; 56 -3.8; 59 -3.4; 64 -2.7; 68 -2.3; 73 -2.1; 78 -2.2; 83 -2.7; 89 -4.1; 95 -5.3; 102 -5.6; 109 -5.0; 117 -4.2; 125 -3.6; 134 -3.4; 143 -3.2; 153 -2.5; 164 -1.8; 175 -2.3; 188 -2.4; 201 -2.6; 215 -2.6; 230 -2.7; 246 -3.0; 263 -3.3; 282 -3.8; 301 -3.8; 323 -3.9; 345 -4.1; 369 -5.5; 395 -6.2; 423 -5.7; 452 -5.4; 484 -5.6; 518 -5.0; 554 -4.3; 593 -3.3; 635 -2.7; 679 -2.1; 726 -1.0; 777 -0.0; 832 -0.8; 890 -0.5; 952 -0.1; 1019 0.0; 1090 0.3; 1167 0.3; 1248 0.1; 1336 0.0; 1429 -0.3; 1529 -0.5; 1636 -0.7; 1751 -0.8; 1873 -0.6; 2004 0.2; 2145 1.0; 2295 1.5; 2455 2.5; 2627 3.5; 2811 4.3; 3008 5.2; 3219 5.3; 3444 5.2; 3685 5.5; 3943 5.7; 4219 6.0; 4514 6.0; 4830 5.5; 5168 5.6; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/SMS%20DJ%20Pro/SMS%20DJ%20Pro.png)