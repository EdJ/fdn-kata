## Foundation Kata

This is an opportunity to show off your coding skills!

Please spend no more than 30 minutes on the task :) Please use node.js for your solution, but feel free to break out of the provided folder structure.

# The Kata

At Foundation we want to provide a way for our users to configure and run simple workflows. Workflows can have multiple steps, and each step can run a pre-defined function.

Examples of functions might be:

Inputs | Action | Outputs
----- | ------ | ------
{ test: 1 } | Increment "test" | { test: 2 }
{ test: 1 } | Set "test" to "hi" | { test: "hi" }
{ test: 1, email: 'test@test.com' } | Send an email to "email" | An email is sent to test@test.com
{ test: 1 }, 'test@test.com' | Set "email" to the second input | { test: 1, email: 'test@test.com' }
