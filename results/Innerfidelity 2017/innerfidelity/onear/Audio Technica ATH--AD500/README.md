# Audio Technica ATH--AD500
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 5.8; 68 5.4; 73 5.0; 78 4.8; 83 4.4; 89 3.6; 95 2.7; 102 2.1; 109 1.7; 117 1.3; 125 0.6; 134 0.2; 143 -0.1; 153 -0.2; 164 -0.3; 175 -0.4; 188 -0.4; 201 -0.5; 215 -0.4; 230 -0.3; 246 -0.4; 263 -0.5; 282 -0.5; 301 -0.5; 323 -0.5; 345 -0.6; 369 -0.5; 395 -0.4; 423 -0.5; 452 -0.6; 484 -0.8; 518 -0.8; 554 -0.4; 593 0.0; 635 0.2; 679 0.2; 726 0.3; 777 0.6; 832 0.5; 890 0.2; 952 0.1; 1019 -0.1; 1090 -0.3; 1167 -0.8; 1248 -1.1; 1336 -1.1; 1429 -1.0; 1529 -0.6; 1636 -0.0; 1751 -0.1; 1873 0.2; 2004 0.8; 2145 1.5; 2295 1.9; 2455 3.4; 2627 4.3; 2811 5.5; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 5.4; 4219 4.7; 4514 5.9; 4830 5.8; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -0.4; 8880 -2.2; 9502 -2.5; 10167 -1.1; 10879 -0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 5.8; 68 5.4; 73 5.0; 78 4.8; 83 4.4; 89 3.6; 95 2.7; 102 2.1; 109 1.7; 117 1.3; 125 0.6; 134 0.2; 143 -0.1; 153 -0.2; 164 -0.3; 175 -0.4; 188 -0.4; 201 -0.5; 215 -0.4; 230 -0.3; 246 -0.4; 263 -0.5; 282 -0.5; 301 -0.5; 323 -0.5; 345 -0.6; 369 -0.5; 395 -0.4; 423 -0.5; 452 -0.6; 484 -0.8; 518 -0.8; 554 -0.4; 593 0.0; 635 0.2; 679 0.2; 726 0.3; 777 0.6; 832 0.5; 890 0.2; 952 0.1; 1019 -0.1; 1090 -0.3; 1167 -0.8; 1248 -1.1; 1336 -1.1; 1429 -1.0; 1529 -0.6; 1636 -0.0; 1751 -0.1; 1873 0.2; 2004 0.8; 2145 1.5; 2295 1.9; 2455 3.4; 2627 4.3; 2811 5.5; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 5.4; 4219 4.7; 4514 5.9; 4830 5.8; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -0.4; 8880 -2.2; 9502 -2.5; 10167 -1.1; 10879 -0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/innerfidelity/onear/Audio%20Technica%20ATH--AD500/Audio%20Technica%20ATH--AD500.png)