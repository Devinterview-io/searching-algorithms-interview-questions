<div data-v-5e9078c0="" data-v-b06dc010="" class="QuestionsList">

<div data-v-5e9078c0="">

# Top 24 Searching interview questions and answers in 2021.

You can check all 24 Searching interview questions here 👉 https://devinterview.io/data/searching-interview-questions

<div data-v-5e9078c0="" class="unit">

<div>

## 🔹 1\. Explain what is Linear (Sequential) Search and when may we use one?

</div>

<div>

### Answer:

<div class="answer">

<div>

<div>

<div class="AnswerBody">

**Linear (sequential) search** goes through all possible elements in some array and compare each one with the desired element. It may take up to `_O_(_n_)` operations, where N is the size of an array and is widely considered to be horribly slow. In linear search when you perform one operation you reduce the size of the problem _by one_ (when you do one operation in binary search you reduce the size of the problem _by half_). Despite it, it can still be used when:

*   You need to perform this search only once,
*   You are _forbidden_ to rearrange the elements and you do not have any extra memory,
*   The array is tiny, such as ten elements or less, or the performance is not an issue at all,
*   Even though in theory other search algorithms may be faster than linear search (for instance binary search), in practice even on medium-sized arrays (around 100 items or less) it might be infeasible to use anything else. On larger arrays, it only makes sense to use other, faster search methods if the data is large enough, because the initial time to prepare (sort) the data is comparable to many linear searches,
*   When the list items are arranged in order of _decreasing probability_, and these probabilities are geometrically distributed, the cost of linear search is only `_O_(_1_)`
*   You have no idea what you are searching.

When you ask MySQL something like `SELECT x FROM y WHERE z = t`, and `z` is a column _without_ an index, linear search is performed with all the consequences of it. This is why adding an index to _searchable_ columns is important.

</div>

</div>

<div>

<div class="mb-2 mt-2"><span class="h5">Complexity Analysis</span></div>

<div class="hide-small">

<div class="row no-gutters my-2 align-items-end">

<div class="col font-weight-bold text-muted">Time:</div>

<div class="col disable text-center">

<div class="text-muted font-weight-bold justify-content-center">Constant</div>

<div class="complexity amazing first p-1 justify-content-center shadow-text">O(1)</div>

</div>

<div class="col disable text-center">

<div class="text-muted font-weight-bold justify-content-center">Dbl. Logarithmic</div>

<div class="complexity good p-1 justify-content-center shadow-text">O(log log n)</div>

</div>

<div class="col disable text-center">

<div class="text-muted font-weight-bold justify-content-center">Logarithmic</div>

<div class="complexity good p-1 justify-content-center shadow-text">O(log n)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold  text-muted justify-content-center">Square Root</div>

<div class="complexity fair p-1 justify-content-center shadow-text ">O(√n)</div>

</div>

<div class="col text-center">

<div class="font-weight-bold  text-muted justify-content-center">Linear</div>

<div class="complexity fair p-1 justify-content-center shadow-text selected-complexity effect7">O(n)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold text-muted justify-content-center">Linearithmic</div>

<div class="complexity bad p-1 justify-content-center shadow-text ">O(n log n)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold  text-muted justify-content-center">Quadratic</div>

<div class="complexity terrible p-1 justify-content-center shadow-text ">_O_(_n_<sup>2</sup>)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold   text-muted justify-content-center">Exponential</div>

<div class="complexity terrible p-1 justify-content-center shadow-text ">_O_(_2_<sup>n</sup>)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold text-muted">Factorial</div>

<div class="complexity terrible last p-1 justify-content-center shadow-text ">O(n!)</div>

</div>

</div>

</div>

<div class="hide-small">

<div class="row no-gutters my-2 align-items-end">

<div class="col font-weight-bold text-muted">Space:</div>

<div class="col text-center">

<div class="text-muted font-weight-bold justify-content-center">Constant</div>

