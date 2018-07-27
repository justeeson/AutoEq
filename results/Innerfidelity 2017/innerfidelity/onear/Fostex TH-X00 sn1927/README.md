# Fostex TH-X00 sn1927
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -1.3; 22 -1.6; 23 -1.8; 25 -2.0; 26 -2.1; 28 -2.2; 30 -2.3; 32 -2.3; 35 -2.2; 37 -2.2; 40 -2.2; 42 -2.1; 45 -2.1; 49 -2.0; 52 -1.9; 56 -1.8; 59 -1.6; 64 -1.4; 68 -1.4; 73 -1.4; 78 -1.5; 83 -1.7; 89 -1.9; 95 -2.0; 102 -2.4; 109 -2.6; 117 -2.8; 125 -3.2; 134 -3.5; 143 -3.6; 153 -3.7; 164 -3.6; 175 -3.5; 188 -3.5; 201 -3.4; 215 -3.2; 230 -2.9; 246 -2.7; 263 -2.5; 282 -2.3; 301 -2.2; 323 -2.1; 345 -1.9; 369 -1.7; 395 -1.6; 423 -1.4; 452 -1.3; 484 -1.5; 518 -1.4; 554 -1.0; 593 -0.5; 635 -0.5; 679 -0.7; 726 -0.8; 777 0.2; 832 0.6; 890 0.2; 952 -0.0; 1019 -0.1; 1090 -0.1; 1167 -0.1; 1248 -0.1; 1336 -0.2; 1429 -0.3; 1529 -0.5; 1636 -0.6; 1751 -0.5; 1873 -0.4; 2004 -0.0; 2145 0.4; 2295 0.8; 2455 1.7; 2627 2.6; 2811 3.4; 3008 5.3; 3219 5.4; 3444 5.6; 3685 5.5; 3943 6.0; 4219 6.0; 4514 6.0; 4830 5.8; 5168 3.7; 5530 2.4; 5917 2.0; 6331 1.7; 6775 2.0; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 -0.0; 10167 -0.6; 10879 -0.4; 11640 -0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -1.3; 22 -1.6; 23 -1.8; 25 -2.0; 26 -2.1; 28 -2.2; 30 -2.3; 32 -2.3; 35 -2.2; 37 -2.2; 40 -2.2; 42 -2.1; 45 -2.1; 49 -2.0; 52 -1.9; 56 -1.8; 59 -1.6; 64 -1.4; 68 -1.4; 73 -1.4; 78 -1.5; 83 -1.7; 89 -1.9; 95 -2.0; 102 -2.4; 109 -2.6; 117 -2.8; 125 -3.2; 134 -3.5; 143 -3.6; 153 -3.7; 164 -3.6; 175 -3.5; 188 -3.5; 201 -3.4; 215 -3.2; 230 -2.9; 246 -2.7; 263 -2.5; 282 -2.3; 301 -2.2; 323 -2.1; 345 -1.9; 369 -1.7; 395 -1.6; 423 -1.4; 452 -1.3; 484 -1.5; 518 -1.4; 554 -1.0; 593 -0.5; 635 -0.5; 679 -0.7; 726 -0.8; 777 0.2; 832 0.6; 890 0.2; 952 -0.0; 1019 -0.1; 1090 -0.1; 1167 -0.1; 1248 -0.1; 1336 -0.2; 1429 -0.3; 1529 -0.5; 1636 -0.6; 1751 -0.5; 1873 -0.4; 2004 -0.0; 2145 0.4; 2295 0.8; 2455 1.7; 2627 2.6; 2811 3.4; 3008 5.3; 3219 5.4; 3444 5.6; 3685 5.5; 3943 6.0; 4219 6.0; 4514 6.0; 4830 5.8; 5168 3.7; 5530 2.4; 5917 2.0; 6331 1.7; 6775 2.0; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 -0.0; 10167 -0.6; 10879 -0.4; 11640 -0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Fostex%20TH-X00%20sn1927/Fostex%20TH-X00%20sn1927.png)