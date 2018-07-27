# Flare Audio Reference R1
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 5.8; 52 5.1; 56 3.9; 59 3.0; 64 1.8; 68 0.9; 73 -0.1; 78 -1.0; 83 -1.7; 89 -2.3; 95 -3.0; 102 -3.9; 109 -4.5; 117 -5.1; 125 -5.7; 134 -6.0; 143 -6.3; 153 -6.5; 164 -6.6; 175 -6.6; 188 -6.7; 201 -6.8; 215 -6.8; 230 -6.9; 246 -7.1; 263 -7.1; 282 -7.3; 301 -7.3; 323 -7.3; 345 -7.2; 369 -7.3; 395 -7.4; 423 -7.5; 452 -8.0; 484 -8.6; 518 -8.9; 554 -8.9; 593 -8.6; 635 -8.5; 679 -8.4; 726 -7.7; 777 -6.7; 832 -5.4; 890 -3.6; 952 -1.7; 1019 0.7; 1090 3.0; 1167 5.5; 1248 6.0; 1336 6.0; 1429 6.0; 1529 6.0; 1636 3.6; 1751 -1.3; 1873 -4.3; 2004 -4.7; 2145 -1.9; 2295 0.7; 2455 3.4; 2627 5.3; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 5.8; 52 5.1; 56 3.9; 59 3.0; 64 1.8; 68 0.9; 73 -0.1; 78 -1.0; 83 -1.7; 89 -2.3; 95 -3.0; 102 -3.9; 109 -4.5; 117 -5.1; 125 -5.7; 134 -6.0; 143 -6.3; 153 -6.5; 164 -6.6; 175 -6.6; 188 -6.7; 201 -6.8; 215 -6.8; 230 -6.9; 246 -7.1; 263 -7.1; 282 -7.3; 301 -7.3; 323 -7.3; 345 -7.2; 369 -7.3; 395 -7.4; 423 -7.5; 452 -8.0; 484 -8.6; 518 -8.9; 554 -8.9; 593 -8.6; 635 -8.5; 679 -8.4; 726 -7.7; 777 -6.7; 832 -5.4; 890 -3.6; 952 -1.7; 1019 0.7; 1090 3.0; 1167 5.5; 1248 6.0; 1336 6.0; 1429 6.0; 1529 6.0; 1636 3.6; 1751 -1.3; 1873 -4.3; 2004 -4.7; 2145 -1.9; 2295 0.7; 2455 3.4; 2627 5.3; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Flare%20Audio%20Reference%20R1/Flare%20Audio%20Reference%20R1.png)