<div class="complexity amazing first p-1 justify-content-center shadow-text selected-complexity effect7">O(1)</div>

</div>

<div class="col disable text-center">

<div class="text-muted font-weight-bold justify-content-center">Dbl. Logarithmic</div>

<div class="complexity good p-1 justify-content-center shadow-text">O(log log n)</div>

</div>

<div class="col disable text-center">

<div class="text-muted font-weight-bold justify-content-center">Logarithmic</div>

<div class="complexity good p-1 justify-content-center shadow-text">O(log n)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold  text-muted justify-content-center">Square Root</div>

<div class="complexity fair p-1 justify-content-center shadow-text ">O(√n)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold  text-muted justify-content-center">Linear</div>

<div class="complexity fair p-1 justify-content-center shadow-text ">O(n)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold text-muted justify-content-center">Linearithmic</div>

<div class="complexity bad p-1 justify-content-center shadow-text ">O(n log n)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold   text-muted justify-content-center">Quadratic</div>

<div class="complexity terrible p-1 justify-content-center shadow-text ">_O_(_n_<sup>2</sup>)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold   text-muted justify-content-center">Exponential</div>

<div class="complexity terrible p-1 justify-content-center shadow-text ">_O_(_2_<sup>n</sup>)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold text-muted">Factorial</div>

<div class="complexity terrible last p-1 justify-content-center shadow-text ">O(n!)</div>

</div>

</div>

</div>

<div class="hide-large">

**Time:** <mark>O(n)</mark>

**Space:** <mark>O(1)</mark>

</div>

<div class="mt-3">

<div>

<div class="AnswerBody">

*   A linear search runs in at worst _linear time_ and makes at most `n` comparisons, where `n` is the length of the list. If each element is _equally likely_ to be searched, then linear search has an average case of `(n+1)/2` comparisons, but the average case can be affected if the search probabilities for each element vary.
*   When the list items are arranged in order of _decreasing probability_, and these probabilities are geometrically distributed, the cost of linear search is only `_O_(_1_)`

</div>

</div>

</div>

</div>

<div style="font-size: 14px;">

<div class="mb-3 mt-2"><span class="h5">Implementation</span></div>

<div>



</div>

</div>

</nav>

</div>

<div class="mt-2">

<div class="AnswerBody">

    function linearSearch(array, toFind){
      for(let i = 0; i < array.length; i++){
        if(array[i] === toFind) return i;
      }
      return -1;
    }

</div>

</div>

</div>

<div class="row my-2">

<div><span>Source: <span>bytescout.com https://bytescout.com/blog/search-algorithms-in-modern-applications.html "Explain what is Linear (Sequential) Search and when may we use one? Interview Questions Source To Answer"</span></span>   </div>

</div>

</div>

</div>

</div>

</div>

<div data-v-5e9078c0="" class="unit">

<div>

## 🔹 2\. Explain what is Binary Search

</div>

<div>

### Answer:

<div class="answer">

<div>

<div>

<div class="AnswerBody">

When the list is **sorted** we can use the **binary search** (also known as half-interval search, logarithmic search, or binary chop) technique to find items on the list. Here's a step-by-step description of using binary search:

1.  Let `min = 1` and `max = n`.
2.  Guess the average of `max` and `min` **rounded down** so that it is an integer.
3.  If you guessed the number, stop. You found it!
4.  If the guess was too low, set _min_ to be one larger than the guess.
5.  If the guess was too high, set _max_ to be one smaller than the guess.
6.  Go back to step two.

In this example we looking for array item with value `4`:

When you do one operation in binary search we reduce the size of the problem **by half** (look at the picture below how do we reduce the size of the problem area) hence the complexity of binary search is `_O_(_log n_)`. The binary search algorithm can be written either _recursively_ or _iteratively_.

</div>

</div>

<div>

<div class="mb-2 mt-2"><span class="h5">Complexity Analysis</span></div>

