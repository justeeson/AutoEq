# Stax 4070
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-23**.
```
GraphicEQ: 10 -84; 20 2.3; 22 0.7; 23 0.1; 25 -0.8; 26 -1.0; 28 -1.3; 30 -1.4; 32 -1.4; 35 -1.1; 37 -0.9; 40 -0.6; 42 -0.4; 45 -0.1; 49 0.2; 52 0.4; 56 0.6; 59 0.7; 64 0.8; 68 0.8; 73 0.7; 78 0.7; 83 0.6; 89 0.4; 95 0.3; 102 -0.0; 109 -0.2; 117 -0.5; 125 -1.0; 134 -1.2; 143 -1.4; 153 -1.6; 164 -1.7; 175 -1.6; 188 -1.9; 201 -2.0; 215 -2.0; 230 -2.1; 246 -2.3; 263 -2.4; 282 -2.5; 301 -2.6; 323 -2.7; 345 -2.4; 369 -1.6; 395 -0.4; 423 0.3; 452 -0.0; 484 -0.7; 518 -0.6; 554 -0.1; 593 0.6; 635 0.9; 679 0.8; 726 0.5; 777 0.6; 832 0.4; 890 0.1; 952 0.0; 1019 -0.2; 1090 -0.4; 1167 -0.8; 1248 -1.1; 1336 -1.5; 1429 -2.0; 1529 -2.8; 1636 -3.5; 1751 -3.9; 1873 -3.9; 2004 -3.6; 2145 -3.1; 2295 -2.5; 2455 -2.1; 2627 -2.3; 2811 -2.7; 3008 -3.3; 3219 -3.4; 3444 -3.7; 3685 -4.2; 3943 -3.9; 4219 -3.4; 4514 -2.3; 4830 -0.7; 5168 0.2; 5530 -0.1; 5917 -1.3; 6331 -1.1; 6775 1.9; 7249 1.3; 7756 0.3; 8299 -0.8; 8880 -2.7; 9502 -2.4; 10167 -1.6; 10879 -1.8; 11640 -2.1; 12455 -1.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 -1.2
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 2.3; 22 0.7; 23 0.1; 25 -0.8; 26 -1.0; 28 -1.3; 30 -1.4; 32 -1.4; 35 -1.1; 37 -0.9; 40 -0.6; 42 -0.4; 45 -0.1; 49 0.2; 52 0.4; 56 0.6; 59 0.7; 64 0.8; 68 0.8; 73 0.7; 78 0.7; 83 0.6; 89 0.4; 95 0.3; 102 -0.0; 109 -0.2; 117 -0.5; 125 -1.0; 134 -1.2; 143 -1.4; 153 -1.6; 164 -1.7; 175 -1.6; 188 -1.9; 201 -2.0; 215 -2.0; 230 -2.1; 246 -2.3; 263 -2.4; 282 -2.5; 301 -2.6; 323 -2.7; 345 -2.4; 369 -1.6; 395 -0.4; 423 0.3; 452 -0.0; 484 -0.7; 518 -0.6; 554 -0.1; 593 0.6; 635 0.9; 679 0.8; 726 0.5; 777 0.6; 832 0.4; 890 0.1; 952 0.0; 1019 -0.2; 1090 -0.4; 1167 -0.8; 1248 -1.1; 1336 -1.5; 1429 -2.0; 1529 -2.8; 1636 -3.5; 1751 -3.9; 1873 -3.9; 2004 -3.6; 2145 -3.1; 2295 -2.5; 2455 -2.1; 2627 -2.3; 2811 -2.7; 3008 -3.3; 3219 -3.4; 3444 -3.7; 3685 -4.2; 3943 -3.9; 4219 -3.4; 4514 -2.3; 4830 -0.7; 5168 0.2; 5530 -0.1; 5917 -1.3; 6331 -1.1; 6775 1.9; 7249 1.3; 7756 0.3; 8299 -0.8; 8880 -2.7; 9502 -2.4; 10167 -1.6; 10879 -1.8; 11640 -2.1; 12455 -1.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 -1.2
Copy: L=-2.3dB*l, R=-2.3dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Stax%204070/Stax%204070.png)