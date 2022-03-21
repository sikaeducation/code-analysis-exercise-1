# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (number){
  let table = ""

  const count = Array(10).fill(true)

  for (let iteration of count) {
    let spacer = ""
    if (iteration < 10){
      spacer = "\n"
    }
    table = `${table}${iteration} * ${number} = ${iteration * number}${spacer}`
  }

  return table
}
```

Inputs and outputs should be valid JavaScript values!

| Input | Output |
| ----- | ------ |
|       |        | 
|       |        | 
|       |        | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td></td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
