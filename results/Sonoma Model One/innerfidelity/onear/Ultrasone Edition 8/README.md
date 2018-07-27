# Ultrasone Edition 8
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 5.9; 102 4.9; 109 4.1; 117 3.4; 125 2.6; 134 1.8; 143 1.3; 153 1.0; 164 1.2; 175 0.3; 188 -0.4; 201 -0.8; 215 -1.0; 230 -0.9; 246 -0.8; 263 -0.3; 282 -0.4; 301 -0.7; 323 -0.6; 345 -0.4; 369 -0.4; 395 -0.3; 423 -0.1; 452 0.1; 484 0.3; 518 0.3; 554 0.5; 593 0.9; 635 1.4; 679 1.8; 726 2.2; 777 2.3; 832 1.9; 890 1.1; 952 0.3; 1019 0.2; 1090 1.1; 1167 2.3; 1248 3.4; 1336 4.4; 1429 5.2; 1529 5.5; 1636 5.4; 1751 5.4; 1873 5.9; 2004 6.0; 2145 6.0; 2295 6.0; 2455 3.9; 2627 2.3; 2811 3.3; 3008 4.7; 3219 5.8; 3444 5.2; 3685 2.4; 3943 2.4; 4219 5.1; 4514 6.0; 4830 6.0; 5168 6.0; 5530 3.5; 5917 -4.8; 6331 -6.8; 6775 -4.6; 7249 -1.4; 7756 0.2; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 -3.5; 14260 -7.8; 15258 -7.8; 16326 -3.8; 17469 -0.2; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 5.9; 102 4.9; 109 4.1; 117 3.4; 125 2.6; 134 1.8; 143 1.3; 153 1.0; 164 1.2; 175 0.3; 188 -0.4; 201 -0.8; 215 -1.0; 230 -0.9; 246 -0.8; 263 -0.3; 282 -0.4; 301 -0.7; 323 -0.6; 345 -0.4; 369 -0.4; 395 -0.3; 423 -0.1; 452 0.1; 484 0.3; 518 0.3; 554 0.5; 593 0.9; 635 1.4; 679 1.8; 726 2.2; 777 2.3; 832 1.9; 890 1.1; 952 0.3; 1019 0.2; 1090 1.1; 1167 2.3; 1248 3.4; 1336 4.4; 1429 5.2; 1529 5.5; 1636 5.4; 1751 5.4; 1873 5.9; 2004 6.0; 2145 6.0; 2295 6.0; 2455 3.9; 2627 2.3; 2811 3.3; 3008 4.7; 3219 5.8; 3444 5.2; 3685 2.4; 3943 2.4; 4219 5.1; 4514 6.0; 4830 6.0; 5168 6.0; 5530 3.5; 5917 -4.8; 6331 -6.8; 6775 -4.6; 7249 -1.4; 7756 0.2; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 -3.5; 14260 -7.8; 15258 -7.8; 16326 -3.8; 17469 -0.2; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Ultrasone%20Edition%208/Ultrasone%20Edition%208.png)