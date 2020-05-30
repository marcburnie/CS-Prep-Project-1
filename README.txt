Big Data

Using Higher Order Functions to Reduce Large Amounts of Data
Let's use higher order functions like map, filter, and reduce to gather information and manipulate some data. Here we are importing historical Bitcoin data from 2013 to 2015. Each object contains information like price, market cap, fees, and much more. Let’s see what information we can extract using higher order functions!

To begin scroll down to line 8034 - click and drag the scrollbar that appears on the right as you begin scrolling to get there quickly.

1. First, let's log the bitcoinData object to investigate the structure of our data.
2. What is the data type of bitcoinData? Let’s say we just want to look at bitcoin information on May 1st, 2013. How can we do that?
3. Let’s say we want to create an array containing only the date and price of each day. Use the built-in map method to create an array containing that information.
4. Let’s create an array that only includes days when exchange volume was not 0. Which method should we use?
5. Everyday, new Bitcoins are generated. If we want to find out how many were generated all together during the time that’s provided in the dataset, can you figure out how to calculate it using reduce?
6. Bitcoin price fluctuates a lot. Let’s combine some array methods to find the total number of days when bitcoin price was over $100!
7. And finally, let’s find the average bitcoin transaction fees between 2013 and 2015. Be sure to floor this value.