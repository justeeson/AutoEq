# Audeze LCD-2 Rev 2
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -0.3; 22 -0.3; 23 -0.3; 25 -0.3; 26 -0.3; 28 -0.3; 30 -0.2; 32 -0.2; 35 -0.1; 37 -0.2; 40 -0.2; 42 -0.2; 45 -0.2; 49 0.0; 52 0.2; 56 -0.2; 59 -0.8; 64 -1.1; 68 -1.1; 73 -1.1; 78 -1.2; 83 -1.1; 89 -1.2; 95 -1.6; 102 -2.0; 109 -2.3; 117 -2.6; 125 -3.1; 134 -3.4; 143 -3.7; 153 -4.1; 164 -4.2; 175 -4.3; 188 -4.6; 201 -4.6; 215 -4.6; 230 -4.6; 246 -4.5; 263 -4.5; 282 -4.7; 301 -4.6; 323 -4.3; 345 -3.9; 369 -3.8; 395 -3.9; 423 -4.0; 452 -4.2; 484 -4.5; 518 -4.5; 554 -4.0; 593 -3.6; 635 -3.4; 679 -3.5; 726 -3.1; 777 -2.8; 832 -2.6; 890 -2.0; 952 -0.8; 1019 0.1; 1090 0.6; 1167 1.3; 1248 0.5; 1336 -0.1; 1429 -0.8; 1529 -1.5; 1636 -1.9; 1751 -2.3; 1873 -1.0; 2004 -0.3; 2145 -0.2; 2295 -1.4; 2455 -0.4; 2627 1.1; 2811 1.1; 3008 1.2; 3219 1.2; 3444 2.7; 3685 4.2; 3943 5.9; 4219 6.0; 4514 6.0; 4830 4.4; 5168 2.4; 5530 1.0; 5917 -0.1; 6331 -0.0; 6775 0.2; 7249 1.1; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 -0.7; 18692 -2.2; 20000 -1.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -0.3; 22 -0.3; 23 -0.3; 25 -0.3; 26 -0.3; 28 -0.3; 30 -0.2; 32 -0.2; 35 -0.1; 37 -0.2; 40 -0.2; 42 -0.2; 45 -0.2; 49 0.0; 52 0.2; 56 -0.2; 59 -0.8; 64 -1.1; 68 -1.1; 73 -1.1; 78 -1.2; 83 -1.1; 89 -1.2; 95 -1.6; 102 -2.0; 109 -2.3; 117 -2.6; 125 -3.1; 134 -3.4; 143 -3.7; 153 -4.1; 164 -4.2; 175 -4.3; 188 -4.6; 201 -4.6; 215 -4.6; 230 -4.6; 246 -4.5; 263 -4.5; 282 -4.7; 301 -4.6; 323 -4.3; 345 -3.9; 369 -3.8; 395 -3.9; 423 -4.0; 452 -4.2; 484 -4.5; 518 -4.5; 554 -4.0; 593 -3.6; 635 -3.4; 679 -3.5; 726 -3.1; 777 -2.8; 832 -2.6; 890 -2.0; 952 -0.8; 1019 0.1; 1090 0.6; 1167 1.3; 1248 0.5; 1336 -0.1; 1429 -0.8; 1529 -1.5; 1636 -1.9; 1751 -2.3; 1873 -1.0; 2004 -0.3; 2145 -0.2; 2295 -1.4; 2455 -0.4; 2627 1.1; 2811 1.1; 3008 1.2; 3219 1.2; 3444 2.7; 3685 4.2; 3943 5.9; 4219 6.0; 4514 6.0; 4830 4.4; 5168 2.4; 5530 1.0; 5917 -0.1; 6331 -0.0; 6775 0.2; 7249 1.1; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 -0.7; 18692 -2.2; 20000 -1.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/headphoncecom/onear/Audeze%20LCD-2%20Rev%202/Audeze%20LCD-2%20Rev%202.png)