# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (a, b, margin){
  if (!margin){
    margin = 0
  }

  if (a < b - margin){
    return -1
  } else if (a - margin > b){
    return 1
  } else {
    return 0
  }
}
```

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
  * Official answer is that it accepts 3 numbers, two to compare, and an optional margin. It returns with `a` is lower than, close to, or higher than `b`.
