# Stax SR-007 SZ3-1576
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 5.8; 32 5.2; 35 4.3; 37 3.8; 40 3.3; 42 3.2; 45 3.1; 49 3.4; 52 3.8; 56 4.3; 59 4.4; 64 4.0; 68 3.2; 73 2.3; 78 2.3; 83 2.8; 89 3.0; 95 3.0; 102 2.8; 109 2.7; 117 2.6; 125 2.3; 134 2.1; 143 2.0; 153 1.9; 164 1.8; 175 1.8; 188 1.7; 201 1.6; 215 1.6; 230 1.6; 246 1.5; 263 1.4; 282 1.4; 301 1.2; 323 1.1; 345 1.0; 369 0.9; 395 0.8; 423 0.7; 452 0.4; 484 0.1; 518 1.0; 554 2.8; 593 2.1; 635 1.4; 679 1.0; 726 0.7; 777 0.6; 832 0.2; 890 -0.1; 952 -0.1; 1019 0.2; 1090 0.5; 1167 0.9; 1248 3.2; 1336 5.0; 1429 4.3; 1529 1.2; 1636 0.4; 1751 1.3; 1873 3.1; 2004 4.2; 2145 4.6; 2295 5.9; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.6; 6331 3.7; 6775 3.5; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 5.8; 32 5.2; 35 4.3; 37 3.8; 40 3.3; 42 3.2; 45 3.1; 49 3.4; 52 3.8; 56 4.3; 59 4.4; 64 4.0; 68 3.2; 73 2.3; 78 2.3; 83 2.8; 89 3.0; 95 3.0; 102 2.8; 109 2.7; 117 2.6; 125 2.3; 134 2.1; 143 2.0; 153 1.9; 164 1.8; 175 1.8; 188 1.7; 201 1.6; 215 1.6; 230 1.6; 246 1.5; 263 1.4; 282 1.4; 301 1.2; 323 1.1; 345 1.0; 369 0.9; 395 0.8; 423 0.7; 452 0.4; 484 0.1; 518 1.0; 554 2.8; 593 2.1; 635 1.4; 679 1.0; 726 0.7; 777 0.6; 832 0.2; 890 -0.1; 952 -0.1; 1019 0.2; 1090 0.5; 1167 0.9; 1248 3.2; 1336 5.0; 1429 4.3; 1529 1.2; 1636 0.4; 1751 1.3; 1873 3.1; 2004 4.2; 2145 4.6; 2295 5.9; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.6; 6331 3.7; 6775 3.5; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Stax%20SR-007%20SZ3-1576/Stax%20SR-007%20SZ3-1576.png)