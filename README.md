# python-2.01-data-types

  1. Fork this repository
  2. Check out your fork
  3. Make a branch
  4. Add your answers to this file, each one surrounded by triple backquotes, like so:
    ```
    This is my answer
    ```
  5. Commit your answers to your branch
  6. Do a Pull Request against `master` in your repository
  7. Merge the pull request.
  8. Paste the link to your repository in your assignment in online.theironyard.com

  ## Answers go below for assignment 3 for Using variables

  1.  ```friendNames = ["Jason", "Joe", "Jesus"]```
  2.  ```USstates = ["Texas", "Florida", "Hawaii"]```
  3.  ```Population  = {78201: 1000, 78205: 3000, 78210: 2000, 78213: 5000}```
  4.  ```Population  = { "Census year 1980": { 78201: 1000, 78205: 3000, 78210: 2000, 78213: 5000 }, "Census year 1990": { 78201: 6000, 78205: 15000, 78210: 500, 78213: 3000}, "Census year 2000": {78201: 9000, 78205: 8000, 78201: 300, 78213: 2000}}```
  5.  ```todaydate = ['April 18, 2016']```
  6.  What decision(s) did you make when answering question #1?
      ```` What type of data type I will be using. This type of data is strings and place them in a list [] or Trules (), also depending if using order or unordered, and  mutable or immutable list.```

      What happens if you have two friends named "John"?
      ``` Here is Example naming two friends = ['John', 'John'] the answer will be print(friends)
['John', 'John'] the name will appear twice and more date will be required```

What if you have two friends named "John Smith"?
```if you have two friends that have the same first and last name like John Smith, you need have a middle initial on one of them to tell them apart. Example friends = ['John A. Smith', 'John Smith'] or you can place city where they were born Example FriendNames = {"Las Vegas": ["John Smith"], "San Diego": ["John Smith"]} to tall them apart```
7.  Why would you choose one over the other?
```Postal Abbreviation is commonly use with zip code to limit position data. It all depends on the output you receive and who reading it or what data is being enter and how many position data is the input requiring.```

If you needed to model both the two letter abbreviation and the "proper" name, what would your data structure look like?
```Data structure will be TX = ("TEXAS")```

How did you decide which two letters refer to which state?
```Had to goggle it```

Which states do the letters "AL", "AR", and "AK" refer to?
```Alabama, Arkansas, Alaska ```

How do you know?
```No two states may have the same abbreviation and If there are two words in the state's name, take the first letter of each. Take the first two letters of the state name to form the abbreviation only if there no old abbreviation. And states with the old abbreviation you take first and last letter of old abbreviation.```

8. What data type did you use for the ZIP code in question #3?
```string```

Why did you choose the data type you chose?
```The data type I used is STRING because Population is be identify by ZIP code```

Would another data type be better?
```List could be used```
Why or why not?
'''The list could only be used if you a multi zip code and population.```

9. Did you use a string, an integer, or some other data type for the census year in question #4?
```I used string and integer```

Why did you choose the data type you chose?
```Because you can use the string and use integer to select which data you want to used.```

Someone might want to use your data to look up the population of a given ZIP code over time, or they might want to look up population across all ZIP codes for a given year. Which of these tasks is your data structure best suited for?
```My data structure is suited for both the ZIP code identify how many in the population and over what time period.```

10. When storing data, it's often a good idea to see if there's a standard format for that kind of data. Look up "ISO 8601" on Wikipedia. How does the ISO 8601 standard compare to the way you decided to store today's date?
```ISO 8601 is to avoid misinterpretation of numeric representations of dates and times, particularly when data are transferred between countries with different conventions for writing numeric dates and times.```
