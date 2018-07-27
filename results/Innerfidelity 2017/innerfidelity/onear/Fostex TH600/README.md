# Fostex TH600
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -3.9; 22 -4.3; 23 -4.4; 25 -4.6; 26 -4.8; 28 -5.0; 30 -5.1; 32 -5.2; 35 -5.4; 37 -5.5; 40 -5.6; 42 -5.6; 45 -5.6; 49 -5.5; 52 -5.4; 56 -5.1; 59 -4.9; 64 -5.0; 68 -5.2; 73 -5.3; 78 -5.5; 83 -5.6; 89 -5.6; 95 -5.8; 102 -6.0; 109 -6.1; 117 -6.2; 125 -6.4; 134 -6.6; 143 -6.6; 153 -6.6; 164 -6.2; 175 -5.8; 188 -5.7; 201 -5.5; 215 -5.1; 230 -4.7; 246 -4.4; 263 -4.1; 282 -3.6; 301 -3.2; 323 -2.6; 345 -2.0; 369 -1.2; 395 -0.4; 423 0.6; 452 1.3; 484 1.7; 518 1.7; 554 1.9; 593 1.8; 635 1.3; 679 0.6; 726 0.0; 777 0.4; 832 1.2; 890 0.4; 952 -0.0; 1019 0.0; 1090 0.1; 1167 0.3; 1248 0.5; 1336 0.6; 1429 0.8; 1529 1.0; 1636 1.0; 1751 0.9; 1873 0.8; 2004 1.0; 2145 1.4; 2295 3.1; 2455 5.0; 2627 4.3; 2811 4.3; 3008 5.9; 3219 6.0; 3444 5.6; 3685 5.9; 3943 6.0; 4219 5.5; 4514 4.0; 4830 1.9; 5168 1.0; 5530 -0.5; 5917 -2.3; 6331 -2.4; 6775 -2.7; 7249 -2.5; 7756 -0.8; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 -2.3; 20000 -4.5
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -3.9; 22 -4.3; 23 -4.4; 25 -4.6; 26 -4.8; 28 -5.0; 30 -5.1; 32 -5.2; 35 -5.4; 37 -5.5; 40 -5.6; 42 -5.6; 45 -5.6; 49 -5.5; 52 -5.4; 56 -5.1; 59 -4.9; 64 -5.0; 68 -5.2; 73 -5.3; 78 -5.5; 83 -5.6; 89 -5.6; 95 -5.8; 102 -6.0; 109 -6.1; 117 -6.2; 125 -6.4; 134 -6.6; 143 -6.6; 153 -6.6; 164 -6.2; 175 -5.8; 188 -5.7; 201 -5.5; 215 -5.1; 230 -4.7; 246 -4.4; 263 -4.1; 282 -3.6; 301 -3.2; 323 -2.6; 345 -2.0; 369 -1.2; 395 -0.4; 423 0.6; 452 1.3; 484 1.7; 518 1.7; 554 1.9; 593 1.8; 635 1.3; 679 0.6; 726 0.0; 777 0.4; 832 1.2; 890 0.4; 952 -0.0; 1019 0.0; 1090 0.1; 1167 0.3; 1248 0.5; 1336 0.6; 1429 0.8; 1529 1.0; 1636 1.0; 1751 0.9; 1873 0.8; 2004 1.0; 2145 1.4; 2295 3.1; 2455 5.0; 2627 4.3; 2811 4.3; 3008 5.9; 3219 6.0; 3444 5.6; 3685 5.9; 3943 6.0; 4219 5.5; 4514 4.0; 4830 1.9; 5168 1.0; 5530 -0.5; 5917 -2.3; 6331 -2.4; 6775 -2.7; 7249 -2.5; 7756 -0.8; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 -2.3; 20000 -4.5
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Fostex%20TH600/Fostex%20TH600.png)