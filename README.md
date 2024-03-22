# [JSL03]: Which one is which? Declarative or Imperative?!
# Project Overview

In this project, I was presented with two JavaScript code examples, each demonstrating a different programming paradigm: imperative and declarative. My task was to analyse these examples and determine which one follows an imperative programming style and which one follows a declarative programming style. 

## Example : [1]

## Imperative Approach
1. **Step-by-Step Explanation:** The cookSteak function code starts by initializing variables ‘grillTemperature’ and ‘steakTemperature’. Then sets grillTemperature to 204. Seasing the steak: then it applies the season to both sides of the steak. Cooking the Steak: The code enters a while loop to cook the steak until it reaches the desired doneness. Inside the loop, it grill the steak, measures the internal temperature, then adjusts the grill temperature and cooking time based on steakWeight and desiredDoneness, and updates steakTemperature accordingly. Serving the Steak: After cooking, the code checks if the steak is ready to serve based on its temperature. If the steak is done, it returns 'Steak is ready to serve!' Otherwise, it returns 'Steak needs more cooking.'

2. **Emphasis on How:** The while loop it is used to iterate over the cooking process until the steak reach the desired doneness. Therefore in the loop, conditions determine whether the steak needs more cooking or is it ready to serve. Mutable Variables: grillTemperature and steakTemperature are used to track the state and progress of the cooking process. These variables are monitored throughout the execution of the function to reflect changes in grill temperature and steak temperature. This approach aligns with the principles of imperative programming. 


## Example : [2]

## Declarative Approach
1. **High-Level Process Description:** The code represents a cooking process defined as a constant array. Each step of the process is represented as an object within the array, with actions and parameters. The first step is to preheat the grill, with the temperature of the grill. After this, the steak is seasoned, and then cooked until the desired level of doneness is achieved. Finally, the last step in the process is to serve the cooked steak.

2. **Use of Data Structures:** The code uses data structures, such as an array of objects, that represent the sequential steps of a cooking process, organizing each step as an object which are associated with parameters. The code it demonstrates abstraction layers through the switch statement, encapsulating the actions associated with each step. By iterating through the 'cookingProcess' array and using the switch statement to execute the corresponding action for each step, the code abstracts the implementation details of each action, enhancing readability and maintainability. This approach aligns with the principles of declarative programming. 

# Learning Outcome 
- Learning the imperative approach provided a grasp of explicit step-by-step programming, while understanding the declarative approach emphasizes expressing desired outcomes without specifying exact steps. This equiped me with diverse problem-solving tools and a deeper understanding of control flow and high-level data manipulation.

Loom Recording Links: 

Example 1: Imperative[https://www.loom.com/share/97ba6cb5997a456dafbdedd070866dc6?sid=88fcf69f-1eb9-4d51-87cd-cd6c0a478447]

Example 2: Declarative[https://www.loom.com/share/7f48d1c3e3e84ddc85ee79345efdef87?sid=ea442a91-f34a-4dac-831c-7d9d3b52b1a8]

Learning Outcome [https://www.loom.com/share/100b8aaa902246e8911852776ea73b1e?sid=bf6d8fa1-7022-4c1b-9eb0-7bbf7602ac7d]

