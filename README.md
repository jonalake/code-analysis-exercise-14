# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (user){
  if (user.isActive){
    return `Welcome back, ${user.username}!`
  } else {
    return `Hey ${user.username}! Would you like to renew your subscription?`
  }
}
```

| Input | Output |
| ----- | ------ |
|   Jon = {username: Jon, isActive: true}    |    `Welcome back, Jon!`    | 
|   Brice = {username: Brice, isActive: false}    |   `Hey Brice! Would you like to renew your subscription?`     | 
|   Shawn = {username: Shawn, isActive: true}    |    `Welcome back, Shawn!`    | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>Checks if a input object, user, is active and displays a string message based on result of this check</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