<div class="hide-small">

<div class="row no-gutters my-2 align-items-end">

<div class="col font-weight-bold text-muted">Time:</div>

<div class="col disable text-center">

<div class="text-muted font-weight-bold justify-content-center">Constant</div>

<div class="complexity amazing first p-1 justify-content-center shadow-text">O(1)</div>

</div>

<div class="col disable text-center">

<div class="text-muted font-weight-bold justify-content-center">Dbl. Logarithmic</div>

<div class="complexity good p-1 justify-content-center shadow-text">O(log log n)</div>

</div>

<div class="col text-center">

<div class="text-muted font-weight-bold justify-content-center">Logarithmic</div>

<div class="complexity good p-1 justify-content-center shadow-text selected-complexity effect7">O(log n)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold  text-muted justify-content-center">Square Root</div>

<div class="complexity fair p-1 justify-content-center shadow-text ">O(√n)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold  text-muted justify-content-center">Linear</div>

<div class="complexity fair p-1 justify-content-center shadow-text ">O(n)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold text-muted justify-content-center">Linearithmic</div>

<div class="complexity bad p-1 justify-content-center shadow-text ">O(n log n)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold  text-muted justify-content-center">Quadratic</div>

<div class="complexity terrible p-1 justify-content-center shadow-text ">_O_(_n_<sup>2</sup>)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold   text-muted justify-content-center">Exponential</div>

<div class="complexity terrible p-1 justify-content-center shadow-text ">_O_(_2_<sup>n</sup>)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold text-muted">Factorial</div>

<div class="complexity terrible last p-1 justify-content-center shadow-text ">O(n!)</div>

</div>

</div>

</div>

<div class="hide-small">

<div class="row no-gutters my-2 align-items-end">

<div class="col font-weight-bold text-muted">Space:</div>

<div class="col text-center">

<div class="text-muted font-weight-bold justify-content-center">Constant</div>

<div class="complexity amazing first p-1 justify-content-center shadow-text selected-complexity effect7">O(1)</div>

</div>

<div class="col disable text-center">

<div class="text-muted font-weight-bold justify-content-center">Dbl. Logarithmic</div>

<div class="complexity good p-1 justify-content-center shadow-text">O(log log n)</div>

</div>

<div class="col disable text-center">

<div class="text-muted font-weight-bold justify-content-center">Logarithmic</div>

<div class="complexity good p-1 justify-content-center shadow-text">O(log n)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold  text-muted justify-content-center">Square Root</div>

<div class="complexity fair p-1 justify-content-center shadow-text ">O(√n)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold  text-muted justify-content-center">Linear</div>

<div class="complexity fair p-1 justify-content-center shadow-text ">O(n)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold text-muted justify-content-center">Linearithmic</div>

<div class="complexity bad p-1 justify-content-center shadow-text ">O(n log n)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold   text-muted justify-content-center">Quadratic</div>

<div class="complexity terrible p-1 justify-content-center shadow-text ">_O_(_n_<sup>2</sup>)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold   text-muted justify-content-center">Exponential</div>

<div class="complexity terrible p-1 justify-content-center shadow-text ">_O_(_2_<sup>n</sup>)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold text-muted">Factorial</div>

<div class="complexity terrible last p-1 justify-content-center shadow-text ">O(n!)</div>

</div>

</div>

</div>

<div class="hide-large">

**Time:** <mark>O(log n)</mark>

**Space:** <mark>O(1)</mark>

</div>

</div>

<div style="font-size: 14px;">

<div class="mb-3 mt-2"><span class="h5">Implementation</span></div>

<div>

<nav class="mdc-tab-bar">

<div class="mdc-tab-scroller">

<div class="mdc-tab-scroller__scroll-area mdc-tab-scroller__scroll-area--scroll" style="margin-bottom: 0px;">

