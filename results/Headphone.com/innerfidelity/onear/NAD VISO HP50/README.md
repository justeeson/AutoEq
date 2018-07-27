# NAD VISO HP50
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -3.6; 22 -3.7; 23 -3.7; 25 -3.8; 26 -3.8; 28 -3.8; 30 -3.8; 32 -3.8; 35 -3.8; 37 -3.8; 40 -3.7; 42 -3.6; 45 -3.5; 49 -3.3; 52 -3.1; 56 -2.9; 59 -2.8; 64 -2.6; 68 -2.4; 73 -2.3; 78 -2.2; 83 -2.1; 89 -2.2; 95 -2.3; 102 -3.0; 109 -3.5; 117 -3.7; 125 -3.7; 134 -4.3; 143 -5.5; 153 -6.1; 164 -4.6; 175 -4.7; 188 -6.0; 201 -5.9; 215 -5.7; 230 -5.1; 246 -4.7; 263 -4.2; 282 -3.5; 301 -2.8; 323 -2.4; 345 -2.3; 369 -2.1; 395 -1.7; 423 -1.3; 452 -1.0; 484 -0.8; 518 -0.6; 554 -0.4; 593 -0.2; 635 -0.1; 679 0.0; 726 -0.1; 777 -0.2; 832 -0.2; 890 -0.1; 952 -0.0; 1019 -0.1; 1090 -0.2; 1167 -0.4; 1248 -0.8; 1336 -0.7; 1429 -0.2; 1529 -0.0; 1636 0.2; 1751 0.6; 1873 1.0; 2004 1.6; 2145 2.3; 2295 3.1; 2455 4.0; 2627 4.8; 2811 5.2; 3008 4.8; 3219 4.5; 3444 3.9; 3685 3.3; 3943 3.1; 4219 3.9; 4514 4.6; 4830 4.2; 5168 5.9; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -3.6; 22 -3.7; 23 -3.7; 25 -3.8; 26 -3.8; 28 -3.8; 30 -3.8; 32 -3.8; 35 -3.8; 37 -3.8; 40 -3.7; 42 -3.6; 45 -3.5; 49 -3.3; 52 -3.1; 56 -2.9; 59 -2.8; 64 -2.6; 68 -2.4; 73 -2.3; 78 -2.2; 83 -2.1; 89 -2.2; 95 -2.3; 102 -3.0; 109 -3.5; 117 -3.7; 125 -3.7; 134 -4.3; 143 -5.5; 153 -6.1; 164 -4.6; 175 -4.7; 188 -6.0; 201 -5.9; 215 -5.7; 230 -5.1; 246 -4.7; 263 -4.2; 282 -3.5; 301 -2.8; 323 -2.4; 345 -2.3; 369 -2.1; 395 -1.7; 423 -1.3; 452 -1.0; 484 -0.8; 518 -0.6; 554 -0.4; 593 -0.2; 635 -0.1; 679 0.0; 726 -0.1; 777 -0.2; 832 -0.2; 890 -0.1; 952 -0.0; 1019 -0.1; 1090 -0.2; 1167 -0.4; 1248 -0.8; 1336 -0.7; 1429 -0.2; 1529 -0.0; 1636 0.2; 1751 0.6; 1873 1.0; 2004 1.6; 2145 2.3; 2295 3.1; 2455 4.0; 2627 4.8; 2811 5.2; 3008 4.8; 3219 4.5; 3444 3.9; 3685 3.3; 3943 3.1; 4219 3.9; 4514 4.6; 4830 4.2; 5168 5.9; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/NAD%20VISO%20HP50/NAD%20VISO%20HP50.png)