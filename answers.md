# CMPS 2200 Reciation 6
## Answers

**Name:**_______Riley Martin
         _Maddie Bonanno_________________


Place all written answers from `recitation-06.md` here for easier grading.







- **1b.**
Sorted:

|   n |   qsort-fixed-pivot |   qsort-random-pivot |
|-----|---------------------|----------------------|
|   1 |               0.010 |                0.012 |
|  10 |               0.082 |                0.064 |
|  50 |               0.705 |                0.333 |
| 100 |              12.483 |                1.371 |
| 200 |              12.861 |                2.363 |
| 300 |              28.228 |                2.409 |
| 400 |             164.677 |                4.121 |
| 500 |             115.426 |                5.065 |
| 600 |             200.600 |                6.213 |
| 700 |             262.269 |                6.886 |
| 800 |             319.640 |               57.910 |
| 900 |             402.969 |                9.654 |

Random:

|   n |   qsort-fixed-pivot |   qsort-random-pivot | 
|-----|---------------------|----------------------|
|   1 |               0.029 |                0.011 |
|  10 |               0.033 |                0.032 |
|  50 |               0.430 |                0.224 |  
| 100 |               1.345 |                0.407 |  
| 200 |               5.513 |                1.039 |  
| 300 |              11.888 |                1.598 |  
| 400 |              37.503 |                3.656 |  
| 500 |             159.383 |                5.214 |  
| 600 |             158.497 |               37.292 |  
| 700 |             133.276 |                4.139 |  
| 800 |             172.456 |                4.091 |  
| 900 |             212.458 |                8.384 |  

Using a sorted list with a fixed pivot causes the runtime to increase, as the input size increases more than the random list with a fixed pivot. Randomized pivot and/or lists cause the runtime to be much lower. 
- **1c.**

Random: 

|   n |   qsort-fixed-pivot |   qsort-random-pivot |   tim_sort |
|-----|---------------------|----------------------|------------|
|   1 |               0.022 |                0.021 |      0.001 |
|  10 |               0.026 |                0.032 |      0.000 |
|  50 |               0.632 |                0.257 |      0.002 |
| 100 |               2.447 |                0.399 |      0.002 |
| 200 |               6.848 |                1.052 |      0.004 |
| 300 |              14.492 |                1.672 |      0.005 |
| 400 |              54.293 |                3.446 |      0.010 |
| 500 |             114.561 |                5.228 |      0.012 |
| 600 |             128.773 |               29.828 |      0.016 |
| 700 |             143.934 |                4.140 |      0.011 |
| 800 |             176.852 |                4.177 |      0.012 |
| 900 |             202.458 |                7.491 |      0.046 |

Sorted:

|   n |   qsort-fixed-pivot |   qsort-random-pivot |   tim_sort |
|-----|---------------------|----------------------|------------|
|   1 |               0.013 |                0.019 |      0.002 |
|  10 |               0.074 |                0.068 |      0.002 |
|  50 |               0.981 |                0.391 |      0.004 |
| 100 |               3.587 |                0.804 |      0.006 |
| 200 |              14.859 |                2.012 |      0.007 |
| 300 |              20.900 |                2.528 |      0.008 |
| 400 |             208.331 |                3.486 |      0.012 |
| 500 |             155.576 |                5.152 |      0.014 |
| 600 |             197.245 |                6.458 |      0.015 |
| 700 |             216.332 |               11.148 |      0.017 |
| 800 |             303.449 |               59.420 |      0.019 |
| 900 |             400.924 |                9.118 |      0.018 |


The trends for both random and sorted implementations are similar to 1b. Tim_sort has the fastest runtime. 