# 1R

Rustem Kussaiynov
IS - 18.577
Report
Here we can see rules that are built according “1R” algorithm. As we can see the minimum 
error  occurred in variables “astigmatic” and “tear_rate”. As the best variable I chose “astigmatic” and its rules are 
{'no': 'soft', 'yes': 'none'}}. There reason for that is this variable have only two states namely “no” and “yes”. 
By comparing constructed matrix in my code, the case “no” appears frequently with class “soft” while the case “yes” 
is associated with class “none”. 

The accuracy of algorithm “1R” is equal to 68.8%.

The accuracy of algorithm “0R” is equal to 50%.

Consequently, “1R” performs better for this classification problem.
