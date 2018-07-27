# Eskuche 33 1 3 B
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 5.8; 32 5.3; 35 4.2; 37 3.5; 40 2.6; 42 2.1; 45 1.5; 49 1.0; 52 0.7; 56 0.5; 59 0.4; 64 0.3; 68 0.3; 73 0.3; 78 0.2; 83 0.2; 89 0.0; 95 -0.2; 102 -0.3; 109 -0.3; 117 -0.4; 125 -0.7; 134 -1.0; 143 -1.3; 153 -1.6; 164 -1.6; 175 -1.6; 188 -1.7; 201 -1.8; 215 -1.9; 230 -2.0; 246 -2.1; 263 -2.2; 282 -2.1; 301 -2.1; 323 -2.1; 345 -1.9; 369 -1.9; 395 -2.0; 423 -2.2; 452 -2.3; 484 -2.7; 518 -3.0; 554 -2.9; 593 -2.6; 635 -2.5; 679 -2.6; 726 -2.5; 777 -2.3; 832 -2.0; 890 -1.5; 952 -0.4; 1019 0.2; 1090 0.8; 1167 1.4; 1248 1.5; 1336 2.3; 1429 3.0; 1529 3.2; 1636 3.5; 1751 3.9; 1873 4.1; 2004 4.2; 2145 4.5; 2295 4.4; 2455 4.2; 2627 4.2; 2811 4.3; 3008 5.3; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 4.9; 5530 5.6; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 5.8; 32 5.3; 35 4.2; 37 3.5; 40 2.6; 42 2.1; 45 1.5; 49 1.0; 52 0.7; 56 0.5; 59 0.4; 64 0.3; 68 0.3; 73 0.3; 78 0.2; 83 0.2; 89 0.0; 95 -0.2; 102 -0.3; 109 -0.3; 117 -0.4; 125 -0.7; 134 -1.0; 143 -1.3; 153 -1.6; 164 -1.6; 175 -1.6; 188 -1.7; 201 -1.8; 215 -1.9; 230 -2.0; 246 -2.1; 263 -2.2; 282 -2.1; 301 -2.1; 323 -2.1; 345 -1.9; 369 -1.9; 395 -2.0; 423 -2.2; 452 -2.3; 484 -2.7; 518 -3.0; 554 -2.9; 593 -2.6; 635 -2.5; 679 -2.6; 726 -2.5; 777 -2.3; 832 -2.0; 890 -1.5; 952 -0.4; 1019 0.2; 1090 0.8; 1167 1.4; 1248 1.5; 1336 2.3; 1429 3.0; 1529 3.2; 1636 3.5; 1751 3.9; 1873 4.1; 2004 4.2; 2145 4.5; 2295 4.4; 2455 4.2; 2627 4.2; 2811 4.3; 3008 5.3; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 4.9; 5530 5.6; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/Eskuche%2033%201%203%20B/Eskuche%2033%201%203%20B.png)