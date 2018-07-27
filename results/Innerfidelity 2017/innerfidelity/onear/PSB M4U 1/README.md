# PSB M4U 1
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-24**.
```
GraphicEQ: 10 -84; 20 -1.9; 22 -1.9; 23 -1.9; 25 -1.8; 26 -1.8; 28 -1.7; 30 -1.5; 32 -1.4; 35 -1.2; 37 -1.1; 40 -0.8; 42 -0.6; 45 -0.4; 49 -0.0; 52 0.3; 56 0.6; 59 0.9; 64 1.3; 68 1.7; 73 2.1; 78 2.2; 83 1.9; 89 0.5; 95 -1.5; 102 -2.9; 109 -3.1; 117 -2.7; 125 -3.0; 134 -3.9; 143 -4.0; 153 -3.7; 164 -2.6; 175 -3.7; 188 -4.0; 201 -3.5; 215 -3.2; 230 -2.9; 246 -2.6; 263 -2.1; 282 -1.8; 301 -0.8; 323 -0.4; 345 -1.6; 369 -1.1; 395 -0.1; 423 0.9; 452 0.6; 484 -0.3; 518 -0.1; 554 0.6; 593 1.5; 635 1.8; 679 1.0; 726 1.0; 777 0.8; 832 0.0; 890 -0.3; 952 -0.2; 1019 -0.0; 1090 -0.1; 1167 -0.3; 1248 -0.5; 1336 -0.7; 1429 -0.8; 1529 -0.9; 1636 -1.1; 1751 -1.4; 1873 -1.5; 2004 -1.4; 2145 -1.5; 2295 -1.5; 2455 -1.4; 2627 -1.3; 2811 -1.4; 3008 -1.4; 3219 -1.5; 3444 -2.1; 3685 -2.1; 3943 -1.2; 4219 -0.2; 4514 0.6; 4830 1.5; 5168 1.3; 5530 1.9; 5917 2.4; 6331 1.8; 6775 0.7; 7249 -2.4; 7756 -4.7; 8299 -5.9; 8880 -5.7; 9502 -3.8; 10167 -0.6; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -1.9; 22 -1.9; 23 -1.9; 25 -1.8; 26 -1.8; 28 -1.7; 30 -1.5; 32 -1.4; 35 -1.2; 37 -1.1; 40 -0.8; 42 -0.6; 45 -0.4; 49 -0.0; 52 0.3; 56 0.6; 59 0.9; 64 1.3; 68 1.7; 73 2.1; 78 2.2; 83 1.9; 89 0.5; 95 -1.5; 102 -2.9; 109 -3.1; 117 -2.7; 125 -3.0; 134 -3.9; 143 -4.0; 153 -3.7; 164 -2.6; 175 -3.7; 188 -4.0; 201 -3.5; 215 -3.2; 230 -2.9; 246 -2.6; 263 -2.1; 282 -1.8; 301 -0.8; 323 -0.4; 345 -1.6; 369 -1.1; 395 -0.1; 423 0.9; 452 0.6; 484 -0.3; 518 -0.1; 554 0.6; 593 1.5; 635 1.8; 679 1.0; 726 1.0; 777 0.8; 832 0.0; 890 -0.3; 952 -0.2; 1019 -0.0; 1090 -0.1; 1167 -0.3; 1248 -0.5; 1336 -0.7; 1429 -0.8; 1529 -0.9; 1636 -1.1; 1751 -1.4; 1873 -1.5; 2004 -1.4; 2145 -1.5; 2295 -1.5; 2455 -1.4; 2627 -1.3; 2811 -1.4; 3008 -1.4; 3219 -1.5; 3444 -2.1; 3685 -2.1; 3943 -1.2; 4219 -0.2; 4514 0.6; 4830 1.5; 5168 1.3; 5530 1.9; 5917 2.4; 6331 1.8; 6775 0.7; 7249 -2.4; 7756 -4.7; 8299 -5.9; 8880 -5.7; 9502 -3.8; 10167 -0.6; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-2.4dB*l, R=-2.4dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/PSB%20M4U%201/PSB%20M4U%201.png)