# AKG K81DJ
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 5.9; 25 5.6; 26 5.4; 28 5.1; 30 4.7; 32 4.3; 35 3.9; 37 3.6; 40 3.2; 42 3.1; 45 2.9; 49 2.7; 52 2.4; 56 2.0; 59 1.8; 64 1.4; 68 1.3; 73 1.3; 78 1.0; 83 0.7; 89 0.6; 95 1.0; 102 0.9; 109 -0.0; 117 -1.0; 125 -1.9; 134 -2.6; 143 -3.0; 153 -3.1; 164 -2.8; 175 -3.0; 188 -2.9; 201 -2.1; 215 -1.3; 230 -1.0; 246 -0.6; 263 -0.6; 282 -0.8; 301 -0.5; 323 -0.3; 345 0.5; 369 1.6; 395 2.1; 423 2.3; 452 2.2; 484 2.1; 518 1.9; 554 1.8; 593 1.8; 635 1.5; 679 1.2; 726 0.9; 777 1.0; 832 0.7; 890 0.4; 952 0.2; 1019 -0.0; 1090 -0.2; 1167 -0.3; 1248 -0.4; 1336 -0.8; 1429 -1.3; 1529 -1.8; 1636 -2.2; 1751 -2.4; 1873 -2.5; 2004 -2.0; 2145 -1.8; 2295 -1.1; 2455 0.5; 2627 1.5; 2811 2.4; 3008 3.4; 3219 3.7; 3444 3.5; 3685 3.1; 3943 2.8; 4219 2.2; 4514 2.0; 4830 3.0; 5168 3.8; 5530 1.6; 5917 2.5; 6331 4.6; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 -0.9; 16326 -2.0; 17469 -2.4; 18692 -0.9; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 5.9; 25 5.6; 26 5.4; 28 5.1; 30 4.7; 32 4.3; 35 3.9; 37 3.6; 40 3.2; 42 3.1; 45 2.9; 49 2.7; 52 2.4; 56 2.0; 59 1.8; 64 1.4; 68 1.3; 73 1.3; 78 1.0; 83 0.7; 89 0.6; 95 1.0; 102 0.9; 109 -0.0; 117 -1.0; 125 -1.9; 134 -2.6; 143 -3.0; 153 -3.1; 164 -2.8; 175 -3.0; 188 -2.9; 201 -2.1; 215 -1.3; 230 -1.0; 246 -0.6; 263 -0.6; 282 -0.8; 301 -0.5; 323 -0.3; 345 0.5; 369 1.6; 395 2.1; 423 2.3; 452 2.2; 484 2.1; 518 1.9; 554 1.8; 593 1.8; 635 1.5; 679 1.2; 726 0.9; 777 1.0; 832 0.7; 890 0.4; 952 0.2; 1019 -0.0; 1090 -0.2; 1167 -0.3; 1248 -0.4; 1336 -0.8; 1429 -1.3; 1529 -1.8; 1636 -2.2; 1751 -2.4; 1873 -2.5; 2004 -2.0; 2145 -1.8; 2295 -1.1; 2455 0.5; 2627 1.5; 2811 2.4; 3008 3.4; 3219 3.7; 3444 3.5; 3685 3.1; 3943 2.8; 4219 2.2; 4514 2.0; 4830 3.0; 5168 3.8; 5530 1.6; 5917 2.5; 6331 4.6; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 -0.9; 16326 -2.0; 17469 -2.4; 18692 -0.9; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/AKG%20K81DJ/AKG%20K81DJ.png)