# AudioTechnica ATH A55
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 6.0; 109 6.0; 117 6.0; 125 6.0; 134 6.0; 143 6.0; 153 6.0; 164 6.0; 175 6.0; 188 6.0; 201 6.0; 215 6.0; 230 5.9; 246 4.0; 263 2.0; 282 0.1; 301 -1.1; 323 -2.2; 345 -2.6; 369 -2.6; 395 -2.2; 423 -1.6; 452 -1.2; 484 -0.7; 518 -0.4; 554 -0.2; 593 0.0; 635 0.3; 679 0.4; 726 0.4; 777 0.3; 832 0.6; 890 0.6; 952 0.2; 1019 -0.1; 1090 -0.2; 1167 -0.2; 1248 0.1; 1336 0.8; 1429 1.5; 1529 2.5; 1636 3.9; 1751 4.3; 1873 4.6; 2004 4.5; 2145 3.8; 2295 3.5; 2455 3.4; 2627 4.5; 2811 5.4; 3008 5.8; 3219 6.0; 3444 6.0; 3685 6.0; 3943 4.0; 4219 0.1; 4514 2.1; 4830 5.7; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.3; 6775 3.8; 7249 0.2; 7756 -1.3; 8299 -1.5; 8880 -0.6; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 6.0; 109 6.0; 117 6.0; 125 6.0; 134 6.0; 143 6.0; 153 6.0; 164 6.0; 175 6.0; 188 6.0; 201 6.0; 215 6.0; 230 5.9; 246 4.0; 263 2.0; 282 0.1; 301 -1.1; 323 -2.2; 345 -2.6; 369 -2.6; 395 -2.2; 423 -1.6; 452 -1.2; 484 -0.7; 518 -0.4; 554 -0.2; 593 0.0; 635 0.3; 679 0.4; 726 0.4; 777 0.3; 832 0.6; 890 0.6; 952 0.2; 1019 -0.1; 1090 -0.2; 1167 -0.2; 1248 0.1; 1336 0.8; 1429 1.5; 1529 2.5; 1636 3.9; 1751 4.3; 1873 4.6; 2004 4.5; 2145 3.8; 2295 3.5; 2455 3.4; 2627 4.5; 2811 5.4; 3008 5.8; 3219 6.0; 3444 6.0; 3685 6.0; 3943 4.0; 4219 0.1; 4514 2.1; 4830 5.7; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.3; 6775 3.8; 7249 0.2; 7756 -1.3; 8299 -1.5; 8880 -0.6; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/headphoncecom/onear/AudioTechnica%20ATH%20A55/AudioTechnica%20ATH%20A55.png)