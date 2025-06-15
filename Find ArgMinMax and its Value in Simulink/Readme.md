# [Matlab Tutorial] Find ArgMin/Max and its Value in Simulink

https://youtu.be/JwzOurcj7OQ

While working in my project, I encountered a problem of finding argmin argmax and their actual value. I found a solution and wanted to share it. 

Please let us know if you have a better approach.

Problem:  
We have three values B,C,D. After calculation, we want to know which one yeild the smallest difference with A.  
Val = [B,C, D]   
D = |A-(B+C)/2|  
Val[ArgMin(|A-B|,|A-C|,D)]  
