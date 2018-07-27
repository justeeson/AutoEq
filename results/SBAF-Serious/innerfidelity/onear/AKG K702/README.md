# AKG K702
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-27**.
```
GraphicEQ: 10 -84; 20 2.7; 22 2.1; 23 1.8; 25 1.3; 26 1.1; 28 0.7; 30 0.3; 32 0.0; 35 -0.4; 37 -0.6; 40 -0.8; 42 -1.0; 45 -1.2; 49 -1.5; 52 -1.6; 56 -1.8; 59 -1.9; 64 -2.0; 68 -2.2; 73 -2.2; 78 -1.9; 83 -1.9; 89 -2.2; 95 -2.6; 102 -2.8; 109 -2.8; 117 -3.5; 125 -4.2; 134 -4.7; 143 -5.0; 153 -5.2; 164 -5.0; 175 -4.9; 188 -5.1; 201 -5.1; 215 -4.9; 230 -4.8; 246 -4.8; 263 -4.7; 282 -4.5; 301 -4.3; 323 -4.0; 345 -3.8; 369 -3.6; 395 -3.3; 423 -2.9; 452 -2.6; 484 -2.4; 518 -1.6; 554 0.1; 593 0.2; 635 0.4; 679 0.8; 726 1.1; 777 1.2; 832 0.8; 890 0.5; 952 0.3; 1019 -0.1; 1090 -0.6; 1167 -0.7; 1248 -0.5; 1336 -1.0; 1429 -1.6; 1529 -2.4; 1636 -3.1; 1751 -3.9; 1873 -4.2; 2004 -5.3; 2145 -5.6; 2295 -5.3; 2455 -4.6; 2627 -3.3; 2811 -2.2; 3008 -0.9; 3219 0.2; 3444 0.2; 3685 -0.0; 3943 -0.8; 4219 -2.7; 4514 -3.5; 4830 -3.4; 5168 -2.7; 5530 -2.8; 5917 -4.6; 6331 -6.0; 6775 -6.4; 7249 -6.5; 7756 -6.6; 8299 -7.1; 8880 -6.3; 9502 -3.1; 10167 -0.1; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 -2.1; 17469 -4.8; 18692 -5.4; 20000 -3.8
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 2.7; 22 2.1; 23 1.8; 25 1.3; 26 1.1; 28 0.7; 30 0.3; 32 0.0; 35 -0.4; 37 -0.6; 40 -0.8; 42 -1.0; 45 -1.2; 49 -1.5; 52 -1.6; 56 -1.8; 59 -1.9; 64 -2.0; 68 -2.2; 73 -2.2; 78 -1.9; 83 -1.9; 89 -2.2; 95 -2.6; 102 -2.8; 109 -2.8; 117 -3.5; 125 -4.2; 134 -4.7; 143 -5.0; 153 -5.2; 164 -5.0; 175 -4.9; 188 -5.1; 201 -5.1; 215 -4.9; 230 -4.8; 246 -4.8; 263 -4.7; 282 -4.5; 301 -4.3; 323 -4.0; 345 -3.8; 369 -3.6; 395 -3.3; 423 -2.9; 452 -2.6; 484 -2.4; 518 -1.6; 554 0.1; 593 0.2; 635 0.4; 679 0.8; 726 1.1; 777 1.2; 832 0.8; 890 0.5; 952 0.3; 1019 -0.1; 1090 -0.6; 1167 -0.7; 1248 -0.5; 1336 -1.0; 1429 -1.6; 1529 -2.4; 1636 -3.1; 1751 -3.9; 1873 -4.2; 2004 -5.3; 2145 -5.6; 2295 -5.3; 2455 -4.6; 2627 -3.3; 2811 -2.2; 3008 -0.9; 3219 0.2; 3444 0.2; 3685 -0.0; 3943 -0.8; 4219 -2.7; 4514 -3.5; 4830 -3.4; 5168 -2.7; 5530 -2.8; 5917 -4.6; 6331 -6.0; 6775 -6.4; 7249 -6.5; 7756 -6.6; 8299 -7.1; 8880 -6.3; 9502 -3.1; 10167 -0.1; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 -2.1; 17469 -4.8; 18692 -5.4; 20000 -3.8
Copy: L=-2.7dB*l, R=-2.7dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/AKG%20K702/AKG%20K702.png)