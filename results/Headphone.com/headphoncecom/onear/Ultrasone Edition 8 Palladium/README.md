# Ultrasone Edition 8 Palladium
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 5.9; 37 5.5; 40 4.9; 42 4.5; 45 4.1; 49 3.3; 52 2.5; 56 1.5; 59 1.0; 64 1.4; 68 1.6; 73 0.8; 78 -0.1; 83 -0.7; 89 -1.4; 95 -2.1; 102 -3.0; 109 -3.7; 117 -4.5; 125 -5.0; 134 -5.6; 143 -5.8; 153 -5.2; 164 -5.2; 175 -5.6; 188 -5.4; 201 -5.7; 215 -4.4; 230 -4.8; 246 -5.6; 263 -4.9; 282 -4.0; 301 -3.8; 323 -3.5; 345 -2.8; 369 -2.1; 395 -1.6; 423 -1.2; 452 -0.7; 484 -0.2; 518 0.3; 554 0.6; 593 0.5; 635 -0.4; 679 -0.4; 726 -0.0; 777 0.1; 832 -0.0; 890 -0.2; 952 -0.1; 1019 -0.0; 1090 -0.3; 1167 -0.1; 1248 0.2; 1336 0.8; 1429 1.5; 1529 2.2; 1636 2.7; 1751 3.1; 1873 3.3; 2004 5.4; 2145 6.0; 2295 6.0; 2455 5.6; 2627 2.4; 2811 1.9; 3008 3.0; 3219 3.4; 3444 2.4; 3685 0.0; 3943 -2.6; 4219 0.2; 4514 2.8; 4830 4.8; 5168 6.0; 5530 6.0; 5917 2.8; 6331 -2.0; 6775 -3.4; 7249 -2.4; 7756 -0.7; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 5.9; 37 5.5; 40 4.9; 42 4.5; 45 4.1; 49 3.3; 52 2.5; 56 1.5; 59 1.0; 64 1.4; 68 1.6; 73 0.8; 78 -0.1; 83 -0.7; 89 -1.4; 95 -2.1; 102 -3.0; 109 -3.7; 117 -4.5; 125 -5.0; 134 -5.6; 143 -5.8; 153 -5.2; 164 -5.2; 175 -5.6; 188 -5.4; 201 -5.7; 215 -4.4; 230 -4.8; 246 -5.6; 263 -4.9; 282 -4.0; 301 -3.8; 323 -3.5; 345 -2.8; 369 -2.1; 395 -1.6; 423 -1.2; 452 -0.7; 484 -0.2; 518 0.3; 554 0.6; 593 0.5; 635 -0.4; 679 -0.4; 726 -0.0; 777 0.1; 832 -0.0; 890 -0.2; 952 -0.1; 1019 -0.0; 1090 -0.3; 1167 -0.1; 1248 0.2; 1336 0.8; 1429 1.5; 1529 2.2; 1636 2.7; 1751 3.1; 1873 3.3; 2004 5.4; 2145 6.0; 2295 6.0; 2455 5.6; 2627 2.4; 2811 1.9; 3008 3.0; 3219 3.4; 3444 2.4; 3685 0.0; 3943 -2.6; 4219 0.2; 4514 2.8; 4830 4.8; 5168 6.0; 5530 6.0; 5917 2.8; 6331 -2.0; 6775 -3.4; 7249 -2.4; 7756 -0.7; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/headphoncecom/onear/Ultrasone%20Edition%208%20Palladium/Ultrasone%20Edition%208%20Palladium.png)