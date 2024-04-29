1. 20
2. 20
3. 20
4. The code returns an error because the variable ```result``` is only defined in line 5 in the **if block**. Therefore, ```result``` can only be accessed within the **if block**. 
5. The code returns an error because the variable ```result``` is **const** type, meaning its value cannot not be changed. As ```result``` is set to 0 in line 5, it will always be 0.
6. The code returns an error becasue of the we are trying to change the value of the **const** variable ```result`` in line 7. The code isn't able to run to line 13 as there is an error in line 9, thus the program stops running.