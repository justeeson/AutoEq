# Sennheiser PX 100 II
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-62**.
```
GraphicEQ: 10 -84; 20 6.2; 22 5.3; 23 5.0; 25 4.3; 26 4.0; 28 3.4; 30 2.9; 32 2.5; 35 1.9; 37 1.6; 40 1.2; 42 0.9; 45 0.5; 49 0.1; 52 -0.2; 56 -0.6; 59 -0.8; 64 -1.1; 68 -1.4; 73 -1.6; 78 -1.9; 83 -2.1; 89 -2.4; 95 -2.6; 102 -2.7; 109 -3.0; 117 -3.5; 125 -4.0; 134 -4.4; 143 -4.7; 153 -4.8; 164 -4.9; 175 -4.9; 188 -4.8; 201 -4.9; 215 -4.7; 230 -4.6; 246 -4.4; 263 -4.4; 282 -4.0; 301 -3.7; 323 -3.7; 345 -3.4; 369 -3.1; 395 -2.8; 423 -2.7; 452 -2.8; 484 -2.9; 518 -2.6; 554 -1.9; 593 -1.3; 635 -1.0; 679 -0.9; 726 -0.6; 777 -0.3; 832 -0.1; 890 -0.1; 952 0.0; 1019 -0.1; 1090 -0.2; 1167 -0.4; 1248 -0.6; 1336 -0.9; 1429 -1.3; 1529 -1.6; 1636 -2.3; 1751 -2.7; 1873 -2.9; 2004 -2.5; 2145 -1.4; 2295 0.4; 2455 2.6; 2627 3.7; 2811 4.8; 3008 4.4; 3219 2.7; 3444 3.6; 3685 5.4; 3943 5.5; 4219 2.3; 4514 0.8; 4830 3.1; 5168 5.7; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.8; 9502 -0.5; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.2; 22 5.3; 23 5.0; 25 4.3; 26 4.0; 28 3.4; 30 2.9; 32 2.5; 35 1.9; 37 1.6; 40 1.2; 42 0.9; 45 0.5; 49 0.1; 52 -0.2; 56 -0.6; 59 -0.8; 64 -1.1; 68 -1.4; 73 -1.6; 78 -1.9; 83 -2.1; 89 -2.4; 95 -2.6; 102 -2.7; 109 -3.0; 117 -3.5; 125 -4.0; 134 -4.4; 143 -4.7; 153 -4.8; 164 -4.9; 175 -4.9; 188 -4.8; 201 -4.9; 215 -4.7; 230 -4.6; 246 -4.4; 263 -4.4; 282 -4.0; 301 -3.7; 323 -3.7; 345 -3.4; 369 -3.1; 395 -2.8; 423 -2.7; 452 -2.8; 484 -2.9; 518 -2.6; 554 -1.9; 593 -1.3; 635 -1.0; 679 -0.9; 726 -0.6; 777 -0.3; 832 -0.1; 890 -0.1; 952 0.0; 1019 -0.1; 1090 -0.2; 1167 -0.4; 1248 -0.6; 1336 -0.9; 1429 -1.3; 1529 -1.6; 1636 -2.3; 1751 -2.7; 1873 -2.9; 2004 -2.5; 2145 -1.4; 2295 0.4; 2455 2.6; 2627 3.7; 2811 4.8; 3008 4.4; 3219 2.7; 3444 3.6; 3685 5.4; 3943 5.5; 4219 2.3; 4514 0.8; 4830 3.1; 5168 5.7; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.8; 9502 -0.5; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.2dB*l, R=-6.2dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/headphoncecom/onear/Sennheiser%20PX%20100%20II/Sennheiser%20PX%20100%20II.png)