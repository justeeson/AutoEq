# Koss BT540i Wired Passive
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 4.8; 22 3.8; 23 3.4; 25 2.6; 26 2.2; 28 1.5; 30 0.8; 32 0.3; 35 -0.5; 37 -0.9; 40 -1.6; 42 -1.9; 45 -2.4; 49 -3.1; 52 -3.5; 56 -3.9; 59 -4.0; 64 -4.0; 68 -3.8; 73 -3.4; 78 -3.3; 83 -3.4; 89 -3.9; 95 -4.7; 102 -5.5; 109 -5.8; 117 -6.1; 125 -6.6; 134 -7.4; 143 -8.1; 153 -8.8; 164 -8.6; 175 -7.8; 188 -8.3; 201 -8.4; 215 -8.3; 230 -8.0; 246 -7.7; 263 -7.2; 282 -6.3; 301 -5.5; 323 -5.2; 345 -4.5; 369 -3.5; 395 -2.2; 423 -0.9; 452 -0.1; 484 0.4; 518 0.7; 554 1.0; 593 1.3; 635 1.5; 679 1.6; 726 1.6; 777 1.5; 832 1.0; 890 0.5; 952 0.1; 1019 0.0; 1090 0.5; 1167 1.0; 1248 1.5; 1336 1.7; 1429 1.6; 1529 1.3; 1636 0.3; 1751 -0.8; 1873 -1.8; 2004 -2.2; 2145 -2.7; 2295 -3.2; 2455 -3.6; 2627 -4.2; 2811 -4.8; 3008 -5.1; 3219 -4.9; 3444 -3.7; 3685 -2.9; 3943 -1.3; 4219 -0.1; 4514 3.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 4.3; 6331 3.1; 6775 1.7; 7249 0.2; 7756 -1.1; 8299 -3.6; 8880 -6.1; 9502 -6.8; 10167 -5.1; 10879 -3.2; 11640 -2.6; 12455 -2.9; 13327 -3.5; 14260 -4.5; 15258 -5.2; 16326 -4.3; 17469 -1.4; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 4.8; 22 3.8; 23 3.4; 25 2.6; 26 2.2; 28 1.5; 30 0.8; 32 0.3; 35 -0.5; 37 -0.9; 40 -1.6; 42 -1.9; 45 -2.4; 49 -3.1; 52 -3.5; 56 -3.9; 59 -4.0; 64 -4.0; 68 -3.8; 73 -3.4; 78 -3.3; 83 -3.4; 89 -3.9; 95 -4.7; 102 -5.5; 109 -5.8; 117 -6.1; 125 -6.6; 134 -7.4; 143 -8.1; 153 -8.8; 164 -8.6; 175 -7.8; 188 -8.3; 201 -8.4; 215 -8.3; 230 -8.0; 246 -7.7; 263 -7.2; 282 -6.3; 301 -5.5; 323 -5.2; 345 -4.5; 369 -3.5; 395 -2.2; 423 -0.9; 452 -0.1; 484 0.4; 518 0.7; 554 1.0; 593 1.3; 635 1.5; 679 1.6; 726 1.6; 777 1.5; 832 1.0; 890 0.5; 952 0.1; 1019 0.0; 1090 0.5; 1167 1.0; 1248 1.5; 1336 1.7; 1429 1.6; 1529 1.3; 1636 0.3; 1751 -0.8; 1873 -1.8; 2004 -2.2; 2145 -2.7; 2295 -3.2; 2455 -3.6; 2627 -4.2; 2811 -4.8; 3008 -5.1; 3219 -4.9; 3444 -3.7; 3685 -2.9; 3943 -1.3; 4219 -0.1; 4514 3.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 4.3; 6331 3.1; 6775 1.7; 7249 0.2; 7756 -1.1; 8299 -3.6; 8880 -6.1; 9502 -6.8; 10167 -5.1; 10879 -3.2; 11640 -2.6; 12455 -2.9; 13327 -3.5; 14260 -4.5; 15258 -5.2; 16326 -4.3; 17469 -1.4; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Koss%20BT540i%20Wired%20Passive/Koss%20BT540i%20Wired%20Passive.png)