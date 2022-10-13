# Friday Function Review

1.  Create a function named ```friday_function``` with one argument named ```movies```.
2.  Inside the body of the function write ```pass```.  This will prevent an error when running your code.  Remove the ```pass``` when we complete the function in step 5. 
   ```py
  def friday_function(movies):
    pass
   ```

3.  Ask the user for the top three best movies.  Use three input statements to get this information.  Save the movies to the three variables, ```movie1```, ```movie2```,```movie3```.  Or you could use a loop with one input statement.  Either way make sure to follow step 4
4.  Save the movies into a list called ```favorite_movies```.
5.  Remove the ```pass``` keyword.  Then use a ```for``` loop inside the ```friday_function``` to loop through the ```movies``` parameter and print:
   ```
    My number [___] favorite movie is [___]
  ```
  Where the first blank is 1,2 or 3 depending on the loop and the second blank is the movie at position 0,1 and 2.  Notice we need the index of the element and reference to the actual element.  [Read about enumerate to make this easy](https://realpython.com/python-enumerate/).

6.  Call the ```friday_function``` with ```favorite_movies``` as an argument.
7.  Observe the output.
8.  Note:  We are not modifying the list in the function....but if we did, we would be modifying the original list.  No list copying is necessary in this exercise. 
   