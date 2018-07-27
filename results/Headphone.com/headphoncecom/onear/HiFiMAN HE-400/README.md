# HiFiMAN HE-400
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 5.5; 22 5.5; 23 5.5; 25 5.5; 26 5.5; 28 5.5; 30 5.5; 32 5.5; 35 5.5; 37 5.5; 40 5.5; 42 5.6; 45 5.7; 49 5.7; 52 5.7; 56 5.7; 59 5.7; 64 5.6; 68 5.6; 73 5.6; 78 5.4; 83 5.2; 89 5.0; 95 4.5; 102 4.0; 109 3.6; 117 3.2; 125 2.7; 134 2.4; 143 2.1; 153 1.8; 164 1.5; 175 1.6; 188 3.2; 201 3.4; 215 2.7; 230 2.3; 246 2.1; 263 1.9; 282 2.1; 301 2.1; 323 2.0; 345 1.6; 369 1.0; 395 1.3; 423 2.9; 452 5.3; 484 4.9; 518 4.8; 554 4.0; 593 3.4; 635 3.2; 679 2.8; 726 1.9; 777 1.3; 832 0.8; 890 1.3; 952 0.8; 1019 0.3; 1090 1.0; 1167 2.2; 1248 3.0; 1336 4.9; 1429 6.0; 1529 6.0; 1636 6.0; 1751 6.0; 1873 6.0; 2004 6.0; 2145 6.0; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.6; 9502 -0.1; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 5.5; 22 5.5; 23 5.5; 25 5.5; 26 5.5; 28 5.5; 30 5.5; 32 5.5; 35 5.5; 37 5.5; 40 5.5; 42 5.6; 45 5.7; 49 5.7; 52 5.7; 56 5.7; 59 5.7; 64 5.6; 68 5.6; 73 5.6; 78 5.4; 83 5.2; 89 5.0; 95 4.5; 102 4.0; 109 3.6; 117 3.2; 125 2.7; 134 2.4; 143 2.1; 153 1.8; 164 1.5; 175 1.6; 188 3.2; 201 3.4; 215 2.7; 230 2.3; 246 2.1; 263 1.9; 282 2.1; 301 2.1; 323 2.0; 345 1.6; 369 1.0; 395 1.3; 423 2.9; 452 5.3; 484 4.9; 518 4.8; 554 4.0; 593 3.4; 635 3.2; 679 2.8; 726 1.9; 777 1.3; 832 0.8; 890 1.3; 952 0.8; 1019 0.3; 1090 1.0; 1167 2.2; 1248 3.0; 1336 4.9; 1429 6.0; 1529 6.0; 1636 6.0; 1751 6.0; 1873 6.0; 2004 6.0; 2145 6.0; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.6; 9502 -0.1; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/headphoncecom/onear/HiFiMAN%20HE-400/HiFiMAN%20HE-400.png)