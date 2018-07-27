# Sennheiser Momentum
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 3.1; 22 2.9; 23 2.8; 25 2.7; 26 2.6; 28 2.5; 30 2.3; 32 2.2; 35 2.1; 37 1.9; 40 1.8; 42 1.8; 45 1.7; 49 1.6; 52 1.5; 56 1.4; 59 1.4; 64 1.3; 68 1.2; 73 1.0; 78 0.8; 83 0.6; 89 0.2; 95 -0.2; 102 -0.7; 109 -1.0; 117 -1.3; 125 -1.5; 134 -1.6; 143 -1.9; 153 -2.5; 164 -2.8; 175 -2.3; 188 -2.6; 201 -2.8; 215 -2.8; 230 -2.7; 246 -2.6; 263 -2.3; 282 -2.0; 301 -1.8; 323 -1.4; 345 -1.0; 369 -0.6; 395 -0.2; 423 0.2; 452 0.4; 484 0.7; 518 0.9; 554 1.1; 593 1.0; 635 1.0; 679 0.9; 726 0.7; 777 0.5; 832 0.3; 890 0.1; 952 -0.0; 1019 0.0; 1090 0.2; 1167 0.4; 1248 0.7; 1336 0.9; 1429 1.1; 1529 1.3; 1636 1.6; 1751 1.9; 1873 2.3; 2004 3.0; 2145 4.0; 2295 5.1; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 3.1; 22 2.9; 23 2.8; 25 2.7; 26 2.6; 28 2.5; 30 2.3; 32 2.2; 35 2.1; 37 1.9; 40 1.8; 42 1.8; 45 1.7; 49 1.6; 52 1.5; 56 1.4; 59 1.4; 64 1.3; 68 1.2; 73 1.0; 78 0.8; 83 0.6; 89 0.2; 95 -0.2; 102 -0.7; 109 -1.0; 117 -1.3; 125 -1.5; 134 -1.6; 143 -1.9; 153 -2.5; 164 -2.8; 175 -2.3; 188 -2.6; 201 -2.8; 215 -2.8; 230 -2.7; 246 -2.6; 263 -2.3; 282 -2.0; 301 -1.8; 323 -1.4; 345 -1.0; 369 -0.6; 395 -0.2; 423 0.2; 452 0.4; 484 0.7; 518 0.9; 554 1.1; 593 1.0; 635 1.0; 679 0.9; 726 0.7; 777 0.5; 832 0.3; 890 0.1; 952 -0.0; 1019 0.0; 1090 0.2; 1167 0.4; 1248 0.7; 1336 0.9; 1429 1.1; 1529 1.3; 1636 1.6; 1751 1.9; 1873 2.3; 2004 3.0; 2145 4.0; 2295 5.1; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/Sennheiser%20Momentum/Sennheiser%20Momentum.png)