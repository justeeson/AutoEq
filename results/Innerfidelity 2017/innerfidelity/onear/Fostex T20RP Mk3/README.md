# Fostex T20RP Mk3
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 5.9; 40 5.4; 42 4.8; 45 3.7; 49 2.3; 52 1.3; 56 0.3; 59 -0.5; 64 -1.7; 68 -2.5; 73 -3.3; 78 -4.1; 83 -4.6; 89 -5.2; 95 -5.6; 102 -5.8; 109 -5.9; 117 -6.0; 125 -6.1; 134 -6.0; 143 -5.9; 153 -5.6; 164 -5.3; 175 -4.8; 188 -4.5; 201 -4.1; 215 -3.8; 230 -3.7; 246 -3.6; 263 -3.4; 282 -3.2; 301 -3.6; 323 -3.4; 345 -2.5; 369 -1.8; 395 -1.6; 423 -1.5; 452 -1.4; 484 0.2; 518 0.3; 554 0.7; 593 1.2; 635 1.9; 679 1.9; 726 1.9; 777 2.3; 832 1.5; 890 1.0; 952 0.6; 1019 0.0; 1090 0.1; 1167 -0.4; 1248 0.8; 1336 -0.4; 1429 0.5; 1529 1.9; 1636 1.9; 1751 2.4; 1873 1.6; 2004 2.6; 2145 2.6; 2295 2.3; 2455 2.7; 2627 2.8; 2811 2.7; 3008 2.7; 3219 2.5; 3444 2.1; 3685 1.9; 3943 1.7; 4219 2.1; 4514 3.0; 4830 4.4; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 -0.1; 8299 -2.9; 8880 -5.1; 9502 -5.8; 10167 -4.4; 10879 -1.1; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 5.9; 40 5.4; 42 4.8; 45 3.7; 49 2.3; 52 1.3; 56 0.3; 59 -0.5; 64 -1.7; 68 -2.5; 73 -3.3; 78 -4.1; 83 -4.6; 89 -5.2; 95 -5.6; 102 -5.8; 109 -5.9; 117 -6.0; 125 -6.1; 134 -6.0; 143 -5.9; 153 -5.6; 164 -5.3; 175 -4.8; 188 -4.5; 201 -4.1; 215 -3.8; 230 -3.7; 246 -3.6; 263 -3.4; 282 -3.2; 301 -3.6; 323 -3.4; 345 -2.5; 369 -1.8; 395 -1.6; 423 -1.5; 452 -1.4; 484 0.2; 518 0.3; 554 0.7; 593 1.2; 635 1.9; 679 1.9; 726 1.9; 777 2.3; 832 1.5; 890 1.0; 952 0.6; 1019 0.0; 1090 0.1; 1167 -0.4; 1248 0.8; 1336 -0.4; 1429 0.5; 1529 1.9; 1636 1.9; 1751 2.4; 1873 1.6; 2004 2.6; 2145 2.6; 2295 2.3; 2455 2.7; 2627 2.8; 2811 2.7; 3008 2.7; 3219 2.5; 3444 2.1; 3685 1.9; 3943 1.7; 4219 2.1; 4514 3.0; 4830 4.4; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 -0.1; 8299 -2.9; 8880 -5.1; 9502 -5.8; 10167 -4.4; 10879 -1.1; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Fostex%20T20RP%20Mk3/Fostex%20T20RP%20Mk3.png)