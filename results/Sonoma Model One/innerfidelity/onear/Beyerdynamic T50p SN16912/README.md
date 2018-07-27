# Beyerdynamic T50p SN16912
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 5.7; 59 5.5; 64 5.5; 68 5.8; 73 6.0; 78 6.0; 83 6.0; 89 5.8; 95 5.0; 102 4.6; 109 4.7; 117 4.5; 125 3.8; 134 3.5; 143 3.4; 153 3.3; 164 3.4; 175 2.3; 188 0.9; 201 -0.5; 215 -1.7; 230 -2.8; 246 -3.4; 263 -3.5; 282 -3.7; 301 -4.5; 323 -5.3; 345 -5.3; 369 -5.0; 395 -4.7; 423 -4.3; 452 -4.0; 484 -3.5; 518 -3.2; 554 -2.8; 593 -2.4; 635 -1.8; 679 -0.8; 726 0.3; 777 0.8; 832 0.6; 890 0.3; 952 0.1; 1019 0.1; 1090 0.7; 1167 1.7; 1248 2.5; 1336 2.9; 1429 3.2; 1529 3.2; 1636 2.8; 1751 2.4; 1873 2.4; 2004 3.0; 2145 4.2; 2295 5.6; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -1.5; 8880 -3.6; 9502 -2.5; 10167 -0.9; 10879 -0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 5.7; 59 5.5; 64 5.5; 68 5.8; 73 6.0; 78 6.0; 83 6.0; 89 5.8; 95 5.0; 102 4.6; 109 4.7; 117 4.5; 125 3.8; 134 3.5; 143 3.4; 153 3.3; 164 3.4; 175 2.3; 188 0.9; 201 -0.5; 215 -1.7; 230 -2.8; 246 -3.4; 263 -3.5; 282 -3.7; 301 -4.5; 323 -5.3; 345 -5.3; 369 -5.0; 395 -4.7; 423 -4.3; 452 -4.0; 484 -3.5; 518 -3.2; 554 -2.8; 593 -2.4; 635 -1.8; 679 -0.8; 726 0.3; 777 0.8; 832 0.6; 890 0.3; 952 0.1; 1019 0.1; 1090 0.7; 1167 1.7; 1248 2.5; 1336 2.9; 1429 3.2; 1529 3.2; 1636 2.8; 1751 2.4; 1873 2.4; 2004 3.0; 2145 4.2; 2295 5.6; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -1.5; 8880 -3.6; 9502 -2.5; 10167 -0.9; 10879 -0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Beyerdynamic%20T50p%20SN16912/Beyerdynamic%20T50p%20SN16912.png)