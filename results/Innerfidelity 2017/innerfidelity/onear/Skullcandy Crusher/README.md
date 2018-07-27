# Skullcandy Crusher
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 5.7; 22 4.3; 23 3.6; 25 2.3; 26 1.8; 28 0.7; 30 -0.3; 32 -1.1; 35 -2.2; 37 -2.9; 40 -3.6; 42 -4.0; 45 -4.4; 49 -4.6; 52 -4.6; 56 -4.7; 59 -4.8; 64 -4.8; 68 -4.6; 73 -4.3; 78 -3.9; 83 -3.6; 89 -2.9; 95 -2.2; 102 -2.6; 109 -3.6; 117 -4.1; 125 -4.9; 134 -5.2; 143 -5.0; 153 -5.4; 164 -5.1; 175 -5.2; 188 -5.5; 201 -5.6; 215 -5.7; 230 -5.8; 246 -5.9; 263 -6.0; 282 -6.0; 301 -6.1; 323 -5.8; 345 -5.6; 369 -5.4; 395 -5.3; 423 -5.2; 452 -5.4; 484 -5.5; 518 -5.8; 554 -5.4; 593 -4.8; 635 -4.6; 679 -4.5; 726 -4.2; 777 -3.6; 832 -3.1; 890 -2.7; 952 -1.3; 1019 -0.2; 1090 0.9; 1167 1.8; 1248 1.0; 1336 1.0; 1429 0.1; 1529 -1.0; 1636 -1.9; 1751 -2.2; 1873 -2.4; 2004 -2.9; 2145 -2.1; 2295 -2.1; 2455 -1.8; 2627 -0.9; 2811 -0.5; 3008 0.2; 3219 -0.2; 3444 0.0; 3685 1.1; 3943 1.3; 4219 0.5; 4514 3.9; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 5.7; 22 4.3; 23 3.6; 25 2.3; 26 1.8; 28 0.7; 30 -0.3; 32 -1.1; 35 -2.2; 37 -2.9; 40 -3.6; 42 -4.0; 45 -4.4; 49 -4.6; 52 -4.6; 56 -4.7; 59 -4.8; 64 -4.8; 68 -4.6; 73 -4.3; 78 -3.9; 83 -3.6; 89 -2.9; 95 -2.2; 102 -2.6; 109 -3.6; 117 -4.1; 125 -4.9; 134 -5.2; 143 -5.0; 153 -5.4; 164 -5.1; 175 -5.2; 188 -5.5; 201 -5.6; 215 -5.7; 230 -5.8; 246 -5.9; 263 -6.0; 282 -6.0; 301 -6.1; 323 -5.8; 345 -5.6; 369 -5.4; 395 -5.3; 423 -5.2; 452 -5.4; 484 -5.5; 518 -5.8; 554 -5.4; 593 -4.8; 635 -4.6; 679 -4.5; 726 -4.2; 777 -3.6; 832 -3.1; 890 -2.7; 952 -1.3; 1019 -0.2; 1090 0.9; 1167 1.8; 1248 1.0; 1336 1.0; 1429 0.1; 1529 -1.0; 1636 -1.9; 1751 -2.2; 1873 -2.4; 2004 -2.9; 2145 -2.1; 2295 -2.1; 2455 -1.8; 2627 -0.9; 2811 -0.5; 3008 0.2; 3219 -0.2; 3444 0.0; 3685 1.1; 3943 1.3; 4219 0.5; 4514 3.9; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Skullcandy%20Crusher/Skullcandy%20Crusher.png)