<div class="mdc-tab-scroller__scroll-content"><button class="mdc-ripple-upgraded mdc-ripple-upgraded--background-focused mdc-tab mdc-tab--min-width mdc-tab--active" aria-selected="true" tabindex="0">

<div class="mdc-tab__content"><span class="mdc-tab__text-label"><span>JavaScript</span> <span class="shadow-text lang-badge js">JS</span></span></div>

<span class="mdc-tab-indicator mdc-tab-indicator--active"><span aria-hidden="true" class="mdc-tab-indicator__content mdc-tab-indicator__content--underline"></span></span></button><button class="mdc-ripple-upgraded mdc-tab mdc-tab--min-width">

<div class="mdc-tab__content"><span class="mdc-tab__text-label"><span>Java</span> <span class="shadow-text lang-badge java">Java</span></span></div>

<span class="mdc-tab-indicator"><span aria-hidden="true" class="mdc-tab-indicator__content mdc-tab-indicator__content--underline"></span></span></button><button class="mdc-ripple-upgraded mdc-tab mdc-tab--min-width">

<div class="mdc-tab__content"><span class="mdc-tab__text-label"><span>Python</span> <span class="shadow-text lang-badge py">PY</span></span></div>

<span class="mdc-tab-indicator"><span aria-hidden="true" class="mdc-tab-indicator__content mdc-tab-indicator__content--underline"></span></span></button></div>

</div>

</div>

</nav>

</div>

<div class="mt-2">

<div class="AnswerBody">

    var binarySearch = function(array, value) {
        var guess,
            min = 0,
            max = array.length - 1;	

        while(min <= max){
            guess = Math.floor((min + max) /2);
    	if(array[guess] === value)
    	    return guess;
    	else if(array[guess] < value)
    	    min = guess + 1;
    	else
    	    max = guess - 1;	
         }

         return -1;
    }

</div>

</div>

</div>

<div class="row my-2">

<div><span>Source: <span>www.tutorialspoint.com https://www.tutorialspoint.com/Binary-Search "Explain what is Binary Search Interview Questions Source To Answer"</span></span>   </div>

</div>

</div>

</div>

</div>

</div>

<div data-v-5e9078c0="" class="unit">

<div>

## 🔹 3\. What is an example of Interpolation Search being slower than Binary Search?

</div>

<div>

### Answer:

<div class="answer">

<div>

<div class="mb-2"><span class="h5">Problem</span></div>

<div>

<div class="AnswerBody">

I understand that interpolation search not only requires a sorted list but also uniformly distributed. Provide an understandable situation where Interpolation search is slower than binary search.

</div>

</div>

<div>

<div class="AnswerBody">

If we assume _uniform distribution_ of the values so we'll use simple linear interpolation. So if the values are:

    1,2,3,4,5,6,7,8,9,10000000

And we search for number `9`, searching using linear interpolation will go through all (excluding the first and last) the indices before finding the correct one. In such cases interpolation search will be `_O_(_n_)`.

</div>

</div>

<div class="row my-2">

<div><span>Source: <span>stackoverflow.com https://stackoverflow.com/questions/41877002/what-is-an-example-of-interpolation-search-being-slower-than-binary-search "What is an example of Interpolation Search being slower than Binary Search? Interview Questions Source To Answer"</span></span>   </div>

</div>

</div>

</div>

</div>

</div>

<div data-v-5e9078c0="" class="unit">

<div>

## 🔹 4\. Explain some Linear Search optimization techniques

</div>

<div>

### Answer:

<div class="answer">

<div>

<div>

<div class="AnswerBody">

If the elements you would be searching in a list are NOT uniformly distributed, then you could do certain optimizations that can help you improve the efficiency of your search algorithms. For such improvements to be effective, you do need to know the characteristics of the data being searched, the frequency and also the fact that the underlying collection needs to be modifiable.

