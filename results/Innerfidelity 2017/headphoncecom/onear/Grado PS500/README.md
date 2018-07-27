# Grado PS500
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 5.8; 26 5.6; 28 5.0; 30 4.4; 32 3.7; 35 2.8; 37 2.3; 40 1.5; 42 1.0; 45 0.3; 49 -0.6; 52 -1.2; 56 -1.9; 59 -2.3; 64 -3.0; 68 -3.4; 73 -3.8; 78 -4.0; 83 -4.1; 89 -4.4; 95 -4.7; 102 -5.0; 109 -5.0; 117 -5.2; 125 -5.3; 134 -5.3; 143 -5.2; 153 -5.1; 164 -4.8; 175 -4.5; 188 -4.3; 201 -4.2; 215 -3.9; 230 -3.6; 246 -3.4; 263 -3.2; 282 -2.9; 301 -2.7; 323 -2.4; 345 -2.1; 369 -1.8; 395 -1.6; 423 -1.6; 452 -1.6; 484 -1.6; 518 -1.4; 554 -0.8; 593 -0.2; 635 0.1; 679 -0.1; 726 0.0; 777 0.3; 832 0.3; 890 0.2; 952 0.2; 1019 -0.0; 1090 -0.3; 1167 -0.8; 1248 -1.3; 1336 -1.9; 1429 -2.6; 1529 -3.1; 1636 -3.3; 1751 -2.6; 1873 -2.7; 2004 -4.4; 2145 -5.3; 2295 -1.7; 2455 0.5; 2627 2.3; 2811 4.7; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -0.0; 8880 -2.4; 9502 -3.5; 10167 -1.4; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 5.8; 26 5.6; 28 5.0; 30 4.4; 32 3.7; 35 2.8; 37 2.3; 40 1.5; 42 1.0; 45 0.3; 49 -0.6; 52 -1.2; 56 -1.9; 59 -2.3; 64 -3.0; 68 -3.4; 73 -3.8; 78 -4.0; 83 -4.1; 89 -4.4; 95 -4.7; 102 -5.0; 109 -5.0; 117 -5.2; 125 -5.3; 134 -5.3; 143 -5.2; 153 -5.1; 164 -4.8; 175 -4.5; 188 -4.3; 201 -4.2; 215 -3.9; 230 -3.6; 246 -3.4; 263 -3.2; 282 -2.9; 301 -2.7; 323 -2.4; 345 -2.1; 369 -1.8; 395 -1.6; 423 -1.6; 452 -1.6; 484 -1.6; 518 -1.4; 554 -0.8; 593 -0.2; 635 0.1; 679 -0.1; 726 0.0; 777 0.3; 832 0.3; 890 0.2; 952 0.2; 1019 -0.0; 1090 -0.3; 1167 -0.8; 1248 -1.3; 1336 -1.9; 1429 -2.6; 1529 -3.1; 1636 -3.3; 1751 -2.6; 1873 -2.7; 2004 -4.4; 2145 -5.3; 2295 -1.7; 2455 0.5; 2627 2.3; 2811 4.7; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -0.0; 8880 -2.4; 9502 -3.5; 10167 -1.4; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/headphoncecom/onear/Grado%20PS500/Grado%20PS500.png)