# Sansui SS35 Pads Off
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 5.9; 49 5.6; 52 5.3; 56 5.0; 59 4.7; 64 4.3; 68 4.1; 73 3.9; 78 3.7; 83 3.5; 89 3.2; 95 2.8; 102 2.5; 109 2.2; 117 1.7; 125 1.5; 134 1.3; 143 1.1; 153 1.0; 164 1.1; 175 1.5; 188 1.4; 201 1.7; 215 2.1; 230 2.6; 246 3.0; 263 3.2; 282 3.2; 301 3.0; 323 2.4; 345 1.5; 369 1.0; 395 0.7; 423 0.5; 452 0.6; 484 0.6; 518 0.9; 554 1.6; 593 2.3; 635 2.9; 679 3.2; 726 3.2; 777 2.8; 832 2.1; 890 1.3; 952 0.6; 1019 -0.2; 1090 -0.5; 1167 -0.5; 1248 0.0; 1336 1.0; 1429 2.6; 1529 4.6; 1636 5.9; 1751 6.0; 1873 6.0; 2004 6.0; 2145 5.2; 2295 4.4; 2455 5.5; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 5.9; 49 5.6; 52 5.3; 56 5.0; 59 4.7; 64 4.3; 68 4.1; 73 3.9; 78 3.7; 83 3.5; 89 3.2; 95 2.8; 102 2.5; 109 2.2; 117 1.7; 125 1.5; 134 1.3; 143 1.1; 153 1.0; 164 1.1; 175 1.5; 188 1.4; 201 1.7; 215 2.1; 230 2.6; 246 3.0; 263 3.2; 282 3.2; 301 3.0; 323 2.4; 345 1.5; 369 1.0; 395 0.7; 423 0.5; 452 0.6; 484 0.6; 518 0.9; 554 1.6; 593 2.3; 635 2.9; 679 3.2; 726 3.2; 777 2.8; 832 2.1; 890 1.3; 952 0.6; 1019 -0.2; 1090 -0.5; 1167 -0.5; 1248 0.0; 1336 1.0; 1429 2.6; 1529 4.6; 1636 5.9; 1751 6.0; 1873 6.0; 2004 6.0; 2145 5.2; 2295 4.4; 2455 5.5; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/Sansui%20SS35%20Pads%20Off/Sansui%20SS35%20Pads%20Off.png)