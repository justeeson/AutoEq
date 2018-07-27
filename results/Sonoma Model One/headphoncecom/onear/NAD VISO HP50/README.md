# NAD VISO HP50
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-43**.
```
GraphicEQ: 10 -84; 20 -4.0; 22 -3.9; 23 -3.8; 25 -3.7; 26 -3.6; 28 -3.6; 30 -3.5; 32 -3.4; 35 -3.3; 37 -3.2; 40 -3.1; 42 -3.1; 45 -3.1; 49 -3.1; 52 -3.1; 56 -3.0; 59 -2.8; 64 -2.3; 68 -1.7; 73 -0.9; 78 -0.4; 83 -0.3; 89 -0.4; 95 -0.7; 102 -1.1; 109 -1.4; 117 -2.4; 125 -4.2; 134 -5.8; 143 -6.3; 153 -5.9; 164 -5.0; 175 -4.8; 188 -5.9; 201 -6.1; 215 -6.0; 230 -5.7; 246 -5.3; 263 -4.9; 282 -4.3; 301 -3.7; 323 -2.9; 345 -2.4; 369 -2.7; 395 -2.3; 423 -1.9; 452 -1.6; 484 -1.4; 518 -1.3; 554 -1.0; 593 -0.5; 635 0.0; 679 0.5; 726 0.8; 777 0.6; 832 0.1; 890 -0.3; 952 -0.3; 1019 -0.1; 1090 0.1; 1167 0.5; 1248 0.2; 1336 -0.2; 1429 -0.5; 1529 -0.8; 1636 -1.1; 1751 -1.5; 1873 -0.8; 2004 -0.7; 2145 0.0; 2295 0.8; 2455 1.9; 2627 2.9; 2811 3.8; 3008 4.2; 3219 3.9; 3444 3.2; 3685 2.1; 3943 1.0; 4219 -1.0; 4514 -2.3; 4830 -2.1; 5168 -0.4; 5530 0.1; 5917 -0.5; 6331 0.7; 6775 1.3; 7249 0.4; 7756 -0.7; 8299 -2.2; 8880 -3.2; 9502 -3.3; 10167 -2.7; 10879 -1.2; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -4.0; 22 -3.9; 23 -3.8; 25 -3.7; 26 -3.6; 28 -3.6; 30 -3.5; 32 -3.4; 35 -3.3; 37 -3.2; 40 -3.1; 42 -3.1; 45 -3.1; 49 -3.1; 52 -3.1; 56 -3.0; 59 -2.8; 64 -2.3; 68 -1.7; 73 -0.9; 78 -0.4; 83 -0.3; 89 -0.4; 95 -0.7; 102 -1.1; 109 -1.4; 117 -2.4; 125 -4.2; 134 -5.8; 143 -6.3; 153 -5.9; 164 -5.0; 175 -4.8; 188 -5.9; 201 -6.1; 215 -6.0; 230 -5.7; 246 -5.3; 263 -4.9; 282 -4.3; 301 -3.7; 323 -2.9; 345 -2.4; 369 -2.7; 395 -2.3; 423 -1.9; 452 -1.6; 484 -1.4; 518 -1.3; 554 -1.0; 593 -0.5; 635 0.0; 679 0.5; 726 0.8; 777 0.6; 832 0.1; 890 -0.3; 952 -0.3; 1019 -0.1; 1090 0.1; 1167 0.5; 1248 0.2; 1336 -0.2; 1429 -0.5; 1529 -0.8; 1636 -1.1; 1751 -1.5; 1873 -0.8; 2004 -0.7; 2145 0.0; 2295 0.8; 2455 1.9; 2627 2.9; 2811 3.8; 3008 4.2; 3219 3.9; 3444 3.2; 3685 2.1; 3943 1.0; 4219 -1.0; 4514 -2.3; 4830 -2.1; 5168 -0.4; 5530 0.1; 5917 -0.5; 6331 0.7; 6775 1.3; 7249 0.4; 7756 -0.7; 8299 -2.2; 8880 -3.2; 9502 -3.3; 10167 -2.7; 10879 -1.2; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-4.3dB*l, R=-4.3dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/headphoncecom/onear/NAD%20VISO%20HP50/NAD%20VISO%20HP50.png)