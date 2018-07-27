# Blue MOFI Passive
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 0.7; 22 0.6; 23 0.6; 25 0.5; 26 0.5; 28 0.4; 30 0.3; 32 0.3; 35 0.2; 37 0.2; 40 0.2; 42 0.2; 45 0.2; 49 0.2; 52 0.2; 56 0.2; 59 0.1; 64 0.1; 68 0.0; 73 -0.0; 78 -0.1; 83 -0.2; 89 -0.5; 95 -0.8; 102 -1.2; 109 -1.4; 117 -1.5; 125 -1.8; 134 -2.3; 143 -2.9; 153 -3.2; 164 -2.8; 175 -2.4; 188 -3.0; 201 -3.1; 215 -2.9; 230 -2.4; 246 -2.0; 263 -1.5; 282 -0.7; 301 -0.1; 323 0.2; 345 -0.1; 369 -0.2; 395 -0.4; 423 0.5; 452 1.1; 484 1.2; 518 1.0; 554 1.0; 593 1.3; 635 1.5; 679 1.1; 726 0.7; 777 0.8; 832 0.8; 890 0.4; 952 0.1; 1019 -0.1; 1090 -0.2; 1167 -0.3; 1248 -0.2; 1336 -0.1; 1429 -0.2; 1529 -0.2; 1636 -0.2; 1751 -0.1; 1873 0.2; 2004 1.0; 2145 1.7; 2295 2.1; 2455 2.5; 2627 3.5; 2811 4.3; 3008 4.9; 3219 5.1; 3444 5.9; 3685 6.0; 3943 5.9; 4219 3.9; 4514 5.9; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 0.7; 22 0.6; 23 0.6; 25 0.5; 26 0.5; 28 0.4; 30 0.3; 32 0.3; 35 0.2; 37 0.2; 40 0.2; 42 0.2; 45 0.2; 49 0.2; 52 0.2; 56 0.2; 59 0.1; 64 0.1; 68 0.0; 73 -0.0; 78 -0.1; 83 -0.2; 89 -0.5; 95 -0.8; 102 -1.2; 109 -1.4; 117 -1.5; 125 -1.8; 134 -2.3; 143 -2.9; 153 -3.2; 164 -2.8; 175 -2.4; 188 -3.0; 201 -3.1; 215 -2.9; 230 -2.4; 246 -2.0; 263 -1.5; 282 -0.7; 301 -0.1; 323 0.2; 345 -0.1; 369 -0.2; 395 -0.4; 423 0.5; 452 1.1; 484 1.2; 518 1.0; 554 1.0; 593 1.3; 635 1.5; 679 1.1; 726 0.7; 777 0.8; 832 0.8; 890 0.4; 952 0.1; 1019 -0.1; 1090 -0.2; 1167 -0.3; 1248 -0.2; 1336 -0.1; 1429 -0.2; 1529 -0.2; 1636 -0.2; 1751 -0.1; 1873 0.2; 2004 1.0; 2145 1.7; 2295 2.1; 2455 2.5; 2627 3.5; 2811 4.3; 3008 4.9; 3219 5.1; 3444 5.9; 3685 6.0; 3943 5.9; 4219 3.9; 4514 5.9; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Blue%20MOFI%20Passive/Blue%20MOFI%20Passive.png)