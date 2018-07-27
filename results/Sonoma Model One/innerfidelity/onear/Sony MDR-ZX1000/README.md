# Sony MDR-ZX1000
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 5.5; 95 4.6; 102 3.8; 109 3.1; 117 2.2; 125 1.2; 134 0.4; 143 -0.2; 153 -0.4; 164 0.0; 175 0.5; 188 0.6; 201 0.8; 215 1.0; 230 1.2; 246 1.3; 263 1.1; 282 1.1; 301 0.8; 323 0.2; 345 -0.3; 369 -0.8; 395 -1.1; 423 -1.1; 452 -0.9; 484 -0.9; 518 -0.9; 554 -0.8; 593 -0.4; 635 0.2; 679 0.7; 726 0.8; 777 1.0; 832 1.0; 890 0.6; 952 0.1; 1019 0.0; 1090 0.3; 1167 0.9; 1248 1.3; 1336 1.2; 1429 0.7; 1529 -0.1; 1636 -1.4; 1751 -2.9; 1873 -3.6; 2004 -3.6; 2145 -3.3; 2295 -2.5; 2455 -1.6; 2627 -0.5; 2811 0.5; 3008 1.6; 3219 2.6; 3444 4.4; 3685 5.7; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 3.5; 5917 2.9; 6331 4.9; 6775 3.9; 7249 1.3; 7756 -1.4; 8299 -5.4; 8880 -8.0; 9502 -8.8; 10167 -6.9; 10879 -1.7; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 5.5; 95 4.6; 102 3.8; 109 3.1; 117 2.2; 125 1.2; 134 0.4; 143 -0.2; 153 -0.4; 164 0.0; 175 0.5; 188 0.6; 201 0.8; 215 1.0; 230 1.2; 246 1.3; 263 1.1; 282 1.1; 301 0.8; 323 0.2; 345 -0.3; 369 -0.8; 395 -1.1; 423 -1.1; 452 -0.9; 484 -0.9; 518 -0.9; 554 -0.8; 593 -0.4; 635 0.2; 679 0.7; 726 0.8; 777 1.0; 832 1.0; 890 0.6; 952 0.1; 1019 0.0; 1090 0.3; 1167 0.9; 1248 1.3; 1336 1.2; 1429 0.7; 1529 -0.1; 1636 -1.4; 1751 -2.9; 1873 -3.6; 2004 -3.6; 2145 -3.3; 2295 -2.5; 2455 -1.6; 2627 -0.5; 2811 0.5; 3008 1.6; 3219 2.6; 3444 4.4; 3685 5.7; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 3.5; 5917 2.9; 6331 4.9; 6775 3.9; 7249 1.3; 7756 -1.4; 8299 -5.4; 8880 -8.0; 9502 -8.8; 10167 -6.9; 10879 -1.7; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Sony%20MDR-ZX1000/Sony%20MDR-ZX1000.png)