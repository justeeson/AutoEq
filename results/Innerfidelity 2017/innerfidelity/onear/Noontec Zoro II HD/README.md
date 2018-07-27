# Noontec Zoro II HD
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -1.7; 22 -1.8; 23 -1.9; 25 -2.0; 26 -2.0; 28 -2.1; 30 -2.2; 32 -2.2; 35 -2.2; 37 -2.2; 40 -2.2; 42 -2.2; 45 -2.1; 49 -2.0; 52 -2.0; 56 -2.1; 59 -2.2; 64 -2.2; 68 -2.2; 73 -2.2; 78 -2.2; 83 -2.3; 89 -2.4; 95 -2.8; 102 -3.3; 109 -3.4; 117 -3.5; 125 -3.6; 134 -4.0; 143 -4.7; 153 -5.1; 164 -4.9; 175 -4.9; 188 -5.2; 201 -5.2; 215 -5.1; 230 -4.8; 246 -4.6; 263 -4.3; 282 -3.9; 301 -3.5; 323 -3.6; 345 -3.5; 369 -3.3; 395 -3.2; 423 -3.1; 452 -3.3; 484 -3.3; 518 -2.7; 554 -2.1; 593 -1.4; 635 -1.0; 679 -0.9; 726 -0.6; 777 -0.2; 832 -0.0; 890 -0.0; 952 0.0; 1019 -0.1; 1090 -0.2; 1167 -0.4; 1248 -0.7; 1336 -0.9; 1429 -1.1; 1529 -1.3; 1636 -1.4; 1751 -1.5; 1873 -1.4; 2004 -0.9; 2145 -0.3; 2295 0.4; 2455 1.3; 2627 1.9; 2811 2.4; 3008 3.4; 3219 3.8; 3444 5.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 5.1; 5530 4.8; 5917 4.1; 6331 2.6; 6775 1.5; 7249 1.2; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -1.7; 22 -1.8; 23 -1.9; 25 -2.0; 26 -2.0; 28 -2.1; 30 -2.2; 32 -2.2; 35 -2.2; 37 -2.2; 40 -2.2; 42 -2.2; 45 -2.1; 49 -2.0; 52 -2.0; 56 -2.1; 59 -2.2; 64 -2.2; 68 -2.2; 73 -2.2; 78 -2.2; 83 -2.3; 89 -2.4; 95 -2.8; 102 -3.3; 109 -3.4; 117 -3.5; 125 -3.6; 134 -4.0; 143 -4.7; 153 -5.1; 164 -4.9; 175 -4.9; 188 -5.2; 201 -5.2; 215 -5.1; 230 -4.8; 246 -4.6; 263 -4.3; 282 -3.9; 301 -3.5; 323 -3.6; 345 -3.5; 369 -3.3; 395 -3.2; 423 -3.1; 452 -3.3; 484 -3.3; 518 -2.7; 554 -2.1; 593 -1.4; 635 -1.0; 679 -0.9; 726 -0.6; 777 -0.2; 832 -0.0; 890 -0.0; 952 0.0; 1019 -0.1; 1090 -0.2; 1167 -0.4; 1248 -0.7; 1336 -0.9; 1429 -1.1; 1529 -1.3; 1636 -1.4; 1751 -1.5; 1873 -1.4; 2004 -0.9; 2145 -0.3; 2295 0.4; 2455 1.3; 2627 1.9; 2811 2.4; 3008 3.4; 3219 3.8; 3444 5.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 5.1; 5530 4.8; 5917 4.1; 6331 2.6; 6775 1.5; 7249 1.2; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Noontec%20Zoro%20II%20HD/Noontec%20Zoro%20II%20HD.png)