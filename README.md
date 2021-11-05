# The Open Closed Challenge

This is a starter Angular app for the OCP (Open Closed Principle) Coding challenge.

This exercise is kind of a deliberate practice. We'll focus solely on Open Closed principle, forgetting about others, in order to practice it to a greater extend.

## The task

You’ll be implementing an employee taxation calculator. There will be three rounds. At the beginning of each round, you’ll receive new requirements to implement. In the first round, you have 30 minutes to implement the requirements. In the next rounds, you have 20 minutes. If you fail to deliver in the given time you drop out of the challenge :stuck_out_tongue: . You have to deliver each round of work in a single commit. A person with the least number of removed lines wins (`git log --shortstat` will be used).

Remember about OCP, don't care too much about the other rules - the time is ticking.

The Open Closed Challenge
You’ll be implementing an employee taxation calculator. There will be three rounds. At the beginning of each round, you’ll receive new requirements to implement. In the first round, you have 30 minutes to implement the requirements. In the next rounds, you have 20 minutes. If you fail to deliver in the given time you drop out of the challenge :stuck_out_tongue: . You have to deliver each round of work in a single commit. A person with the least number of removed lines wins (git log --shortstat)
Remember about OCP, and YAGNI rule at the same time. Don’t care about the styling.

## Requirements

1. UoP - we need a Tax calculator. Add an input field with the employee's gross income and output with net income. The tax is calculated with the following rules: 17% tax is applied for the amount up to 7 000zł, and 32% tax is applied for the amount above 7 000zł.

<br/><br/><br/><br/><br/><br/><br/><br/><br/>

=== DON'T PEEK  until you're done with the previous task ===

<br/><br/><br/><br/><br/><br/><br/><br/><br/>

2. B2B - the boss comes in and asks you to add a dropdown where user can select the type tax. UoP is the name of the tax rules implemented in the previous step. B2B rules are simpler. There’s only 19% tax applied regardless of the income. 

<br/><br/><br/><br/><br/><br/><br/><br/><br/>

=== DON'T PEEK  until you're done with the previous task ===

<br/><br/><br/><br/><br/><br/><br/><br/><br/>

3. B2B New Order - next year new taxation rules for B2B introduced and called “New Order”. Users want to simulate the taxes after the New Order introduction. When user selects B2B tax type a “New Order” checkbox should appear. If the checkbox is selected then additional 9% of tax is added.
