# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident that you know how the function works.
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

Inputs and outputs should be valid JavaScript values!

|                  Input                          |         Output            |
| Andrew = {username: "aconkli9", isActive: true} | 'Welcome back, aconkli9!' |
| Raja = {username: "OrangeCat1", isActive: flase}|  'Hey OrangeCat1! Would you like to renew your subscription? | 
|       |        | 
|       |        | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This program takes an object as an input and checks the object to find the username and whether or not the user is active. Depending on the properties of the object, the program returns one of two messages. If the user is active, the program returns a welcome back message. If the user is inactive, the program returns a message asking the user to renew their subscription. </td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