1.  Most used pattern: If the likelihood of the current element being searched again is high, then move if from it's current location (say position i) to the front of the collection (say position 0). This does require moving elements from `A[0, i-1] to A[1, i]` to accommodate the new element at `A[0]`.
2.  The disadvantage of the above pattern is that it requires a lot of movement. One quick strategy is to move an element up on success by simply swapping the target element from position `x` with the first element at position `0`. This eventually results in a similar pattern as the frequently searched elements bubble up to the top of the list.
3.  On the other end of the spectrum, if an element is unlikely to be search again, then moving it to the end on find improves the chances of the other elements being searched.

</div>

</div>

<div class="row my-2">

<div><span>Source: <span>hoven-in.appspot.com https://hoven-in.appspot.com/Home/Data-Structures/Data-Structure-Interview-Questions/interview-questions-on-linear-search-01.html "Explain some Linear Search optimization techniques Interview Questions Source To Answer"</span></span>   </div>

</div>

</div>

</div>

</div>

</div>

<div data-v-5e9078c0="" class="unit">

<div>

## 🔹 5\. Recursive and Iterative Binary Search: Which one is more efficient and why?

</div>

<div>

### Answer:

<div class="answer">

<div>

<div>

<div class="AnswerBody">

*   With regard to **time complexity**, recursive and iterative methods both will give you `_O_(_log n_)` time complexity, with regard to input size, provided you implement correct binary search logic.
*   Focusing on **space complexity**:
    *   The iterative approach is more efficient since we are allocating a constant amount `O(1)` of space for the function call and constant space for variable allocations.
    *   There have been concerns around the recursive version regarding the function stack it is going to use. However, once you see it carefully, the recursive version is a **tail recursion**. Most of the modern compiler converts the tail recursion into iterative program. Thus, there won't be any issue regarding the usage of the function stack.

**P.S.** A **tail recursion** is also a kind of recursion but it will make the return value of the recursion call as the last statement of the method. This will make the calculation occurs _before_ the recursion call and hence there is _no need to keep the stack to store the intermediate value_ when it moves to the next recursive call.

</div>

</div>

<div class="row my-2">

<div><span>Source: <span>stackoverflow.com https://stackoverflow.com/questions/57481997/recursive-and-iterative-binary-search-which-one-is-more-efficient-and-why "Recursive and Iterative Binary Search: Which one is more efficient and why? Interview Questions Source To Answer"</span></span>   </div>

</div>

</div>

</div>

</div>

</div>

<div data-v-5e9078c0="" class="unit">

<div>

## 🔹 6\. Explain what is Interpolation Search

</div>

<div>

### Answer:

<div class="answer">

<div>

<div>

<div class="AnswerBody">

**Interpolation Search** is an algorithm similar to **Binary Search** for searching for a given target value in a sorted array. It is an improvement over Binary Search for instances, where the values in a sorted array are _uniformly distributed_.

The binary search always chooses the middle of the remaining search space. On a contrast Interpolation search, at each search step, calculates (using **interpolation formula**) where in the remaining search space the target _might be present_, based on the **low** and **high** values of the search space and the value of the target. For example, if the value of the key is closer to the last element, interpolation search is likely to start search toward the end side. The value actually found at this estimated position is then compared to the target value. If it is not equal, then depending on the comparison, the remaining search space is reduced to the part before or after the estimated position.

The idea of the **interpolation formula** or **partitioning logic** is to return higher value of `pos` when element to be searched is closer to `arr[hi]`. And smaller value when closer to `arr[low].`

    arr[] ==> Array where elements need to be searched
    x     ==> Element to be searched
    low   ==> Starting index in arr[]
    hi    ==> Ending index in arr[]

    pos = low + [ (x-arr[low])*(hi-low) / (arr[hi]-arr[Low]) ]

</div>

</div>

<div>

<div class="mb-2 mt-2"><span class="h5">Complexity Analysis</span></div>

<div class="hide-small">

<div class="row no-gutters my-2 align-items-end">

<div class="col font-weight-bold text-muted">Time:</div>

