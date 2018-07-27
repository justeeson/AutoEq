# Denon AH-D1001K Silver
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 5.9; 40 5.4; 42 5.0; 45 4.6; 49 4.1; 52 3.9; 56 3.8; 59 3.7; 64 3.3; 68 3.0; 73 2.6; 78 2.3; 83 2.0; 89 1.7; 95 1.4; 102 0.9; 109 0.7; 117 0.5; 125 0.1; 134 0.2; 143 0.2; 153 0.2; 164 0.1; 175 0.2; 188 0.5; 201 0.7; 215 0.8; 230 0.9; 246 0.8; 263 0.8; 282 1.0; 301 1.1; 323 1.3; 345 1.6; 369 1.8; 395 2.0; 423 2.1; 452 2.0; 484 1.9; 518 2.0; 554 2.3; 593 2.6; 635 2.2; 679 1.6; 726 0.9; 777 0.4; 832 0.0; 890 -0.2; 952 -0.2; 1019 -0.0; 1090 0.3; 1167 0.6; 1248 0.7; 1336 0.8; 1429 1.2; 1529 1.5; 1636 1.7; 1751 1.9; 1873 2.4; 2004 3.0; 2145 3.6; 2295 4.3; 2455 4.7; 2627 4.5; 2811 4.0; 3008 3.9; 3219 3.1; 3444 3.0; 3685 5.8; 3943 5.6; 4219 3.7; 4514 3.6; 4830 3.7; 5168 5.1; 5530 6.0; 5917 5.9; 6331 5.6; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.3; 9502 -2.3; 10167 -3.0; 10879 -0.9; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 5.9; 40 5.4; 42 5.0; 45 4.6; 49 4.1; 52 3.9; 56 3.8; 59 3.7; 64 3.3; 68 3.0; 73 2.6; 78 2.3; 83 2.0; 89 1.7; 95 1.4; 102 0.9; 109 0.7; 117 0.5; 125 0.1; 134 0.2; 143 0.2; 153 0.2; 164 0.1; 175 0.2; 188 0.5; 201 0.7; 215 0.8; 230 0.9; 246 0.8; 263 0.8; 282 1.0; 301 1.1; 323 1.3; 345 1.6; 369 1.8; 395 2.0; 423 2.1; 452 2.0; 484 1.9; 518 2.0; 554 2.3; 593 2.6; 635 2.2; 679 1.6; 726 0.9; 777 0.4; 832 0.0; 890 -0.2; 952 -0.2; 1019 -0.0; 1090 0.3; 1167 0.6; 1248 0.7; 1336 0.8; 1429 1.2; 1529 1.5; 1636 1.7; 1751 1.9; 1873 2.4; 2004 3.0; 2145 3.6; 2295 4.3; 2455 4.7; 2627 4.5; 2811 4.0; 3008 3.9; 3219 3.1; 3444 3.0; 3685 5.8; 3943 5.6; 4219 3.7; 4514 3.6; 4830 3.7; 5168 5.1; 5530 6.0; 5917 5.9; 6331 5.6; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.3; 9502 -2.3; 10167 -3.0; 10879 -0.9; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/headphoncecom/onear/Denon%20AH-D1001K%20Silver/Denon%20AH-D1001K%20Silver.png)