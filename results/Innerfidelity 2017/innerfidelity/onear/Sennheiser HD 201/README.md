# Sennheiser HD 201
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 6.0; 109 6.0; 117 6.0; 125 5.6; 134 5.0; 143 4.4; 153 4.0; 164 3.8; 175 3.4; 188 3.2; 201 3.1; 215 2.9; 230 2.7; 246 2.1; 263 1.7; 282 1.4; 301 1.1; 323 0.6; 345 0.2; 369 -0.2; 395 -0.6; 423 -0.9; 452 -1.3; 484 -1.7; 518 -1.6; 554 -1.1; 593 -0.5; 635 -0.3; 679 -0.3; 726 -0.5; 777 -0.8; 832 -1.0; 890 -1.0; 952 -0.4; 1019 0.1; 1090 0.2; 1167 -0.3; 1248 -0.0; 1336 0.1; 1429 0.2; 1529 0.7; 1636 1.4; 1751 0.5; 1873 0.2; 2004 0.4; 2145 0.9; 2295 1.6; 2455 2.7; 2627 3.4; 2811 3.7; 3008 4.2; 3219 4.8; 3444 4.3; 3685 3.9; 3943 5.4; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.2; 8299 -3.0; 8880 -4.4; 9502 -2.9; 10167 -0.8; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 6.0; 109 6.0; 117 6.0; 125 5.6; 134 5.0; 143 4.4; 153 4.0; 164 3.8; 175 3.4; 188 3.2; 201 3.1; 215 2.9; 230 2.7; 246 2.1; 263 1.7; 282 1.4; 301 1.1; 323 0.6; 345 0.2; 369 -0.2; 395 -0.6; 423 -0.9; 452 -1.3; 484 -1.7; 518 -1.6; 554 -1.1; 593 -0.5; 635 -0.3; 679 -0.3; 726 -0.5; 777 -0.8; 832 -1.0; 890 -1.0; 952 -0.4; 1019 0.1; 1090 0.2; 1167 -0.3; 1248 -0.0; 1336 0.1; 1429 0.2; 1529 0.7; 1636 1.4; 1751 0.5; 1873 0.2; 2004 0.4; 2145 0.9; 2295 1.6; 2455 2.7; 2627 3.4; 2811 3.7; 3008 4.2; 3219 4.8; 3444 4.3; 3685 3.9; 3943 5.4; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.2; 8299 -3.0; 8880 -4.4; 9502 -2.9; 10167 -0.8; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Sennheiser%20HD%20201/Sennheiser%20HD%20201.png)