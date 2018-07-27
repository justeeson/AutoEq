# Grado SR225
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 5.9; 49 5.2; 52 4.5; 56 3.6; 59 3.1; 64 2.3; 68 1.7; 73 1.1; 78 0.7; 83 0.3; 89 -0.1; 95 -0.5; 102 -1.0; 109 -1.4; 117 -1.7; 125 -2.0; 134 -2.3; 143 -2.3; 153 -2.4; 164 -2.4; 175 -2.3; 188 -2.3; 201 -2.4; 215 -2.4; 230 -2.1; 246 -2.2; 263 -2.2; 282 -2.2; 301 -2.2; 323 -2.0; 345 -1.5; 369 -1.4; 395 -1.4; 423 -1.4; 452 -1.6; 484 -1.8; 518 -1.6; 554 -1.2; 593 -0.6; 635 -0.3; 679 -0.3; 726 -0.2; 777 0.1; 832 0.1; 890 0.1; 952 0.1; 1019 -0.1; 1090 -0.4; 1167 -0.8; 1248 -1.1; 1336 -1.6; 1429 -2.1; 1529 -2.7; 1636 -3.4; 1751 -4.1; 1873 -4.8; 2004 -5.3; 2145 -5.6; 2295 -5.5; 2455 -4.8; 2627 -4.5; 2811 -4.3; 3008 -3.7; 3219 -3.7; 3444 -3.8; 3685 -4.9; 3943 -6.5; 4219 -7.5; 4514 -5.8; 4830 -4.8; 5168 -5.2; 5530 -6.9; 5917 -7.5; 6331 -6.1; 6775 -4.8; 7249 -2.1; 7756 -2.8; 8299 -5.2; 8880 -8.7; 9502 -11.3; 10167 -11.6; 10879 -9.7; 11640 -6.6; 12455 -3.5; 13327 -1.4; 14260 -0.6; 15258 -0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 5.9; 49 5.2; 52 4.5; 56 3.6; 59 3.1; 64 2.3; 68 1.7; 73 1.1; 78 0.7; 83 0.3; 89 -0.1; 95 -0.5; 102 -1.0; 109 -1.4; 117 -1.7; 125 -2.0; 134 -2.3; 143 -2.3; 153 -2.4; 164 -2.4; 175 -2.3; 188 -2.3; 201 -2.4; 215 -2.4; 230 -2.1; 246 -2.2; 263 -2.2; 282 -2.2; 301 -2.2; 323 -2.0; 345 -1.5; 369 -1.4; 395 -1.4; 423 -1.4; 452 -1.6; 484 -1.8; 518 -1.6; 554 -1.2; 593 -0.6; 635 -0.3; 679 -0.3; 726 -0.2; 777 0.1; 832 0.1; 890 0.1; 952 0.1; 1019 -0.1; 1090 -0.4; 1167 -0.8; 1248 -1.1; 1336 -1.6; 1429 -2.1; 1529 -2.7; 1636 -3.4; 1751 -4.1; 1873 -4.8; 2004 -5.3; 2145 -5.6; 2295 -5.5; 2455 -4.8; 2627 -4.5; 2811 -4.3; 3008 -3.7; 3219 -3.7; 3444 -3.8; 3685 -4.9; 3943 -6.5; 4219 -7.5; 4514 -5.8; 4830 -4.8; 5168 -5.2; 5530 -6.9; 5917 -7.5; 6331 -6.1; 6775 -4.8; 7249 -2.1; 7756 -2.8; 8299 -5.2; 8880 -8.7; 9502 -11.3; 10167 -11.6; 10879 -9.7; 11640 -6.6; 12455 -3.5; 13327 -1.4; 14260 -0.6; 15258 -0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/headphoncecom/onear/Grado%20SR225/Grado%20SR225.png)