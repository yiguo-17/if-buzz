# <a name="if-buzz">If Buzz</a>


### <a name="introduction">Introduction</a>

For this project, you'll be tackling more complex if/else/else-if statements in a classic simple algorithm problem: FizzBuzz.


### <a name="what-the-heck-is-fizzbuzz">What The Heck Is FizzBuzz?</a>

FizzBuzz is a classic problem meant to test people with simple logic that nonetheless can be approached in numerous ways. The rules are simple:

1. Given a number divisible by `3`, FizzBuzz prints the string "Fizz".
2. Given a number divisible by `5`, FizzBuzz prints the string "Buzz".
3. Given a number divisible by BOTH `3` and `5`, FizzBuzz prints the string "FizzBuzz".
4. Given a number divisible by neither, FizzBuzz simply prints that number out.

Often this problem is given as a loop, but our app will just handle one number, passed as the first argument. See the [Workflow](#workflow) section for examples.

### <a name="guidelines">Guidelines</a>

* Do NOT make any extra functions for this one. Just `getInput`!
* You can use `if` without `else` in this one, but it takes some tricks.

### <a name="workflow">Workflow</a>

* You'll fork and clone this repository.
* You'll be working in `main.js`.
* For now, we'll eschew automatic testing and just skip straight to manual testing. To try your app out, write `node main.js` followed by a number, in the directory of your app.
* You'll know you're done when the following inputs give their respective outputs:

`node main.js 1` -> '1'

`node main.js 2` -> '2'

`node main.js 3` -> 'Fizz'

`node main.js 4` -> '4'

`node main.js 5` -> 'Buzz'

`node main.js 15` -> 'FizzBuzz'


### <a name="steps">Steps</a>


### Stretch Goals

* If you solved the problem without `else`, try solving it with. And vice versa. Feel free to comment out your original solution.
* Add the ability for the user to write `node main.js 16 4 7`, making those second and third arguments the numbers used for a divisibility check instead of 3 and 5. You'll have to use `getInput` to get those extra arguments, store them in variables, and use them appropriately. The below examples use `2` and `3` as the Fizz and Buzz numbers, showing you the input you'd expect and what should result.

`node main.js 1 2 3` -> '1'

`node main.js 2 2 3` -> 'Fizz'

`node main.js 3 2 3` -> 'Buzz'

`node main.js 4 2 3` -> 'Fizz'

`node main.js 5 2 3` -> '5'

`node main.js 6 2 3` -> 'FizzBuzz'

* After completing the above stretch goal, change it so that if they leave off the second or third argument, we default to `3` and `5`. Make sure they still can put those arguments in, though! You can use `if` to make this happen. What happens if we check `getInput(1)` and there isn't an argument there? What value will it return?
