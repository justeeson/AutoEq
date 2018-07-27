# Skullcandy Mix Master
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 5.5; 22 4.7; 23 4.3; 25 3.6; 26 3.3; 28 2.7; 30 2.3; 32 1.9; 35 1.5; 37 1.3; 40 1.1; 42 0.9; 45 0.8; 49 0.7; 52 0.6; 56 0.6; 59 0.6; 64 0.7; 68 0.8; 73 0.8; 78 0.5; 83 0.2; 89 -0.0; 95 -0.4; 102 -0.8; 109 -0.9; 117 -1.3; 125 -1.7; 134 -2.1; 143 -2.3; 153 -2.5; 164 -2.5; 175 -2.5; 188 -2.7; 201 -2.8; 215 -2.8; 230 -2.7; 246 -2.5; 263 -2.2; 282 -1.8; 301 -1.5; 323 -1.5; 345 -1.3; 369 -1.0; 395 -1.1; 423 -1.0; 452 -0.5; 484 -0.2; 518 0.4; 554 1.1; 593 1.5; 635 1.6; 679 1.5; 726 1.4; 777 1.4; 832 0.9; 890 0.3; 952 -0.0; 1019 -0.0; 1090 -0.0; 1167 -0.3; 1248 -0.8; 1336 -1.7; 1429 -2.5; 1529 -2.8; 1636 -3.1; 1751 -2.7; 1873 -1.9; 2004 -1.6; 2145 -0.7; 2295 0.4; 2455 1.9; 2627 3.1; 2811 4.1; 3008 4.9; 3219 5.4; 3444 4.3; 3685 0.6; 3943 -1.4; 4219 -0.2; 4514 1.8; 4830 3.5; 5168 5.9; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 5.5; 22 4.7; 23 4.3; 25 3.6; 26 3.3; 28 2.7; 30 2.3; 32 1.9; 35 1.5; 37 1.3; 40 1.1; 42 0.9; 45 0.8; 49 0.7; 52 0.6; 56 0.6; 59 0.6; 64 0.7; 68 0.8; 73 0.8; 78 0.5; 83 0.2; 89 -0.0; 95 -0.4; 102 -0.8; 109 -0.9; 117 -1.3; 125 -1.7; 134 -2.1; 143 -2.3; 153 -2.5; 164 -2.5; 175 -2.5; 188 -2.7; 201 -2.8; 215 -2.8; 230 -2.7; 246 -2.5; 263 -2.2; 282 -1.8; 301 -1.5; 323 -1.5; 345 -1.3; 369 -1.0; 395 -1.1; 423 -1.0; 452 -0.5; 484 -0.2; 518 0.4; 554 1.1; 593 1.5; 635 1.6; 679 1.5; 726 1.4; 777 1.4; 832 0.9; 890 0.3; 952 -0.0; 1019 -0.0; 1090 -0.0; 1167 -0.3; 1248 -0.8; 1336 -1.7; 1429 -2.5; 1529 -2.8; 1636 -3.1; 1751 -2.7; 1873 -1.9; 2004 -1.6; 2145 -0.7; 2295 0.4; 2455 1.9; 2627 3.1; 2811 4.1; 3008 4.9; 3219 5.4; 3444 4.3; 3685 0.6; 3943 -1.4; 4219 -0.2; 4514 1.8; 4830 3.5; 5168 5.9; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/Skullcandy%20Mix%20Master/Skullcandy%20Mix%20Master.png)