# Sennheiser HD203
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 5.8; 22 4.9; 23 4.5; 25 3.7; 26 3.4; 28 2.9; 30 2.4; 32 2.1; 35 1.5; 37 0.9; 40 -0.2; 42 -0.8; 45 -1.3; 49 -1.8; 52 -2.0; 56 -2.5; 59 -2.8; 64 -3.3; 68 -3.4; 73 -3.2; 78 -2.7; 83 -2.5; 89 -3.1; 95 -3.7; 102 -4.0; 109 -4.0; 117 -4.0; 125 -3.9; 134 -3.7; 143 -3.3; 153 -2.7; 164 -1.7; 175 -0.7; 188 1.3; 201 4.2; 215 6.0; 230 5.4; 246 4.5; 263 3.9; 282 3.2; 301 2.4; 323 1.2; 345 -0.2; 369 -0.9; 395 -1.3; 423 -1.5; 452 -1.9; 484 -2.4; 518 -2.3; 554 -1.7; 593 -1.1; 635 -0.7; 679 -0.7; 726 -0.4; 777 -0.2; 832 -0.2; 890 -0.2; 952 0.1; 1019 -0.1; 1090 -0.5; 1167 -0.6; 1248 -0.7; 1336 -1.0; 1429 -0.9; 1529 -0.7; 1636 -0.5; 1751 0.3; 1873 1.1; 2004 1.6; 2145 2.6; 2295 3.8; 2455 4.9; 2627 5.6; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 4.3; 4830 5.4; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 5.8; 22 4.9; 23 4.5; 25 3.7; 26 3.4; 28 2.9; 30 2.4; 32 2.1; 35 1.5; 37 0.9; 40 -0.2; 42 -0.8; 45 -1.3; 49 -1.8; 52 -2.0; 56 -2.5; 59 -2.8; 64 -3.3; 68 -3.4; 73 -3.2; 78 -2.7; 83 -2.5; 89 -3.1; 95 -3.7; 102 -4.0; 109 -4.0; 117 -4.0; 125 -3.9; 134 -3.7; 143 -3.3; 153 -2.7; 164 -1.7; 175 -0.7; 188 1.3; 201 4.2; 215 6.0; 230 5.4; 246 4.5; 263 3.9; 282 3.2; 301 2.4; 323 1.2; 345 -0.2; 369 -0.9; 395 -1.3; 423 -1.5; 452 -1.9; 484 -2.4; 518 -2.3; 554 -1.7; 593 -1.1; 635 -0.7; 679 -0.7; 726 -0.4; 777 -0.2; 832 -0.2; 890 -0.2; 952 0.1; 1019 -0.1; 1090 -0.5; 1167 -0.6; 1248 -0.7; 1336 -1.0; 1429 -0.9; 1529 -0.7; 1636 -0.5; 1751 0.3; 1873 1.1; 2004 1.6; 2145 2.6; 2295 3.8; 2455 4.9; 2627 5.6; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 4.3; 4830 5.4; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/headphoncecom/onear/Sennheiser%20HD203/Sennheiser%20HD203.png)