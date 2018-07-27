# Nocs NS700
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -2.5; 22 -3.1; 23 -3.4; 25 -3.8; 26 -3.9; 28 -4.2; 30 -4.5; 32 -4.7; 35 -5.1; 37 -5.2; 40 -5.3; 42 -5.4; 45 -5.4; 49 -5.5; 52 -5.5; 56 -5.5; 59 -5.5; 64 -5.5; 68 -5.5; 73 -5.6; 78 -5.6; 83 -5.5; 89 -5.5; 95 -5.2; 102 -4.9; 109 -4.3; 117 -4.1; 125 -5.0; 134 -5.4; 143 -5.6; 153 -5.3; 164 -4.4; 175 -3.6; 188 -3.2; 201 -2.4; 215 -1.5; 230 -0.7; 246 -0.0; 263 0.3; 282 0.3; 301 -0.4; 323 -2.2; 345 -3.3; 369 -3.7; 395 -3.6; 423 -3.5; 452 -3.5; 484 -3.6; 518 -3.3; 554 -2.8; 593 -2.1; 635 -1.8; 679 -1.7; 726 -1.4; 777 -0.9; 832 -0.6; 890 -0.4; 952 -0.1; 1019 0.2; 1090 0.6; 1167 0.9; 1248 1.2; 1336 1.3; 1429 1.3; 1529 0.8; 1636 1.3; 1751 1.6; 1873 1.6; 2004 1.6; 2145 1.5; 2295 1.3; 2455 1.1; 2627 0.7; 2811 0.1; 3008 -0.4; 3219 -0.7; 3444 -0.4; 3685 0.5; 3943 3.3; 4219 5.7; 4514 6.0; 4830 4.8; 5168 2.7; 5530 1.9; 5917 3.3; 6331 2.4; 6775 0.4; 7249 0.0; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -2.5; 22 -3.1; 23 -3.4; 25 -3.8; 26 -3.9; 28 -4.2; 30 -4.5; 32 -4.7; 35 -5.1; 37 -5.2; 40 -5.3; 42 -5.4; 45 -5.4; 49 -5.5; 52 -5.5; 56 -5.5; 59 -5.5; 64 -5.5; 68 -5.5; 73 -5.6; 78 -5.6; 83 -5.5; 89 -5.5; 95 -5.2; 102 -4.9; 109 -4.3; 117 -4.1; 125 -5.0; 134 -5.4; 143 -5.6; 153 -5.3; 164 -4.4; 175 -3.6; 188 -3.2; 201 -2.4; 215 -1.5; 230 -0.7; 246 -0.0; 263 0.3; 282 0.3; 301 -0.4; 323 -2.2; 345 -3.3; 369 -3.7; 395 -3.6; 423 -3.5; 452 -3.5; 484 -3.6; 518 -3.3; 554 -2.8; 593 -2.1; 635 -1.8; 679 -1.7; 726 -1.4; 777 -0.9; 832 -0.6; 890 -0.4; 952 -0.1; 1019 0.2; 1090 0.6; 1167 0.9; 1248 1.2; 1336 1.3; 1429 1.3; 1529 0.8; 1636 1.3; 1751 1.6; 1873 1.6; 2004 1.6; 2145 1.5; 2295 1.3; 2455 1.1; 2627 0.7; 2811 0.1; 3008 -0.4; 3219 -0.7; 3444 -0.4; 3685 0.5; 3943 3.3; 4219 5.7; 4514 6.0; 4830 4.8; 5168 2.7; 5530 1.9; 5917 3.3; 6331 2.4; 6775 0.4; 7249 0.0; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Nocs%20NS700/Nocs%20NS700.png)