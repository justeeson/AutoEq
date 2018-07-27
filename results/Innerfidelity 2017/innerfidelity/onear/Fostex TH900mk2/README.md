# Fostex TH900mk2
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-42**.
```
GraphicEQ: 10 -84; 20 -3.5; 22 -3.8; 23 -3.9; 25 -4.1; 26 -4.2; 28 -4.4; 30 -4.5; 32 -4.7; 35 -4.8; 37 -4.9; 40 -4.9; 42 -4.9; 45 -4.9; 49 -4.8; 52 -4.8; 56 -4.7; 59 -4.7; 64 -4.4; 68 -4.2; 73 -4.2; 78 -4.3; 83 -4.4; 89 -4.6; 95 -4.8; 102 -5.0; 109 -5.1; 117 -5.2; 125 -5.5; 134 -5.6; 143 -5.6; 153 -5.5; 164 -5.1; 175 -4.9; 188 -4.8; 201 -4.6; 215 -4.3; 230 -3.9; 246 -3.8; 263 -3.4; 282 -3.1; 301 -2.7; 323 -2.2; 345 -1.7; 369 -1.2; 395 -0.7; 423 -0.2; 452 0.1; 484 0.1; 518 0.1; 554 0.4; 593 0.6; 635 0.4; 679 -0.2; 726 -0.5; 777 0.5; 832 0.6; 890 0.0; 952 -0.1; 1019 0.0; 1090 0.3; 1167 0.6; 1248 0.9; 1336 1.3; 1429 1.6; 1529 1.8; 1636 1.8; 1751 1.6; 1873 1.6; 2004 1.5; 2145 1.6; 2295 2.0; 2455 3.1; 2627 3.6; 2811 3.1; 3008 2.1; 3219 0.9; 3444 1.9; 3685 3.2; 3943 4.2; 4219 4.1; 4514 3.4; 4830 1.9; 5168 -0.4; 5530 -4.0; 5917 -5.8; 6331 -3.6; 6775 -2.0; 7249 -3.2; 7756 -4.5; 8299 -3.1; 8880 -0.2; 9502 0.0; 10167 0.0; 10879 -0.5; 11640 -1.4; 12455 -0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 -0.3; 18692 -2.9; 20000 -5.6
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -3.5; 22 -3.8; 23 -3.9; 25 -4.1; 26 -4.2; 28 -4.4; 30 -4.5; 32 -4.7; 35 -4.8; 37 -4.9; 40 -4.9; 42 -4.9; 45 -4.9; 49 -4.8; 52 -4.8; 56 -4.7; 59 -4.7; 64 -4.4; 68 -4.2; 73 -4.2; 78 -4.3; 83 -4.4; 89 -4.6; 95 -4.8; 102 -5.0; 109 -5.1; 117 -5.2; 125 -5.5; 134 -5.6; 143 -5.6; 153 -5.5; 164 -5.1; 175 -4.9; 188 -4.8; 201 -4.6; 215 -4.3; 230 -3.9; 246 -3.8; 263 -3.4; 282 -3.1; 301 -2.7; 323 -2.2; 345 -1.7; 369 -1.2; 395 -0.7; 423 -0.2; 452 0.1; 484 0.1; 518 0.1; 554 0.4; 593 0.6; 635 0.4; 679 -0.2; 726 -0.5; 777 0.5; 832 0.6; 890 0.0; 952 -0.1; 1019 0.0; 1090 0.3; 1167 0.6; 1248 0.9; 1336 1.3; 1429 1.6; 1529 1.8; 1636 1.8; 1751 1.6; 1873 1.6; 2004 1.5; 2145 1.6; 2295 2.0; 2455 3.1; 2627 3.6; 2811 3.1; 3008 2.1; 3219 0.9; 3444 1.9; 3685 3.2; 3943 4.2; 4219 4.1; 4514 3.4; 4830 1.9; 5168 -0.4; 5530 -4.0; 5917 -5.8; 6331 -3.6; 6775 -2.0; 7249 -3.2; 7756 -4.5; 8299 -3.1; 8880 -0.2; 9502 0.0; 10167 0.0; 10879 -0.5; 11640 -1.4; 12455 -0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 -0.3; 18692 -2.9; 20000 -5.6
Copy: L=-4.2dB*l, R=-4.2dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Fostex%20TH900mk2/Fostex%20TH900mk2.png)