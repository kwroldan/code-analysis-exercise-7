# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

*Summary*
1) The function takes an array of inputs `a, b, margin`. 
2) If no margin is entered, the margin is set equal to zero.
3) First, the function checks if `a < b - margin` and if the statement is true, the function will return `-1`.
4) If step 3 is not true, it moves to `a - margin > b` and if that statement is true, the function returns `1`.
5) Lastly, if neither step 3 or step 4 come back true, the function returns `0`. 

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

| Input       | Output |
| ----------- | ------ |
| (8, 5, 2)   |   1    |
| (1, 10)     |  -1    | 
| (0, 10, 22) |   0    | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>I'm not sure the practical use of the function, but I can follow along with the statements!</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
