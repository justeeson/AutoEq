# Audio Technica ATH-ANC7B
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 5.8; 26 5.3; 28 3.9; 30 2.3; 32 0.6; 35 -1.6; 37 -2.8; 40 -4.3; 42 -5.0; 45 -5.7; 49 -5.8; 52 -5.5; 56 -4.8; 59 -4.3; 64 -3.7; 68 -3.4; 73 -3.1; 78 -3.0; 83 -2.9; 89 -2.9; 95 -3.1; 102 -3.2; 109 -3.4; 117 -3.6; 125 -3.8; 134 -3.9; 143 -4.0; 153 -4.1; 164 -4.0; 175 -3.9; 188 -3.8; 201 -3.6; 215 -3.4; 230 -3.2; 246 -3.0; 263 -2.8; 282 -2.5; 301 -2.5; 323 -2.1; 345 -2.0; 369 -2.0; 395 -1.9; 423 -1.9; 452 -2.1; 484 -2.3; 518 -2.6; 554 -3.0; 593 -3.5; 635 -4.1; 679 -4.5; 726 -4.2; 777 -3.5; 832 -2.3; 890 -0.9; 952 -0.1; 1019 -0.2; 1090 -1.6; 1167 -1.7; 1248 -0.5; 1336 0.1; 1429 2.2; 1529 3.7; 1636 5.1; 1751 3.4; 1873 2.6; 2004 3.5; 2145 3.8; 2295 5.2; 2455 5.9; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 5.9; 3685 5.4; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 5.0; 5530 5.2; 5917 5.3; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 5.8; 26 5.3; 28 3.9; 30 2.3; 32 0.6; 35 -1.6; 37 -2.8; 40 -4.3; 42 -5.0; 45 -5.7; 49 -5.8; 52 -5.5; 56 -4.8; 59 -4.3; 64 -3.7; 68 -3.4; 73 -3.1; 78 -3.0; 83 -2.9; 89 -2.9; 95 -3.1; 102 -3.2; 109 -3.4; 117 -3.6; 125 -3.8; 134 -3.9; 143 -4.0; 153 -4.1; 164 -4.0; 175 -3.9; 188 -3.8; 201 -3.6; 215 -3.4; 230 -3.2; 246 -3.0; 263 -2.8; 282 -2.5; 301 -2.5; 323 -2.1; 345 -2.0; 369 -2.0; 395 -1.9; 423 -1.9; 452 -2.1; 484 -2.3; 518 -2.6; 554 -3.0; 593 -3.5; 635 -4.1; 679 -4.5; 726 -4.2; 777 -3.5; 832 -2.3; 890 -0.9; 952 -0.1; 1019 -0.2; 1090 -1.6; 1167 -1.7; 1248 -0.5; 1336 0.1; 1429 2.2; 1529 3.7; 1636 5.1; 1751 3.4; 1873 2.6; 2004 3.5; 2145 3.8; 2295 5.2; 2455 5.9; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 5.9; 3685 5.4; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 5.0; 5530 5.2; 5917 5.3; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/headphoncecom/onear/Audio%20Technica%20ATH-ANC7B/Audio%20Technica%20ATH-ANC7B.png)