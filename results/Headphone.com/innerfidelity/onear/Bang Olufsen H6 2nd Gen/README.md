# Bang Olufsen H6 2nd Gen
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 5.1; 22 4.2; 23 3.7; 25 3.0; 26 2.7; 28 2.1; 30 1.6; 32 1.1; 35 0.5; 37 0.2; 40 -0.2; 42 -0.3; 45 -0.5; 49 -0.7; 52 -0.8; 56 -0.8; 59 -0.8; 64 -0.7; 68 -0.5; 73 -0.3; 78 -0.2; 83 -0.2; 89 -0.0; 95 0.3; 102 0.7; 109 0.8; 117 0.4; 125 -0.6; 134 -1.2; 143 -0.8; 153 0.8; 164 3.2; 175 3.7; 188 3.3; 201 3.9; 215 4.6; 230 5.5; 246 5.3; 263 4.7; 282 3.9; 301 3.3; 323 2.6; 345 2.1; 369 1.8; 395 1.5; 423 1.4; 452 1.2; 484 1.1; 518 1.1; 554 1.1; 593 1.1; 635 1.0; 679 1.0; 726 0.8; 777 0.5; 832 0.3; 890 0.2; 952 0.1; 1019 -0.0; 1090 0.1; 1167 0.5; 1248 0.9; 1336 1.4; 1429 2.0; 1529 2.4; 1636 2.6; 1751 2.6; 1873 2.8; 2004 3.2; 2145 3.8; 2295 4.7; 2455 5.7; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 5.1; 22 4.2; 23 3.7; 25 3.0; 26 2.7; 28 2.1; 30 1.6; 32 1.1; 35 0.5; 37 0.2; 40 -0.2; 42 -0.3; 45 -0.5; 49 -0.7; 52 -0.8; 56 -0.8; 59 -0.8; 64 -0.7; 68 -0.5; 73 -0.3; 78 -0.2; 83 -0.2; 89 -0.0; 95 0.3; 102 0.7; 109 0.8; 117 0.4; 125 -0.6; 134 -1.2; 143 -0.8; 153 0.8; 164 3.2; 175 3.7; 188 3.3; 201 3.9; 215 4.6; 230 5.5; 246 5.3; 263 4.7; 282 3.9; 301 3.3; 323 2.6; 345 2.1; 369 1.8; 395 1.5; 423 1.4; 452 1.2; 484 1.1; 518 1.1; 554 1.1; 593 1.1; 635 1.0; 679 1.0; 726 0.8; 777 0.5; 832 0.3; 890 0.2; 952 0.1; 1019 -0.0; 1090 0.1; 1167 0.5; 1248 0.9; 1336 1.4; 1429 2.0; 1529 2.4; 1636 2.6; 1751 2.6; 1873 2.8; 2004 3.2; 2145 3.8; 2295 4.7; 2455 5.7; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/Bang%20Olufsen%20H6%202nd%20Gen/Bang%20Olufsen%20H6%202nd%20Gen.png)