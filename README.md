# ssb_calculate
online calculate: https://dustinchen26.github.io/SLIV

## Purpose
SLIV is the Start and Length Indicator for the time domain allocation for PDSCH.
```
if (L-1) <= 7 then
      SLIV = 14 x (L-1) + S
else
      SLIV = 14 x (14-L+1) + (14-1-S)
          , where 0 < L <= 14 - S
                   S = Start Symbol Index
                   L = Number of Consecutive Symbols
```				   

## Program 1: Calculate SLIV
S: 
L: 
Calculate SLIV

## Program 2: Calculate S and L
SLIV: 
Calculate S and L

## Program 3: List all Possible Combinations
Print All Combinations
```
ex:
S = 0, L = 1, Calculated SLIV = 0
S = 0, L = 2, Calculated SLIV = 14
S = 0, L = 3, Calculated SLIV = 28
S = 0, L = 4, Calculated SLIV = 42
S = 0, L = 5, Calculated SLIV = 56
S = 0, L = 6, Calculated SLIV = 70
S = 0, L = 7, Calculated SLIV = 84
S = 0, L = 8, Calculated SLIV = 98
S = 0, L = 9, Calculated SLIV = 97
S = 0, L = 10, Calculated SLIV = 83
S = 0, L = 11, Calculated SLIV = 69
S = 0, L = 12, Calculated SLIV = 55
S = 0, L = 13, Calculated SLIV = 41
S = 0, L = 14, Calculated SLIV = 27
S = 1, L = 1, Calculated SLIV = 1
S = 1, L = 2, Calculated SLIV = 15
S = 1, L = 3, Calculated SLIV = 29
S = 1, L = 4, Calculated SLIV = 43
S = 1, L = 5, Calculated SLIV = 57
S = 1, L = 6, Calculated SLIV = 71
S = 1, L = 7, Calculated SLIV = 85
S = 1, L = 8, Calculated SLIV = 99
S = 1, L = 9, Calculated SLIV = 96
S = 1, L = 10, Calculated SLIV = 82
S = 1, L = 11, Calculated SLIV = 68
S = 1, L = 12, Calculated SLIV = 54
S = 1, L = 13, Calculated SLIV = 40
S = 2, L = 1, Calculated SLIV = 2
S = 2, L = 2, Calculated SLIV = 16
S = 2, L = 3, Calculated SLIV = 30
S = 2, L = 4, Calculated SLIV = 44
S = 2, L = 5, Calculated SLIV = 58
S = 2, L = 6, Calculated SLIV = 72
S = 2, L = 7, Calculated SLIV = 86
S = 2, L = 8, Calculated SLIV = 100
S = 2, L = 9, Calculated SLIV = 95
S = 2, L = 10, Calculated SLIV = 81
S = 2, L = 11, Calculated SLIV = 67
S = 2, L = 12, Calculated SLIV = 53
S = 3, L = 1, Calculated SLIV = 3
S = 3, L = 2, Calculated SLIV = 17
S = 3, L = 3, Calculated SLIV = 31
S = 3, L = 4, Calculated SLIV = 45
S = 3, L = 5, Calculated SLIV = 59
S = 3, L = 6, Calculated SLIV = 73
S = 3, L = 7, Calculated SLIV = 87
S = 3, L = 8, Calculated SLIV = 101
S = 3, L = 9, Calculated SLIV = 94
S = 3, L = 10, Calculated SLIV = 80
S = 3, L = 11, Calculated SLIV = 66
S = 4, L = 1, Calculated SLIV = 4
S = 4, L = 2, Calculated SLIV = 18
S = 4, L = 3, Calculated SLIV = 32
S = 4, L = 4, Calculated SLIV = 46
S = 4, L = 5, Calculated SLIV = 60
S = 4, L = 6, Calculated SLIV = 74
S = 4, L = 7, Calculated SLIV = 88
S = 4, L = 8, Calculated SLIV = 102
S = 4, L = 9, Calculated SLIV = 93
S = 4, L = 10, Calculated SLIV = 79
S = 5, L = 1, Calculated SLIV = 5
S = 5, L = 2, Calculated SLIV = 19
S = 5, L = 3, Calculated SLIV = 33
S = 5, L = 4, Calculated SLIV = 47
S = 5, L = 5, Calculated SLIV = 61
S = 5, L = 6, Calculated SLIV = 75
S = 5, L = 7, Calculated SLIV = 89
S = 5, L = 8, Calculated SLIV = 103
S = 5, L = 9, Calculated SLIV = 92
S = 6, L = 1, Calculated SLIV = 6
S = 6, L = 2, Calculated SLIV = 20
S = 6, L = 3, Calculated SLIV = 34
S = 6, L = 4, Calculated SLIV = 48
S = 6, L = 5, Calculated SLIV = 62
S = 6, L = 6, Calculated SLIV = 76
S = 6, L = 7, Calculated SLIV = 90
S = 6, L = 8, Calculated SLIV = 104
S = 7, L = 1, Calculated SLIV = 7
S = 7, L = 2, Calculated SLIV = 21
S = 7, L = 3, Calculated SLIV = 35
S = 7, L = 4, Calculated SLIV = 49
S = 7, L = 5, Calculated SLIV = 63
S = 7, L = 6, Calculated SLIV = 77
S = 7, L = 7, Calculated SLIV = 91
S = 8, L = 1, Calculated SLIV = 8
S = 8, L = 2, Calculated SLIV = 22
S = 8, L = 3, Calculated SLIV = 36
S = 8, L = 4, Calculated SLIV = 50
S = 8, L = 5, Calculated SLIV = 64
S = 8, L = 6, Calculated SLIV = 78
S = 9, L = 1, Calculated SLIV = 9
S = 9, L = 2, Calculated SLIV = 23
S = 9, L = 3, Calculated SLIV = 37
S = 9, L = 4, Calculated SLIV = 51
S = 9, L = 5, Calculated SLIV = 65
S = 10, L = 1, Calculated SLIV = 10
S = 10, L = 2, Calculated SLIV = 24
S = 10, L = 3, Calculated SLIV = 38
S = 10, L = 4, Calculated SLIV = 52
S = 11, L = 1, Calculated SLIV = 11
S = 11, L = 2, Calculated SLIV = 25
S = 11, L = 3, Calculated SLIV = 39
S = 12, L = 1, Calculated SLIV = 12
S = 12, L = 2, Calculated SLIV = 26
S = 13, L = 1, Calculated SLIV = 13
```
