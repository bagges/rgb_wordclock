rgb_wordclock
=============

Wordclock based on the popular WS2812B RGB LED strips

More information can be found here: https://blogges.de/2014/02/diy-rgb-strip-wordclock/

####Build

1) Download Arduino 1.5.8 IDE from arduino.cc

2) Install "FastLED", "Arduino-Libraries\DCF77" and "Time" libraries from my repositories

3) Open Sketch and compile

####Known Issues

Compile Error: "IRremoteTools.cpp: 5: error: 'TKD2' was not declared in this scope"
Solution: Delete libraries\RobotIRremote\IRremoteTools.cpp and libraries\RobotIRremote\IRremoteTools.h (see http://forum.arduino.cc/index.php?topic=188236.0)

The clock is fast by exactly one minute.... Does anybody know why?

####LED Mapping

```
default_layout.h
113                                        110          .                             .

       9 10 29 30 49 50 69 70 89 90 109                      E S K I S T A F Ü N F
       8 11 28 31 48 51 68 71 88 91 108                      Z E H N Z W A N Z I G
       7 12 27 32 47 52 67 72 87 92 107                      D R E I V I E R T E L
       6 13 26 33 46 53 66 73 86 93 106                      V O R F U N K N A C H
       5 14 25 34 45 54 65 74 85 94 105                      H A L B A E L F Ü N F
       4 15 24 35 44 55 64 75 84 95 104                      E I N S X Ä M Z W E I
       3 16 23 36 43 56 63 76 83 96 103                      D R E I A U J V I E R
       2 17 22 37 42 57 62 77 82 97 102                      S E C H S N L A C H T
       1 18 21 38 41 58 61 78 81 98 101                      S I E B E N Z W Ö L F
       0 19 20 39 40 59 60 79 80 99 100                      Z E H N E U N K U H R

112                                        111          .                             .


alt_layout1.h
112                                                  113

        0   1   2   3   4   5   6   7   8   9  10
       11  12  13  14  15  16  17  18  19  20  21
       22  23  24  25  26  27  28  29  30  31  32
       33  34  35  36  37  38  39  40  41  42  43
       44  45  46  47  48  49  50  51  52  53  54
       55  56  57  58  59  60  61  62  63  64  65
       66  67  68  69  70  71  72  73  74  75  76
       77  78  79  80  81  82  83  84  85  86  87
       88  89  90  91  92  93  94  95  96  97  98
       99 100 101 102 103 104 105 106 107 108 109

111                                                  110
```

####Buy me a beer
I am working on this in my spare time. So if you want to buy me a beer, please click the Donate-Button on my blog:

https://blogges.de
