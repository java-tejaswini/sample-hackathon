# Improve performance with "Performance Analyzer Skill"

## Introduction

This project includes a class called **PrimeGenerator** which will create a list of very large prime numbers. These are needed for a security application.

## Challenge
The challenge is to improve the performance of the **PrimeGenerator** class. The current implementation is slow and inefficient. Your task is to alayze the code and improve the code performance to make it faster and more efficient **without changing its functionality**

As you work through the challenge you may ask the GenAI tools to keep optimising a number of times - at each point keep a record of how long the process takes so that you can be sure each optimisation is a genuine improvement on the last. 

## Objectives
* The Skill should Analyze the code
* The SKill should identify performance bottlenecks
* The Skill should explain why they impact performance
* The should suggest optimized implementation
* The skill should estimate performance improvements

## Constraints
* Do NOT change the functionality (must still return prime numbers)
* Do NOT reduce the prime size (must remain 2000-bit)
* Focus on performance, not style
* Be specific—avoid generic suggestions like “optimize loop”

## Expected output format
* The skill should return structured like:
```
    ## The performance bottlenecks are,
    ## The resons of impacting the performance,
    ## Suggestions to optimize the code, 
    ## Estimate performance improvements are
```

## Notes
* **You must not alter the bit length** of the BigIntegers being generated - the security application requires this to be set to 2000.
* Ensure you understand the code being generated - ask the GenAI tools to explain anything you are not sure about.


## Points
This challenge is worth up to 300 points

### Mark Scheme

* 100 points - you have successfully solved the problem
* 100 points - you can explain to your instructor to their satisfaction what the problem was and why the solution works

### Bonus Points

* 100 points - Create an Agent

You can create an agent that 
* Decides whether the issue is:
   * logical bug
   * performance problem
* Calls the appropriate skill
* Returns a structured response in the specified Output Format

### As Bussiness Analyst,
* Define Performance Expectations
* Provide Business Requirement such as generation time, support for batch requests other performance parameters
* Suggest Optimization Recommendations
