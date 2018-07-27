# Stax SR-Lambda Signature
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 5.9; 32 5.2; 35 3.7; 37 2.5; 40 1.0; 42 0.1; 45 -0.9; 49 -1.4; 52 -1.4; 56 -1.1; 59 -0.9; 64 -0.1; 68 0.6; 73 1.1; 78 1.3; 83 1.4; 89 1.4; 95 1.4; 102 1.4; 109 1.4; 117 1.3; 125 1.1; 134 1.1; 143 1.0; 153 0.9; 164 1.0; 175 1.0; 188 1.1; 201 1.1; 215 1.2; 230 1.3; 246 1.3; 263 1.4; 282 1.4; 301 1.4; 323 1.4; 345 1.5; 369 1.4; 395 1.5; 423 1.7; 452 1.8; 484 1.8; 518 1.7; 554 1.6; 593 1.7; 635 1.6; 679 1.3; 726 1.2; 777 1.2; 832 1.0; 890 0.7; 952 0.4; 1019 -0.1; 1090 -0.3; 1167 -0.8; 1248 -1.5; 1336 -2.4; 1429 -3.3; 1529 -3.8; 1636 -4.0; 1751 -4.4; 1873 -4.2; 2004 -2.6; 2145 -0.4; 2295 2.1; 2455 4.0; 2627 3.5; 2811 1.6; 3008 1.3; 3219 0.8; 3444 0.9; 3685 0.4; 3943 0.0; 4219 -0.6; 4514 -0.3; 4830 0.4; 5168 1.6; 5530 2.8; 5917 2.3; 6331 0.4; 6775 -0.8; 7249 -0.3; 7756 -0.1; 8299 -1.8; 8880 -3.5; 9502 -2.9; 10167 -0.4; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 -0.0; 18692 -1.8; 20000 -3.3
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 5.9; 32 5.2; 35 3.7; 37 2.5; 40 1.0; 42 0.1; 45 -0.9; 49 -1.4; 52 -1.4; 56 -1.1; 59 -0.9; 64 -0.1; 68 0.6; 73 1.1; 78 1.3; 83 1.4; 89 1.4; 95 1.4; 102 1.4; 109 1.4; 117 1.3; 125 1.1; 134 1.1; 143 1.0; 153 0.9; 164 1.0; 175 1.0; 188 1.1; 201 1.1; 215 1.2; 230 1.3; 246 1.3; 263 1.4; 282 1.4; 301 1.4; 323 1.4; 345 1.5; 369 1.4; 395 1.5; 423 1.7; 452 1.8; 484 1.8; 518 1.7; 554 1.6; 593 1.7; 635 1.6; 679 1.3; 726 1.2; 777 1.2; 832 1.0; 890 0.7; 952 0.4; 1019 -0.1; 1090 -0.3; 1167 -0.8; 1248 -1.5; 1336 -2.4; 1429 -3.3; 1529 -3.8; 1636 -4.0; 1751 -4.4; 1873 -4.2; 2004 -2.6; 2145 -0.4; 2295 2.1; 2455 4.0; 2627 3.5; 2811 1.6; 3008 1.3; 3219 0.8; 3444 0.9; 3685 0.4; 3943 0.0; 4219 -0.6; 4514 -0.3; 4830 0.4; 5168 1.6; 5530 2.8; 5917 2.3; 6331 0.4; 6775 -0.8; 7249 -0.3; 7756 -0.1; 8299 -1.8; 8880 -3.5; 9502 -2.9; 10167 -0.4; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 -0.0; 18692 -1.8; 20000 -3.3
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/Stax%20SR-Lambda%20Signature/Stax%20SR-Lambda%20Signature.png)