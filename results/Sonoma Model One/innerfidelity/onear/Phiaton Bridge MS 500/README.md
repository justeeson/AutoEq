# Phiaton Bridge MS 500
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 5.6; 23 5.4; 25 5.0; 26 4.9; 28 4.6; 30 4.4; 32 4.1; 35 3.8; 37 3.6; 40 3.3; 42 3.1; 45 2.8; 49 2.4; 52 2.2; 56 2.0; 59 2.1; 64 2.4; 68 2.8; 73 3.2; 78 3.4; 83 3.4; 89 3.1; 95 2.6; 102 2.2; 109 2.0; 117 1.2; 125 0.6; 134 0.3; 143 0.3; 153 0.5; 164 1.2; 175 1.5; 188 2.0; 201 2.6; 215 3.3; 230 4.0; 246 4.6; 263 5.1; 282 5.6; 301 5.5; 323 5.2; 345 5.1; 369 4.8; 395 4.4; 423 4.1; 452 3.8; 484 3.4; 518 2.8; 554 2.4; 593 2.1; 635 2.0; 679 2.2; 726 2.2; 777 1.9; 832 1.3; 890 1.2; 952 0.7; 1019 -0.2; 1090 0.0; 1167 0.9; 1248 1.7; 1336 2.3; 1429 3.1; 1529 3.7; 1636 3.1; 1751 1.6; 1873 1.1; 2004 2.2; 2145 3.7; 2295 5.1; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 5.2; 3444 3.9; 3685 2.7; 3943 1.8; 4219 2.8; 4514 4.8; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 5.6; 23 5.4; 25 5.0; 26 4.9; 28 4.6; 30 4.4; 32 4.1; 35 3.8; 37 3.6; 40 3.3; 42 3.1; 45 2.8; 49 2.4; 52 2.2; 56 2.0; 59 2.1; 64 2.4; 68 2.8; 73 3.2; 78 3.4; 83 3.4; 89 3.1; 95 2.6; 102 2.2; 109 2.0; 117 1.2; 125 0.6; 134 0.3; 143 0.3; 153 0.5; 164 1.2; 175 1.5; 188 2.0; 201 2.6; 215 3.3; 230 4.0; 246 4.6; 263 5.1; 282 5.6; 301 5.5; 323 5.2; 345 5.1; 369 4.8; 395 4.4; 423 4.1; 452 3.8; 484 3.4; 518 2.8; 554 2.4; 593 2.1; 635 2.0; 679 2.2; 726 2.2; 777 1.9; 832 1.3; 890 1.2; 952 0.7; 1019 -0.2; 1090 0.0; 1167 0.9; 1248 1.7; 1336 2.3; 1429 3.1; 1529 3.7; 1636 3.1; 1751 1.6; 1873 1.1; 2004 2.2; 2145 3.7; 2295 5.1; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 5.2; 3444 3.9; 3685 2.7; 3943 1.8; 4219 2.8; 4514 4.8; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Phiaton%20Bridge%20MS%20500/Phiaton%20Bridge%20MS%20500.png)