# Audio Technica ATH-AD900
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 5.8; 78 5.9; 83 6.0; 89 5.9; 95 4.9; 102 4.1; 109 3.8; 117 3.4; 125 2.6; 134 2.0; 143 1.6; 153 1.3; 164 1.2; 175 0.9; 188 0.8; 201 0.8; 215 0.8; 230 0.7; 246 0.6; 263 0.5; 282 0.7; 301 0.8; 323 0.9; 345 1.0; 369 0.9; 395 1.0; 423 0.9; 452 0.9; 484 0.7; 518 0.7; 554 0.8; 593 0.9; 635 0.9; 679 0.7; 726 0.9; 777 0.9; 832 0.4; 890 0.3; 952 0.3; 1019 0.0; 1090 -0.1; 1167 -0.3; 1248 -0.8; 1336 -1.4; 1429 -2.6; 1529 -4.0; 1636 -4.2; 1751 -2.7; 1873 -1.8; 2004 -0.7; 2145 0.8; 2295 0.9; 2455 2.4; 2627 1.7; 2811 1.0; 3008 0.9; 3219 1.7; 3444 0.1; 3685 -3.2; 3943 -4.5; 4219 -5.7; 4514 -5.6; 4830 -3.4; 5168 -1.0; 5530 1.6; 5917 2.3; 6331 2.6; 6775 3.2; 7249 1.3; 7756 0.3; 8299 -0.2; 8880 -2.2; 9502 -3.0; 10167 -1.3; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 -0.9
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 5.8; 78 5.9; 83 6.0; 89 5.9; 95 4.9; 102 4.1; 109 3.8; 117 3.4; 125 2.6; 134 2.0; 143 1.6; 153 1.3; 164 1.2; 175 0.9; 188 0.8; 201 0.8; 215 0.8; 230 0.7; 246 0.6; 263 0.5; 282 0.7; 301 0.8; 323 0.9; 345 1.0; 369 0.9; 395 1.0; 423 0.9; 452 0.9; 484 0.7; 518 0.7; 554 0.8; 593 0.9; 635 0.9; 679 0.7; 726 0.9; 777 0.9; 832 0.4; 890 0.3; 952 0.3; 1019 0.0; 1090 -0.1; 1167 -0.3; 1248 -0.8; 1336 -1.4; 1429 -2.6; 1529 -4.0; 1636 -4.2; 1751 -2.7; 1873 -1.8; 2004 -0.7; 2145 0.8; 2295 0.9; 2455 2.4; 2627 1.7; 2811 1.0; 3008 0.9; 3219 1.7; 3444 0.1; 3685 -3.2; 3943 -4.5; 4219 -5.7; 4514 -5.6; 4830 -3.4; 5168 -1.0; 5530 1.6; 5917 2.3; 6331 2.6; 6775 3.2; 7249 1.3; 7756 0.3; 8299 -0.2; 8880 -2.2; 9502 -3.0; 10167 -1.3; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 -0.9
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/headphoncecom/onear/Audio%20Technica%20ATH-AD900/Audio%20Technica%20ATH-AD900.png)