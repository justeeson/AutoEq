# Beyerdynamic Custom Pro One switch position 1
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 5.9; 40 5.7; 42 5.5; 45 5.3; 49 5.3; 52 5.3; 56 5.3; 59 5.2; 64 5.3; 68 5.8; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 4.6; 102 -0.6; 109 -2.8; 117 -3.9; 125 -5.2; 134 -6.0; 143 -6.1; 153 -5.7; 164 -4.8; 175 -6.5; 188 -6.7; 201 -6.3; 215 -6.1; 230 -5.7; 246 -5.3; 263 -5.2; 282 -4.7; 301 -4.4; 323 -4.1; 345 -3.7; 369 -3.4; 395 -3.1; 423 -2.6; 452 -2.4; 484 -2.2; 518 -2.0; 554 -1.6; 593 -1.3; 635 -1.1; 679 -1.1; 726 -1.0; 777 0.0; 832 0.2; 890 -0.0; 952 -0.1; 1019 0.0; 1090 0.1; 1167 0.2; 1248 0.2; 1336 -0.2; 1429 -0.8; 1529 -1.5; 1636 -2.2; 1751 -2.8; 1873 -3.2; 2004 -3.5; 2145 -3.4; 2295 -3.0; 2455 -1.8; 2627 -0.8; 2811 0.2; 3008 1.3; 3219 1.8; 3444 2.3; 3685 3.0; 3943 3.7; 4219 4.8; 4514 5.5; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 4.7; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -1.0; 9502 -0.8; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 5.9; 40 5.7; 42 5.5; 45 5.3; 49 5.3; 52 5.3; 56 5.3; 59 5.2; 64 5.3; 68 5.8; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 4.6; 102 -0.6; 109 -2.8; 117 -3.9; 125 -5.2; 134 -6.0; 143 -6.1; 153 -5.7; 164 -4.8; 175 -6.5; 188 -6.7; 201 -6.3; 215 -6.1; 230 -5.7; 246 -5.3; 263 -5.2; 282 -4.7; 301 -4.4; 323 -4.1; 345 -3.7; 369 -3.4; 395 -3.1; 423 -2.6; 452 -2.4; 484 -2.2; 518 -2.0; 554 -1.6; 593 -1.3; 635 -1.1; 679 -1.1; 726 -1.0; 777 0.0; 832 0.2; 890 -0.0; 952 -0.1; 1019 0.0; 1090 0.1; 1167 0.2; 1248 0.2; 1336 -0.2; 1429 -0.8; 1529 -1.5; 1636 -2.2; 1751 -2.8; 1873 -3.2; 2004 -3.5; 2145 -3.4; 2295 -3.0; 2455 -1.8; 2627 -0.8; 2811 0.2; 3008 1.3; 3219 1.8; 3444 2.3; 3685 3.0; 3943 3.7; 4219 4.8; 4514 5.5; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 4.7; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -1.0; 9502 -0.8; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/Beyerdynamic%20Custom%20Pro%20One%20switch%20position%201/Beyerdynamic%20Custom%20Pro%20One%20switch%20position%201.png)