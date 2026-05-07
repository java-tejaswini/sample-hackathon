# Find and fix a bug using "Code Rewrite Skill"

## Introduction
This project contains a class called ValidateISBN which is used to validate ISBN numbers (the numbers that appear on the barcode on books.).

The class was written using Test driven development techniques, however there is a failing test and the developer cannot work out what is wrong.



## The challenge
You are building an AI-powered assistant that helps developers analyze, debug, and optimize Java code while preserving publishing-standard compliance and improving maintainability

* Write a Skill using which,
  * You should be able to explain why the code isn't working. 
  * You should be able to find out what is wrong with the code and fix it.
  * You should be able to explain what differences the changes to the code make.
  * Be sure to check that every change suggested is actually needed and take confirmations
  * The skill should return structured JSON like:

    {
      "issues": [],
      "fixed_code": "",
      "explanation": ""
    }

      e.g.
      Output format (JSON)

      {
        "bugs": [
          {
            "issue": "...",
            "why_it_is_wrong": "...",
            "location": "method or line reference",
            "severity": "low | medium | high"
          }
        ],
        "fixed_code": "...",
        "explanation": "..."
      }
* You should add the Constraints such as,
    * Do NOT change functionality unless fixing a bug
    * Explanations must reference actual code patterns
    * Avoid generic advice like “improve performance”
    * Be specific and actionable

* In addition, review the code and identify any improvements that could be made. 
* Determine if the descriptions of the exceptions that could be thrown accurate.
* As you make any changes, use the tests to check that the code still works!


## Points
This exercise is worth up to 200 points.

## Mark Scheme

* 50 points - finding the bug!
* 50 points - fixing the bug!
* 50 points - quality of the fix and appropriateness of the new code
* 50 points - you can explain to the satisfaction of your instructor what the issue was and why the solution is appropriate

## Bonus Points

* 100 points - Create an Agent

You can create an agent that
* Decides whether the issue is:
   * logical bug
   * performance problem
* Calls the appropriate skill
* Returns a structured response in the specified Output Format

As a BA,
* define skill purpose
* define the Validation rules if required
* detect functional risks/bugs
* create acceptance criteria
* improve naming conventions, error messages, redability



