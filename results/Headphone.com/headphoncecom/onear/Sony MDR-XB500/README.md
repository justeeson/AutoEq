# Sony MDR-XB500
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -9.6; 22 -9.8; 23 -9.9; 25 -10.0; 26 -10.1; 28 -10.2; 30 -10.3; 32 -10.4; 35 -10.5; 37 -10.5; 40 -10.5; 42 -10.5; 45 -10.5; 49 -10.6; 52 -10.6; 56 -10.5; 59 -10.4; 64 -10.2; 68 -10.2; 73 -10.3; 78 -10.7; 83 -11.1; 89 -11.7; 95 -11.9; 102 -11.9; 109 -12.2; 117 -13.0; 125 -13.7; 134 -14.3; 143 -14.9; 153 -15.1; 164 -14.4; 175 -14.0; 188 -14.0; 201 -14.6; 215 -15.1; 230 -15.1; 246 -14.6; 263 -14.3; 282 -14.1; 301 -13.9; 323 -13.6; 345 -13.2; 369 -12.8; 395 -12.2; 423 -11.5; 452 -10.8; 484 -9.8; 518 -8.8; 554 -7.5; 593 -6.2; 635 -4.7; 679 -3.2; 726 -1.7; 777 -0.3; 832 0.7; 890 1.0; 952 0.6; 1019 -0.1; 1090 -1.0; 1167 -1.5; 1248 -2.3; 1336 -2.9; 1429 -2.8; 1529 -2.5; 1636 -2.0; 1751 -1.3; 1873 -0.7; 2004 0.2; 2145 1.3; 2295 2.3; 2455 3.6; 2627 5.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 5.6; 4514 3.8; 4830 3.0; 5168 3.6; 5530 4.0; 5917 3.8; 6331 3.0; 6775 1.3; 7249 -1.2; 7756 -0.4; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -9.6; 22 -9.8; 23 -9.9; 25 -10.0; 26 -10.1; 28 -10.2; 30 -10.3; 32 -10.4; 35 -10.5; 37 -10.5; 40 -10.5; 42 -10.5; 45 -10.5; 49 -10.6; 52 -10.6; 56 -10.5; 59 -10.4; 64 -10.2; 68 -10.2; 73 -10.3; 78 -10.7; 83 -11.1; 89 -11.7; 95 -11.9; 102 -11.9; 109 -12.2; 117 -13.0; 125 -13.7; 134 -14.3; 143 -14.9; 153 -15.1; 164 -14.4; 175 -14.0; 188 -14.0; 201 -14.6; 215 -15.1; 230 -15.1; 246 -14.6; 263 -14.3; 282 -14.1; 301 -13.9; 323 -13.6; 345 -13.2; 369 -12.8; 395 -12.2; 423 -11.5; 452 -10.8; 484 -9.8; 518 -8.8; 554 -7.5; 593 -6.2; 635 -4.7; 679 -3.2; 726 -1.7; 777 -0.3; 832 0.7; 890 1.0; 952 0.6; 1019 -0.1; 1090 -1.0; 1167 -1.5; 1248 -2.3; 1336 -2.9; 1429 -2.8; 1529 -2.5; 1636 -2.0; 1751 -1.3; 1873 -0.7; 2004 0.2; 2145 1.3; 2295 2.3; 2455 3.6; 2627 5.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 5.6; 4514 3.8; 4830 3.0; 5168 3.6; 5530 4.0; 5917 3.8; 6331 3.0; 6775 1.3; 7249 -1.2; 7756 -0.4; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/headphoncecom/onear/Sony%20MDR-XB500/Sony%20MDR-XB500.png)