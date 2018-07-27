# Koss Porta Pro
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 5.9; 28 5.5; 30 4.9; 32 4.2; 35 3.2; 37 2.6; 40 1.8; 42 1.4; 45 0.7; 49 -0.1; 52 -0.7; 56 -1.3; 59 -1.7; 64 -2.3; 68 -2.8; 73 -3.3; 78 -3.7; 83 -4.2; 89 -4.7; 95 -5.2; 102 -5.8; 109 -6.2; 117 -6.6; 125 -6.9; 134 -7.1; 143 -7.2; 153 -7.2; 164 -7.1; 175 -6.9; 188 -6.6; 201 -6.3; 215 -6.1; 230 -5.8; 246 -5.5; 263 -5.2; 282 -4.8; 301 -4.6; 323 -4.3; 345 -4.0; 369 -3.7; 395 -3.2; 423 -2.8; 452 -2.4; 484 -1.9; 518 -1.5; 554 -1.1; 593 -0.8; 635 -0.5; 679 -0.2; 726 0.0; 777 0.0; 832 0.0; 890 0.0; 952 -0.0; 1019 -0.0; 1090 0.0; 1167 0.0; 1248 0.1; 1336 0.3; 1429 0.4; 1529 0.3; 1636 -0.2; 1751 -0.7; 1873 -1.0; 2004 -0.7; 2145 0.2; 2295 1.5; 2455 3.1; 2627 5.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 5.9; 28 5.5; 30 4.9; 32 4.2; 35 3.2; 37 2.6; 40 1.8; 42 1.4; 45 0.7; 49 -0.1; 52 -0.7; 56 -1.3; 59 -1.7; 64 -2.3; 68 -2.8; 73 -3.3; 78 -3.7; 83 -4.2; 89 -4.7; 95 -5.2; 102 -5.8; 109 -6.2; 117 -6.6; 125 -6.9; 134 -7.1; 143 -7.2; 153 -7.2; 164 -7.1; 175 -6.9; 188 -6.6; 201 -6.3; 215 -6.1; 230 -5.8; 246 -5.5; 263 -5.2; 282 -4.8; 301 -4.6; 323 -4.3; 345 -4.0; 369 -3.7; 395 -3.2; 423 -2.8; 452 -2.4; 484 -1.9; 518 -1.5; 554 -1.1; 593 -0.8; 635 -0.5; 679 -0.2; 726 0.0; 777 0.0; 832 0.0; 890 0.0; 952 -0.0; 1019 -0.0; 1090 0.0; 1167 0.0; 1248 0.1; 1336 0.3; 1429 0.4; 1529 0.3; 1636 -0.2; 1751 -0.7; 1873 -1.0; 2004 -0.7; 2145 0.2; 2295 1.5; 2455 3.1; 2627 5.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/Koss%20Porta%20Pro/Koss%20Porta%20Pro.png)