# Audio Technica ATH-M10
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 5.9; 109 4.9; 117 4.0; 125 3.0; 134 2.2; 143 1.5; 153 1.0; 164 1.3; 175 0.6; 188 0.2; 201 0.1; 215 -0.1; 230 -0.4; 246 -0.6; 263 -0.7; 282 -0.9; 301 -1.0; 323 -1.1; 345 -1.1; 369 -1.1; 395 -1.1; 423 -0.9; 452 -0.7; 484 -0.7; 518 -0.8; 554 -0.8; 593 -0.7; 635 -0.4; 679 -0.1; 726 -0.1; 777 -0.2; 832 -0.9; 890 -1.8; 952 -1.9; 1019 0.5; 1090 1.2; 1167 2.3; 1248 1.2; 1336 1.6; 1429 2.3; 1529 3.2; 1636 3.9; 1751 4.2; 1873 4.3; 2004 4.4; 2145 5.0; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 1.1; 6775 1.0; 7249 1.0; 7756 -0.1; 8299 -1.0; 8880 -1.4; 9502 -1.3; 10167 -0.4; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 5.9; 109 4.9; 117 4.0; 125 3.0; 134 2.2; 143 1.5; 153 1.0; 164 1.3; 175 0.6; 188 0.2; 201 0.1; 215 -0.1; 230 -0.4; 246 -0.6; 263 -0.7; 282 -0.9; 301 -1.0; 323 -1.1; 345 -1.1; 369 -1.1; 395 -1.1; 423 -0.9; 452 -0.7; 484 -0.7; 518 -0.8; 554 -0.8; 593 -0.7; 635 -0.4; 679 -0.1; 726 -0.1; 777 -0.2; 832 -0.9; 890 -1.8; 952 -1.9; 1019 0.5; 1090 1.2; 1167 2.3; 1248 1.2; 1336 1.6; 1429 2.3; 1529 3.2; 1636 3.9; 1751 4.2; 1873 4.3; 2004 4.4; 2145 5.0; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 1.1; 6775 1.0; 7249 1.0; 7756 -0.1; 8299 -1.0; 8880 -1.4; 9502 -1.3; 10167 -0.4; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Audio%20Technica%20ATH-M10/Audio%20Technica%20ATH-M10.png)