# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (firstName, lastName, age){
  const person = {
    firstName: firstName,
    lastName: lastName,
    age: age,
  }

  return person
}
```

| Input                   | Output |
| -----                   | ------ |
| "Matt", "Perrius", "46" | 'Matt Perrius 46' is stored as person    | 
| "Bob", "Smith", "23"    | 'Bob Smith 23' is stored as person       | 
| "Wade", "Wilson", "39"  | 'Wade Wilson 39' is stored as person     | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This program takes the inputs and stores them as the value of the variable person which could then be used somewhere else in a program.</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
