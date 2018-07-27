# Sennheiser Momentum M2 OEBT Wired Passive
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -1.4; 22 -1.8; 23 -2.0; 25 -2.3; 26 -2.5; 28 -2.7; 30 -3.0; 32 -3.2; 35 -3.4; 37 -3.6; 40 -3.8; 42 -3.9; 45 -4.2; 49 -4.4; 52 -4.5; 56 -4.7; 59 -4.7; 64 -4.7; 68 -4.4; 73 -4.2; 78 -5.0; 83 -5.7; 89 -5.7; 95 -5.4; 102 -5.0; 109 -5.4; 117 -6.6; 125 -7.5; 134 -8.0; 143 -8.2; 153 -7.9; 164 -7.2; 175 -7.2; 188 -6.7; 201 -5.8; 215 -4.5; 230 -3.2; 246 -1.8; 263 -0.7; 282 0.4; 301 1.0; 323 1.2; 345 1.2; 369 0.7; 395 0.1; 423 0.1; 452 0.3; 484 0.3; 518 0.4; 554 0.6; 593 0.7; 635 0.6; 679 0.6; 726 0.5; 777 0.6; 832 0.4; 890 0.2; 952 0.1; 1019 0.0; 1090 -0.1; 1167 -0.2; 1248 -0.4; 1336 -0.9; 1429 -1.5; 1529 -2.1; 1636 -2.7; 1751 -3.0; 1873 -3.4; 2004 -3.5; 2145 -3.4; 2295 -3.4; 2455 -2.8; 2627 -1.9; 2811 -1.3; 3008 0.0; 3219 1.3; 3444 2.8; 3685 3.9; 3943 5.8; 4219 6.0; 4514 4.8; 4830 1.6; 5168 0.3; 5530 2.2; 5917 3.3; 6331 2.2; 6775 -0.2; 7249 -1.0; 7756 -1.7; 8299 -3.0; 8880 -4.9; 9502 -5.1; 10167 -1.4; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -1.4; 22 -1.8; 23 -2.0; 25 -2.3; 26 -2.5; 28 -2.7; 30 -3.0; 32 -3.2; 35 -3.4; 37 -3.6; 40 -3.8; 42 -3.9; 45 -4.2; 49 -4.4; 52 -4.5; 56 -4.7; 59 -4.7; 64 -4.7; 68 -4.4; 73 -4.2; 78 -5.0; 83 -5.7; 89 -5.7; 95 -5.4; 102 -5.0; 109 -5.4; 117 -6.6; 125 -7.5; 134 -8.0; 143 -8.2; 153 -7.9; 164 -7.2; 175 -7.2; 188 -6.7; 201 -5.8; 215 -4.5; 230 -3.2; 246 -1.8; 263 -0.7; 282 0.4; 301 1.0; 323 1.2; 345 1.2; 369 0.7; 395 0.1; 423 0.1; 452 0.3; 484 0.3; 518 0.4; 554 0.6; 593 0.7; 635 0.6; 679 0.6; 726 0.5; 777 0.6; 832 0.4; 890 0.2; 952 0.1; 1019 0.0; 1090 -0.1; 1167 -0.2; 1248 -0.4; 1336 -0.9; 1429 -1.5; 1529 -2.1; 1636 -2.7; 1751 -3.0; 1873 -3.4; 2004 -3.5; 2145 -3.4; 2295 -3.4; 2455 -2.8; 2627 -1.9; 2811 -1.3; 3008 0.0; 3219 1.3; 3444 2.8; 3685 3.9; 3943 5.8; 4219 6.0; 4514 4.8; 4830 1.6; 5168 0.3; 5530 2.2; 5917 3.3; 6331 2.2; 6775 -0.2; 7249 -1.0; 7756 -1.7; 8299 -3.0; 8880 -4.9; 9502 -5.1; 10167 -1.4; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/Sennheiser%20Momentum%20M2%20OEBT%20Wired%20Passive/Sennheiser%20Momentum%20M2%20OEBT%20Wired%20Passive.png)