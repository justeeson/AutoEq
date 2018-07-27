# Monster Beats Pro
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-46**.
```
GraphicEQ: 10 -84; 20 4.6; 22 3.8; 23 3.4; 25 2.7; 26 2.4; 28 1.8; 30 1.2; 32 0.7; 35 0.0; 37 -0.4; 40 -1.0; 42 -1.4; 45 -1.9; 49 -2.4; 52 -2.8; 56 -3.0; 59 -3.1; 64 -2.8; 68 -2.4; 73 -1.8; 78 -1.6; 83 -1.7; 89 -2.4; 95 -3.3; 102 -4.0; 109 -4.5; 117 -5.0; 125 -5.6; 134 -6.1; 143 -6.7; 153 -6.9; 164 -7.0; 175 -6.9; 188 -6.8; 201 -6.9; 215 -6.8; 230 -6.7; 246 -6.6; 263 -6.3; 282 -6.0; 301 -5.7; 323 -5.3; 345 -4.7; 369 -4.3; 395 -4.1; 423 -4.1; 452 -3.6; 484 -3.5; 518 -3.4; 554 -3.3; 593 -2.8; 635 -2.3; 679 -1.8; 726 -1.2; 777 -0.8; 832 -0.7; 890 -0.4; 952 -0.2; 1019 0.0; 1090 0.3; 1167 1.3; 1248 2.0; 1336 2.8; 1429 3.0; 1529 2.5; 1636 1.3; 1751 -0.4; 1873 -1.9; 2004 -3.1; 2145 -4.3; 2295 -5.7; 2455 -6.5; 2627 -6.7; 2811 -6.6; 3008 -5.4; 3219 -4.3; 3444 -3.1; 3685 -2.1; 3943 -1.6; 4219 -3.2; 4514 -4.3; 4830 -3.5; 5168 -1.0; 5530 1.3; 5917 3.6; 6331 0.3; 6775 -1.0; 7249 -1.2; 7756 -1.5; 8299 -2.6; 8880 -4.8; 9502 -7.1; 10167 -7.5; 10879 -5.1; 11640 -1.5; 12455 -0.0; 13327 -0.2; 14260 -1.5; 15258 -0.9; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 4.6; 22 3.8; 23 3.4; 25 2.7; 26 2.4; 28 1.8; 30 1.2; 32 0.7; 35 0.0; 37 -0.4; 40 -1.0; 42 -1.4; 45 -1.9; 49 -2.4; 52 -2.8; 56 -3.0; 59 -3.1; 64 -2.8; 68 -2.4; 73 -1.8; 78 -1.6; 83 -1.7; 89 -2.4; 95 -3.3; 102 -4.0; 109 -4.5; 117 -5.0; 125 -5.6; 134 -6.1; 143 -6.7; 153 -6.9; 164 -7.0; 175 -6.9; 188 -6.8; 201 -6.9; 215 -6.8; 230 -6.7; 246 -6.6; 263 -6.3; 282 -6.0; 301 -5.7; 323 -5.3; 345 -4.7; 369 -4.3; 395 -4.1; 423 -4.1; 452 -3.6; 484 -3.5; 518 -3.4; 554 -3.3; 593 -2.8; 635 -2.3; 679 -1.8; 726 -1.2; 777 -0.8; 832 -0.7; 890 -0.4; 952 -0.2; 1019 0.0; 1090 0.3; 1167 1.3; 1248 2.0; 1336 2.8; 1429 3.0; 1529 2.5; 1636 1.3; 1751 -0.4; 1873 -1.9; 2004 -3.1; 2145 -4.3; 2295 -5.7; 2455 -6.5; 2627 -6.7; 2811 -6.6; 3008 -5.4; 3219 -4.3; 3444 -3.1; 3685 -2.1; 3943 -1.6; 4219 -3.2; 4514 -4.3; 4830 -3.5; 5168 -1.0; 5530 1.3; 5917 3.6; 6331 0.3; 6775 -1.0; 7249 -1.2; 7756 -1.5; 8299 -2.6; 8880 -4.8; 9502 -7.1; 10167 -7.5; 10879 -5.1; 11640 -1.5; 12455 -0.0; 13327 -0.2; 14260 -1.5; 15258 -0.9; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-4.6dB*l, R=-4.6dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Monster%20Beats%20Pro/Monster%20Beats%20Pro.png)