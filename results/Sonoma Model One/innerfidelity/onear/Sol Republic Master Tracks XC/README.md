# Sol Republic Master Tracks XC
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 3.4; 22 2.9; 23 2.7; 25 2.4; 26 2.2; 28 2.0; 30 1.7; 32 1.5; 35 1.2; 37 1.0; 40 0.7; 42 0.5; 45 0.2; 49 -0.1; 52 -0.4; 56 -0.5; 59 -0.5; 64 -0.3; 68 0.1; 73 0.6; 78 0.8; 83 0.6; 89 0.1; 95 -0.6; 102 -1.5; 109 -2.2; 117 -3.0; 125 -3.9; 134 -4.4; 143 -4.8; 153 -5.2; 164 -5.2; 175 -5.1; 188 -5.4; 201 -5.4; 215 -5.3; 230 -5.1; 246 -5.0; 263 -4.8; 282 -4.4; 301 -4.1; 323 -3.5; 345 -3.0; 369 -2.3; 395 -1.7; 423 -1.2; 452 -1.6; 484 -1.9; 518 -1.7; 554 -1.3; 593 -0.9; 635 -0.4; 679 0.2; 726 0.6; 777 0.7; 832 0.5; 890 0.3; 952 0.1; 1019 0.1; 1090 0.6; 1167 1.7; 1248 2.9; 1336 3.6; 1429 4.1; 1529 4.6; 1636 4.6; 1751 4.5; 1873 4.7; 2004 5.6; 2145 6.0; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 5.9; 4219 3.9; 4514 1.9; 4830 1.6; 5168 5.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 3.4; 22 2.9; 23 2.7; 25 2.4; 26 2.2; 28 2.0; 30 1.7; 32 1.5; 35 1.2; 37 1.0; 40 0.7; 42 0.5; 45 0.2; 49 -0.1; 52 -0.4; 56 -0.5; 59 -0.5; 64 -0.3; 68 0.1; 73 0.6; 78 0.8; 83 0.6; 89 0.1; 95 -0.6; 102 -1.5; 109 -2.2; 117 -3.0; 125 -3.9; 134 -4.4; 143 -4.8; 153 -5.2; 164 -5.2; 175 -5.1; 188 -5.4; 201 -5.4; 215 -5.3; 230 -5.1; 246 -5.0; 263 -4.8; 282 -4.4; 301 -4.1; 323 -3.5; 345 -3.0; 369 -2.3; 395 -1.7; 423 -1.2; 452 -1.6; 484 -1.9; 518 -1.7; 554 -1.3; 593 -0.9; 635 -0.4; 679 0.2; 726 0.6; 777 0.7; 832 0.5; 890 0.3; 952 0.1; 1019 0.1; 1090 0.6; 1167 1.7; 1248 2.9; 1336 3.6; 1429 4.1; 1529 4.6; 1636 4.6; 1751 4.5; 1873 4.7; 2004 5.6; 2145 6.0; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 5.9; 4219 3.9; 4514 1.9; 4830 1.6; 5168 5.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Sol%20Republic%20Master%20Tracks%20XC/Sol%20Republic%20Master%20Tracks%20XC.png)