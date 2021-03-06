# Count the Number of Islands

## Question

You're given an `n x m` 2d grid where `X` is water and `O` is land.
Please return the total number of islands in the grid.

Islands are only formed when they are connected vertically or horizontally. Diagonal connections are not counted as part of an island.

## Example

Example Data:
```
[
    ["O", "O", "O", "X", "O", "X"],
    ["O", "X", "O", "O", "X", "O"],
    ["O", "O", "O", "X", "X", "X"],
    ["X", "X", "X", "O", "O", "O"],
    ["O", "O", "O", "X", "X", "O"],
    ["O", "O", "O", "X", "O", "X"],
    ["O", "O", "O", "X", "O", "X"],
]
```

Example Answer:
```
// Counting the total number of islands manually
[
    ["1", "1", "1", "X", "2", "X"],
    ["1", "X", "1", "1", "X", "3"],
    ["1", "1", "1", "X", "X", "X"],
    ["X", "X", "X", "4", "4", "4"],
    ["5", "5", "5", "X", "X", "4"],
    ["5", "5", "5", "X", "6", "X"],
    ["5", "5", "5", "X", "6", "X"],
]
...
// Method returns total number of islands
const total = countIslands();
// Returns 6
```


## Requirements:

* You can use whatever coding language you prefer.
* You must track your work progress with git.
    *  Please commit everything in stages and not all in one go. We're more interested in how you work rather than the final answer.
* Fork this repository, make a new branch for the solution and then make a pull request to **your** repository when you've completed the question. Then send us a link to it.
* Write tests for your code to make sure it works.
* Update the improvements section below with what you think could've been done better in your solution.


## Bonus:
Now's your time to shine! Add your own flair and personalize this to make it say that this is your work. Show us what other skills and frameworks/tools you're familiar with. Here's some suggestions to get you started:

* Comment your code
* Update the README.md with more details on how to `Get Set Up`, `Run`, `Test` and anythinig else you can think of.
* Can you solve this linearly?
* Use a linter.
* Run tests on a CI.
* Make a UI that displays progress.
* Any thing else that you can think of to make this more awesome.

## Improvements:
How this could be improved:
```
// TODO
```