<div class="col disable text-center">

<div class="text-muted font-weight-bold justify-content-center">Constant</div>

<div class="complexity amazing first p-1 justify-content-center shadow-text">O(1)</div>

</div>

<div class="col text-center">

<div class="text-muted font-weight-bold justify-content-center">Dbl. Logarithmic</div>

<div class="complexity good p-1 justify-content-center shadow-text selected-complexity effect7">O(log log n)</div>

</div>

<div class="col disable text-center">

<div class="text-muted font-weight-bold justify-content-center">Logarithmic</div>

<div class="complexity good p-1 justify-content-center shadow-text">O(log n)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold  text-muted justify-content-center">Square Root</div>

<div class="complexity fair p-1 justify-content-center shadow-text ">O(√n)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold  text-muted justify-content-center">Linear</div>

<div class="complexity fair p-1 justify-content-center shadow-text ">O(n)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold text-muted justify-content-center">Linearithmic</div>

<div class="complexity bad p-1 justify-content-center shadow-text ">O(n log n)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold  text-muted justify-content-center">Quadratic</div>

<div class="complexity terrible p-1 justify-content-center shadow-text ">_O_(_n_<sup>2</sup>)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold   text-muted justify-content-center">Exponential</div>

<div class="complexity terrible p-1 justify-content-center shadow-text ">_O_(_2_<sup>n</sup>)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold text-muted">Factorial</div>

<div class="complexity terrible last p-1 justify-content-center shadow-text ">O(n!)</div>

</div>

</div>

</div>

<div class="hide-small">

<div class="row no-gutters my-2 align-items-end">

<div class="col font-weight-bold text-muted">Space:</div>

<div class="col text-center">

<div class="text-muted font-weight-bold justify-content-center">Constant</div>

<div class="complexity amazing first p-1 justify-content-center shadow-text selected-complexity effect7">O(1)</div>

</div>

<div class="col disable text-center">

<div class="text-muted font-weight-bold justify-content-center">Dbl. Logarithmic</div>

<div class="complexity good p-1 justify-content-center shadow-text">O(log log n)</div>

</div>

<div class="col disable text-center">

<div class="text-muted font-weight-bold justify-content-center">Logarithmic</div>

<div class="complexity good p-1 justify-content-center shadow-text">O(log n)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold  text-muted justify-content-center">Square Root</div>

<div class="complexity fair p-1 justify-content-center shadow-text ">O(√n)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold  text-muted justify-content-center">Linear</div>

<div class="complexity fair p-1 justify-content-center shadow-text ">O(n)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold text-muted justify-content-center">Linearithmic</div>

<div class="complexity bad p-1 justify-content-center shadow-text ">O(n log n)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold   text-muted justify-content-center">Quadratic</div>

<div class="complexity terrible p-1 justify-content-center shadow-text ">_O_(_n_<sup>2</sup>)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold   text-muted justify-content-center">Exponential</div>

<div class="complexity terrible p-1 justify-content-center shadow-text ">_O_(_2_<sup>n</sup>)</div>

</div>

<div class="col disable text-center">

<div class="font-weight-bold text-muted">Factorial</div>

<div class="complexity terrible last p-1 justify-content-center shadow-text ">O(n!)</div>

</div>

</div>

</div>

<div class="hide-large">

**Time:** <mark>O(log log n)</mark>

**Space:** <mark>O(1)</mark>

</div>

<div class="mt-3">

<div>

<div class="AnswerBody">

In the interpolation search algorithm, the midpoint is computed in such a way that it gives a higher probability of obtaining our search term faster. The worst case complexity of interpolation search is `_O_(_n_)`. However, its average case complexity, under the assumption that the keys are uniformly distributed, is _`O(log log N)`.

