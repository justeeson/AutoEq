# Ultrasone PROline 650
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 0.5; 22 -0.3; 23 -0.6; 25 -1.1; 26 -1.3; 28 -1.7; 30 -2.0; 32 -2.2; 35 -2.6; 37 -2.8; 40 -2.9; 42 -2.8; 45 -2.2; 49 -0.5; 52 0.6; 56 0.2; 59 -0.9; 64 -2.3; 68 -3.1; 73 -3.7; 78 -3.8; 83 -3.4; 89 -3.0; 95 -3.2; 102 -3.5; 109 -3.7; 117 -3.0; 125 -2.8; 134 -3.5; 143 -3.4; 153 -3.1; 164 -2.2; 175 -1.9; 188 -1.4; 201 -0.7; 215 0.3; 230 0.9; 246 1.8; 263 2.8; 282 3.3; 301 3.5; 323 3.1; 345 2.8; 369 2.2; 395 1.5; 423 1.2; 452 1.0; 484 1.7; 518 5.2; 554 4.2; 593 2.2; 635 1.5; 679 1.2; 726 1.6; 777 1.2; 832 0.8; 890 0.6; 952 0.3; 1019 -0.0; 1090 -0.1; 1167 0.1; 1248 0.5; 1336 0.8; 1429 1.1; 1529 0.8; 1636 0.4; 1751 0.0; 1873 0.4; 2004 1.4; 2145 3.7; 2295 6.0; 2455 5.8; 2627 2.6; 2811 1.1; 3008 1.3; 3219 0.6; 3444 -1.2; 3685 -1.8; 3943 -1.3; 4219 0.1; 4514 2.7; 4830 5.2; 5168 4.5; 5530 5.9; 5917 5.9; 6331 2.4; 6775 -0.7; 7249 1.2; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 -0.6; 16326 -0.1; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 0.5; 22 -0.3; 23 -0.6; 25 -1.1; 26 -1.3; 28 -1.7; 30 -2.0; 32 -2.2; 35 -2.6; 37 -2.8; 40 -2.9; 42 -2.8; 45 -2.2; 49 -0.5; 52 0.6; 56 0.2; 59 -0.9; 64 -2.3; 68 -3.1; 73 -3.7; 78 -3.8; 83 -3.4; 89 -3.0; 95 -3.2; 102 -3.5; 109 -3.7; 117 -3.0; 125 -2.8; 134 -3.5; 143 -3.4; 153 -3.1; 164 -2.2; 175 -1.9; 188 -1.4; 201 -0.7; 215 0.3; 230 0.9; 246 1.8; 263 2.8; 282 3.3; 301 3.5; 323 3.1; 345 2.8; 369 2.2; 395 1.5; 423 1.2; 452 1.0; 484 1.7; 518 5.2; 554 4.2; 593 2.2; 635 1.5; 679 1.2; 726 1.6; 777 1.2; 832 0.8; 890 0.6; 952 0.3; 1019 -0.0; 1090 -0.1; 1167 0.1; 1248 0.5; 1336 0.8; 1429 1.1; 1529 0.8; 1636 0.4; 1751 0.0; 1873 0.4; 2004 1.4; 2145 3.7; 2295 6.0; 2455 5.8; 2627 2.6; 2811 1.1; 3008 1.3; 3219 0.6; 3444 -1.2; 3685 -1.8; 3943 -1.3; 4219 0.1; 4514 2.7; 4830 5.2; 5168 4.5; 5530 5.9; 5917 5.9; 6331 2.4; 6775 -0.7; 7249 1.2; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 -0.6; 16326 -0.1; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/headphoncecom/onear/Ultrasone%20PROline%20650/Ultrasone%20PROline%20650.png)