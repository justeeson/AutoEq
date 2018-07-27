# PSB M4U 2 passive
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -0.7; 22 -0.7; 23 -0.7; 25 -0.7; 26 -0.7; 28 -0.7; 30 -0.7; 32 -0.6; 35 -0.5; 37 -0.4; 40 -0.2; 42 -0.1; 45 0.1; 49 0.3; 52 0.5; 56 0.8; 59 1.1; 64 1.7; 68 2.1; 73 2.5; 78 2.8; 83 2.3; 89 0.7; 95 -1.1; 102 -2.6; 109 -3.1; 117 -3.1; 125 -2.9; 134 -3.1; 143 -3.1; 153 -2.7; 164 -1.8; 175 -2.9; 188 -2.9; 201 -2.3; 215 -1.9; 230 -1.4; 246 -1.0; 263 -0.3; 282 0.5; 301 0.7; 323 0.9; 345 1.3; 369 1.1; 395 1.7; 423 2.4; 452 2.4; 484 2.4; 518 2.4; 554 2.2; 593 2.1; 635 2.2; 679 1.8; 726 1.5; 777 1.1; 832 0.5; 890 0.2; 952 0.1; 1019 0.0; 1090 0.2; 1167 0.4; 1248 0.7; 1336 1.1; 1429 1.6; 1529 2.2; 1636 2.5; 1751 2.9; 1873 3.4; 2004 3.8; 2145 4.1; 2295 4.3; 2455 4.6; 2627 5.0; 2811 5.2; 3008 4.4; 3219 3.4; 3444 2.5; 3685 1.7; 3943 1.8; 4219 3.7; 4514 5.0; 4830 5.9; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.4; 6775 3.8; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -0.7; 22 -0.7; 23 -0.7; 25 -0.7; 26 -0.7; 28 -0.7; 30 -0.7; 32 -0.6; 35 -0.5; 37 -0.4; 40 -0.2; 42 -0.1; 45 0.1; 49 0.3; 52 0.5; 56 0.8; 59 1.1; 64 1.7; 68 2.1; 73 2.5; 78 2.8; 83 2.3; 89 0.7; 95 -1.1; 102 -2.6; 109 -3.1; 117 -3.1; 125 -2.9; 134 -3.1; 143 -3.1; 153 -2.7; 164 -1.8; 175 -2.9; 188 -2.9; 201 -2.3; 215 -1.9; 230 -1.4; 246 -1.0; 263 -0.3; 282 0.5; 301 0.7; 323 0.9; 345 1.3; 369 1.1; 395 1.7; 423 2.4; 452 2.4; 484 2.4; 518 2.4; 554 2.2; 593 2.1; 635 2.2; 679 1.8; 726 1.5; 777 1.1; 832 0.5; 890 0.2; 952 0.1; 1019 0.0; 1090 0.2; 1167 0.4; 1248 0.7; 1336 1.1; 1429 1.6; 1529 2.2; 1636 2.5; 1751 2.9; 1873 3.4; 2004 3.8; 2145 4.1; 2295 4.3; 2455 4.6; 2627 5.0; 2811 5.2; 3008 4.4; 3219 3.4; 3444 2.5; 3685 1.7; 3943 1.8; 4219 3.7; 4514 5.0; 4830 5.9; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.4; 6775 3.8; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/PSB%20M4U%202%20passive/PSB%20M4U%202%20passive.png)