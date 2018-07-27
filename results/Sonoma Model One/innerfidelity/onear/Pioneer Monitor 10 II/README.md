# Pioneer Monitor 10 II
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -1.8; 22 -1.8; 23 -1.8; 25 -1.9; 26 -1.9; 28 -1.9; 30 -1.9; 32 -1.9; 35 -1.9; 37 -2.0; 40 -2.1; 42 -2.1; 45 -2.3; 49 -2.6; 52 -2.8; 56 -2.9; 59 -2.8; 64 -2.5; 68 -2.0; 73 -1.4; 78 -1.0; 83 -0.9; 89 -1.3; 95 -1.8; 102 -2.7; 109 -3.4; 117 -3.7; 125 -3.3; 134 -2.9; 143 -3.1; 153 -6.2; 164 -5.9; 175 -3.7; 188 -4.9; 201 -5.9; 215 -6.4; 230 -6.6; 246 -6.9; 263 -7.2; 282 -6.7; 301 -6.2; 323 -6.3; 345 -5.5; 369 -4.8; 395 -4.0; 423 -2.8; 452 -1.7; 484 -0.7; 518 0.3; 554 1.4; 593 2.7; 635 3.9; 679 4.7; 726 5.1; 777 4.3; 832 2.9; 890 1.6; 952 0.3; 1019 0.2; 1090 0.9; 1167 1.0; 1248 0.8; 1336 -0.4; 1429 -2.4; 1529 -4.5; 1636 -6.3; 1751 -7.2; 1873 -5.7; 2004 -3.3; 2145 -1.0; 2295 1.0; 2455 1.3; 2627 0.9; 2811 1.7; 3008 3.9; 3219 4.9; 3444 4.1; 3685 4.2; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 4.0; 5530 5.9; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -1.8; 22 -1.8; 23 -1.8; 25 -1.9; 26 -1.9; 28 -1.9; 30 -1.9; 32 -1.9; 35 -1.9; 37 -2.0; 40 -2.1; 42 -2.1; 45 -2.3; 49 -2.6; 52 -2.8; 56 -2.9; 59 -2.8; 64 -2.5; 68 -2.0; 73 -1.4; 78 -1.0; 83 -0.9; 89 -1.3; 95 -1.8; 102 -2.7; 109 -3.4; 117 -3.7; 125 -3.3; 134 -2.9; 143 -3.1; 153 -6.2; 164 -5.9; 175 -3.7; 188 -4.9; 201 -5.9; 215 -6.4; 230 -6.6; 246 -6.9; 263 -7.2; 282 -6.7; 301 -6.2; 323 -6.3; 345 -5.5; 369 -4.8; 395 -4.0; 423 -2.8; 452 -1.7; 484 -0.7; 518 0.3; 554 1.4; 593 2.7; 635 3.9; 679 4.7; 726 5.1; 777 4.3; 832 2.9; 890 1.6; 952 0.3; 1019 0.2; 1090 0.9; 1167 1.0; 1248 0.8; 1336 -0.4; 1429 -2.4; 1529 -4.5; 1636 -6.3; 1751 -7.2; 1873 -5.7; 2004 -3.3; 2145 -1.0; 2295 1.0; 2455 1.3; 2627 0.9; 2811 1.7; 3008 3.9; 3219 4.9; 3444 4.1; 3685 4.2; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 4.0; 5530 5.9; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Pioneer%20Monitor%2010%20II/Pioneer%20Monitor%2010%20II.png)