It can be proven that Interpolation Search repeatedly reducing the problem to a subproblem of size that is the **square root of the original problem size**, and algorithm will terminate after _`O(log log n)`_ steps (see proof [here http://www.cs.technion.ac.il/~itai/publications/Algorithms/p550-perl.pdf)). When the values are equally dispersed into the interval this search algorithm can be extremely useful – way faster than the binary search (that divides searching space _by half_).

</div>

</div>

</div>

</div>

<div style="font-size: 14px;">

<div class="mb-3 mt-2"><span class="h5">Implementation</span></div>

<div>



</div>

</div>

</nav>

</div>

<div class="mt-2">

<div class="AnswerBody">

    const interpolationSearch = (array, key) => {

      // if array is empty.
      if (!array.length) {
        return -1;
      }

      let low = 0;
      let high = array.length - 1;
      while (low <= high && key >= array[low] && x <= array[high]) {

        // calculate position with
        let pos = low + Math.floor(((high - low) * (key - array[low])) / (array[high] - array[low]));

        // if all elements are same then we'll have divide by 0 or 0/0
        // which may cause NaN
        pos = Number.isNaN(pos) ? low : pos;

        if (array[pos] === key) {
          return pos;
        }

        if (array[pos] > key) {
          high = pos - 1;
        } else {
          low = pos + 1;
        }

      }

      // not found.
      return -1;
    };

</div>

</div>

</div>

<div class="row my-2">

<div><span>Source: <span>kdr2.com https://kdr2.com/promotion/1901-interpolation-search-py.html "Explain what is Interpolation Search Interview Questions Source To Answer"</span></span>   </div>

</div>

</div>

</div>

</div>

</div>

<div data-v-5e9078c0="" class="unit">

<div>

## 🔹 7\. Explain why complexity of Binary Search is O(log n)?

</div>

<div>👉🏼 Check all 24 answers https://devinterview.io/data/searching-interview-questions </div>

</div>

<div data-v-5e9078c0="" class="unit">

<div>

## 🔹 8\. Compare Binary Search vs Linear Search

</div>

<div>👉🏼 Check all 24 answers https://devinterview.io/data/searching-interview-questions </div>

</div>

<div data-v-5e9078c0="" class="unit">

<div>

## 🔹 9\. What is a Jump (or Block) Search?

</div>

<div>👉🏼 Check all 24 answers https://devinterview.io/data/searching-interview-questions </div>

</div>

<div data-v-5e9078c0="" class="unit">

<div>

## 🔹 10\. Which of the following algorithms would be the fastest?

</div>

<div>👉🏼 Check all 24 answers https://devinterview.io/data/searching-interview-questions </div>

</div>

<div data-v-5e9078c0="" class="unit">

<div>

## 🔹 11\. Write a program for Recursive Binary Search

</div>

<div>👉🏼 Check all 24 answers https://devinterview.io/data/searching-interview-questions </div>

</div>

<div data-v-5e9078c0="" class="unit">

<div>

## 🔹 12\. What's wrong with this Recursive Binary Search function?

</div>

<div>👉🏼 Check all 24 answers https://devinterview.io/data/searching-interview-questions </div>

</div>

<div data-v-5e9078c0="" class="unit">

<div>

## 🔹 13\. Explain how does the Sentinel Search work?

</div>

<div>👉🏼 Check all 24 answers https://devinterview.io/data/searching-interview-questions </div>

</div>

<div data-v-5e9078c0="" class="unit">

<div>

## 🔹 14\. Explain what is Ternary Search?

</div>

<div>👉🏼 Check all 24 answers https://devinterview.io/data/searching-interview-questions </div>

</div>

<div data-v-5e9078c0="" class="unit">

<div>

## 🔹 15\. For Binary Search why do we need round down the average? Could we round up instead?

</div>

<div>👉🏼 Check all 24 answers https://devinterview.io/data/searching-interview-questions </div>

</div>

Thanks 🙌 for reading and good luck on your next tech interview!  
Explore 3800+ dev interview question here 👉 [Devinterview.io https://devinterview.io/)</div>

</div>
