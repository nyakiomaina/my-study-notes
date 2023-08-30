# Time Complexity

Imagine you have a large box of differently colored LEGO bricks, and you're trying to find a specific color.

## Constant Time (O(1)):
It's like always knowing the top LEGO brick's color without looking inside the box.
No matter how many LEGO bricks you have, it always takes the same amount of time to check the top brick's color. In coding, some tasks always take the same time, regardless of the input size.

## Logarithmic Time (O(logn)):
Every time you look for a LEGO brick, you halve the number you have to search through until you find it.
Just like narrowing down a location on a map by repeatedly zooming in, certain tasks can be broken down in halves, making them faster as you progress.

## Linear Time (O(n)):
You look at each LEGO brick one by one until you find the one you're searching for.
The more LEGO bricks you have, the longer it might take to find your specific brick. Similarly, some tasks in coding take more time the more items they deal with.

## Linearithmic Time (O(nlogn)):
It's like sorting your LEGO bricks by color and then searching for a specific color.
Sometimes, breaking tasks into smaller ones and then working on each can be efficient. It's a mix of the sorting and then the halving method.

## Quadratic Time (O(n2)):
For every LEGO brick, you compare it with every other brick.
It's like checking every pair of LEGO bricks to see which two might fit together best. As you can imagine, if you have a lot of bricks, this can take a while.

## Exponential Time (O(2n)):
Imagine doubling the number of LEGO bricks you check each time: 1, then 2, then 4, then 8, and so on.
Some tasks grow in difficulty really quickly. They can become impractical for even slightly larger inputs.
