# threads
# Description
Program will calculate the sum of numbers from 0 to 9999 using threads in C. It will create 10 threads
and each thread will calculate the sum of 1000 given its respectful range. So one thread will go from 
0-1000 and another will do 3000-4000 and so on and so forth. Then will add up all these sums and 
give us the final sum of 10000

# Creation
* First will create 10 threads each with their own unique ids
* Then each thread will calculate a sum of 1000 based of a range
   * So one thread will go from 0-1000 then the next will 1000-2000, ....
* After the all threads finish their job they will then add up all their sums to get the final sum

# Compilation
To compile the program you will use a virtual machine to access the C file
once you have the terminal open you will locate the directory the file is in and then use the commands below
* gcc -pthread -o [chooseyourownname] threads.c
* ./[chooseyourownname]

  # Output Example
  This is what a given output should look like
  ![threadsEX](https://github.com/user-attachments/assets/ebbeaf6b-aca4-42ed-ac63-6ddd51a4c374)
