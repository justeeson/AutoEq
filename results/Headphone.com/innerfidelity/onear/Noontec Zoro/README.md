# Noontec Zoro
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -0.4; 22 -0.7; 23 -0.9; 25 -1.2; 26 -1.3; 28 -1.5; 30 -1.7; 32 -1.9; 35 -2.1; 37 -2.2; 40 -2.4; 42 -2.4; 45 -2.5; 49 -2.6; 52 -2.6; 56 -2.7; 59 -2.7; 64 -2.8; 68 -2.9; 73 -3.1; 78 -3.3; 83 -3.5; 89 -3.8; 95 -4.1; 102 -4.6; 109 -5.0; 117 -5.4; 125 -5.8; 134 -6.0; 143 -6.1; 153 -6.2; 164 -6.4; 175 -6.2; 188 -6.3; 201 -6.3; 215 -6.2; 230 -6.2; 246 -6.0; 263 -5.8; 282 -5.5; 301 -5.3; 323 -5.3; 345 -5.3; 369 -5.2; 395 -4.9; 423 -4.5; 452 -4.3; 484 -4.0; 518 -3.6; 554 -3.3; 593 -2.9; 635 -2.4; 679 -1.9; 726 -1.4; 777 -1.0; 832 -0.6; 890 -0.2; 952 -0.0; 1019 0.0; 1090 0.0; 1167 0.2; 1248 0.6; 1336 0.7; 1429 0.8; 1529 0.9; 1636 1.3; 1751 1.9; 1873 2.5; 2004 3.9; 2145 5.3; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 -0.6; 8299 -1.0; 8880 -0.1; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -0.4; 22 -0.7; 23 -0.9; 25 -1.2; 26 -1.3; 28 -1.5; 30 -1.7; 32 -1.9; 35 -2.1; 37 -2.2; 40 -2.4; 42 -2.4; 45 -2.5; 49 -2.6; 52 -2.6; 56 -2.7; 59 -2.7; 64 -2.8; 68 -2.9; 73 -3.1; 78 -3.3; 83 -3.5; 89 -3.8; 95 -4.1; 102 -4.6; 109 -5.0; 117 -5.4; 125 -5.8; 134 -6.0; 143 -6.1; 153 -6.2; 164 -6.4; 175 -6.2; 188 -6.3; 201 -6.3; 215 -6.2; 230 -6.2; 246 -6.0; 263 -5.8; 282 -5.5; 301 -5.3; 323 -5.3; 345 -5.3; 369 -5.2; 395 -4.9; 423 -4.5; 452 -4.3; 484 -4.0; 518 -3.6; 554 -3.3; 593 -2.9; 635 -2.4; 679 -1.9; 726 -1.4; 777 -1.0; 832 -0.6; 890 -0.2; 952 -0.0; 1019 0.0; 1090 0.0; 1167 0.2; 1248 0.6; 1336 0.7; 1429 0.8; 1529 0.9; 1636 1.3; 1751 1.9; 1873 2.5; 2004 3.9; 2145 5.3; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 -0.6; 8299 -1.0; 8880 -0.1; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/Noontec%20Zoro/Noontec%20Zoro.png)