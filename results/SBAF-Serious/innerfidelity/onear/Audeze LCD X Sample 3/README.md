# Audeze LCD X Sample 3
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 4.2; 22 4.1; 23 4.0; 25 3.8; 26 3.7; 28 3.5; 30 3.3; 32 3.0; 35 2.2; 37 1.4; 40 0.4; 42 0.1; 45 0.1; 49 0.3; 52 0.5; 56 0.8; 59 0.9; 64 1.0; 68 1.0; 73 0.9; 78 0.9; 83 0.8; 89 0.5; 95 0.2; 102 -0.1; 109 -0.4; 117 -0.8; 125 -1.2; 134 -1.5; 143 -1.8; 153 -1.9; 164 -2.0; 175 -2.1; 188 -2.2; 201 -2.3; 215 -2.3; 230 -2.2; 246 -2.3; 263 -2.3; 282 -2.1; 301 -2.0; 323 -1.9; 345 -1.7; 369 -1.5; 395 -1.3; 423 -1.1; 452 -1.3; 484 -1.6; 518 -1.6; 554 -1.2; 593 -0.9; 635 -1.1; 679 -1.3; 726 -1.3; 777 -0.9; 832 -0.8; 890 -0.2; 952 0.1; 1019 0.0; 1090 0.3; 1167 0.2; 1248 0.1; 1336 -0.4; 1429 -0.6; 1529 -0.6; 1636 -0.6; 1751 -0.3; 1873 -0.4; 2004 -0.6; 2145 -0.6; 2295 -0.4; 2455 0.4; 2627 1.8; 2811 3.1; 3008 4.5; 3219 5.3; 3444 5.8; 3685 6.0; 3943 5.6; 4219 3.2; 4514 -0.3; 4830 -0.5; 5168 4.5; 5530 6.0; 5917 5.5; 6331 3.9; 6775 2.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 -0.7; 16326 -2.7; 17469 -4.0; 18692 -5.1; 20000 -6.4
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 4.2; 22 4.1; 23 4.0; 25 3.8; 26 3.7; 28 3.5; 30 3.3; 32 3.0; 35 2.2; 37 1.4; 40 0.4; 42 0.1; 45 0.1; 49 0.3; 52 0.5; 56 0.8; 59 0.9; 64 1.0; 68 1.0; 73 0.9; 78 0.9; 83 0.8; 89 0.5; 95 0.2; 102 -0.1; 109 -0.4; 117 -0.8; 125 -1.2; 134 -1.5; 143 -1.8; 153 -1.9; 164 -2.0; 175 -2.1; 188 -2.2; 201 -2.3; 215 -2.3; 230 -2.2; 246 -2.3; 263 -2.3; 282 -2.1; 301 -2.0; 323 -1.9; 345 -1.7; 369 -1.5; 395 -1.3; 423 -1.1; 452 -1.3; 484 -1.6; 518 -1.6; 554 -1.2; 593 -0.9; 635 -1.1; 679 -1.3; 726 -1.3; 777 -0.9; 832 -0.8; 890 -0.2; 952 0.1; 1019 0.0; 1090 0.3; 1167 0.2; 1248 0.1; 1336 -0.4; 1429 -0.6; 1529 -0.6; 1636 -0.6; 1751 -0.3; 1873 -0.4; 2004 -0.6; 2145 -0.6; 2295 -0.4; 2455 0.4; 2627 1.8; 2811 3.1; 3008 4.5; 3219 5.3; 3444 5.8; 3685 6.0; 3943 5.6; 4219 3.2; 4514 -0.3; 4830 -0.5; 5168 4.5; 5530 6.0; 5917 5.5; 6331 3.9; 6775 2.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 -0.7; 16326 -2.7; 17469 -4.0; 18692 -5.1; 20000 -6.4
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/innerfidelity/onear/Audeze%20LCD%20X%20Sample%203/Audeze%20LCD%20X%20Sample%203.png)