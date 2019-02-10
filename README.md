#Nested Loop
~~~
A nested loop is a loop within a loop, an inner loop within the body of an outer one. 
How this works is that the first pass of the outer loop triggers the inner loop, which executes to completion. Then the second pass of the outer loop triggers the inner loop again.

~~~
#Time Complexity
~~~
          Statement                 Number of Executions

            n = 5                        1
           sum = 0
             i++	                     n
             i = 0	                     1
             i = 1                      1
             i = 2	                    1
…	
             i = n	                    1
             j++	                     n
             j = 0	                    1
             j = 1               	    1
              j = 2              	    1
…	
              j = n	                      1
         sum+=1                      	n^2
console.log(sum)	                    1


     Time Complexity =1+1+n+(1+1+1+...+1)+n+(1+1+1+...+1)+((n^2)+1=>

   3n^2+4n+3

   ~~~
​


​
​​ 
​
