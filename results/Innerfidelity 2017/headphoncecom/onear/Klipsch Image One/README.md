# Klipsch Image One
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-61**.
```
GraphicEQ: 10 -84; 20 6.1; 22 5.1; 23 4.7; 25 3.9; 26 3.5; 28 2.9; 30 2.3; 32 1.8; 35 1.2; 37 0.8; 40 0.2; 42 -0.1; 45 -0.5; 49 -1.0; 52 -1.4; 56 -1.7; 59 -1.9; 64 -2.1; 68 -2.2; 73 -2.4; 78 -2.7; 83 -3.0; 89 -3.3; 95 -3.7; 102 -4.1; 109 -4.4; 117 -4.9; 125 -5.2; 134 -5.5; 143 -5.7; 153 -5.9; 164 -6.0; 175 -5.9; 188 -6.2; 201 -6.1; 215 -5.6; 230 -5.4; 246 -5.2; 263 -5.0; 282 -4.9; 301 -4.9; 323 -4.8; 345 -4.5; 369 -4.2; 395 -4.1; 423 -4.0; 452 -4.1; 484 -3.9; 518 -3.3; 554 -2.2; 593 -1.0; 635 -0.0; 679 0.5; 726 0.6; 777 0.6; 832 0.2; 890 -0.3; 952 -0.6; 1019 0.2; 1090 -0.7; 1167 -1.6; 1248 -2.1; 1336 -2.6; 1429 -2.7; 1529 -2.8; 1636 -3.3; 1751 -4.0; 1873 -4.6; 2004 -5.0; 2145 -5.3; 2295 -5.6; 2455 -5.8; 2627 -6.6; 2811 -6.7; 3008 -5.8; 3219 -4.7; 3444 -3.2; 3685 -0.3; 3943 3.2; 4219 5.0; 4514 5.6; 4830 4.6; 5168 3.5; 5530 0.8; 5917 1.1; 6331 0.3; 6775 -2.0; 7249 -0.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.1; 22 5.1; 23 4.7; 25 3.9; 26 3.5; 28 2.9; 30 2.3; 32 1.8; 35 1.2; 37 0.8; 40 0.2; 42 -0.1; 45 -0.5; 49 -1.0; 52 -1.4; 56 -1.7; 59 -1.9; 64 -2.1; 68 -2.2; 73 -2.4; 78 -2.7; 83 -3.0; 89 -3.3; 95 -3.7; 102 -4.1; 109 -4.4; 117 -4.9; 125 -5.2; 134 -5.5; 143 -5.7; 153 -5.9; 164 -6.0; 175 -5.9; 188 -6.2; 201 -6.1; 215 -5.6; 230 -5.4; 246 -5.2; 263 -5.0; 282 -4.9; 301 -4.9; 323 -4.8; 345 -4.5; 369 -4.2; 395 -4.1; 423 -4.0; 452 -4.1; 484 -3.9; 518 -3.3; 554 -2.2; 593 -1.0; 635 -0.0; 679 0.5; 726 0.6; 777 0.6; 832 0.2; 890 -0.3; 952 -0.6; 1019 0.2; 1090 -0.7; 1167 -1.6; 1248 -2.1; 1336 -2.6; 1429 -2.7; 1529 -2.8; 1636 -3.3; 1751 -4.0; 1873 -4.6; 2004 -5.0; 2145 -5.3; 2295 -5.6; 2455 -5.8; 2627 -6.6; 2811 -6.7; 3008 -5.8; 3219 -4.7; 3444 -3.2; 3685 -0.3; 3943 3.2; 4219 5.0; 4514 5.6; 4830 4.6; 5168 3.5; 5530 0.8; 5917 1.1; 6331 0.3; 6775 -2.0; 7249 -0.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.1dB*l, R=-6.1dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/headphoncecom/onear/Klipsch%20Image%20One/Klipsch%20Image%20One.png)