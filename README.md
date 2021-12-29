# leetcode
Leetcode repository for interview question practice.

<details>
<summary>template</summary>

https://leetcode.com/problems/

solution

Runtime:   
Memory:

```js

```

</details>

<details>
<summary>1. Two Sum</summary>

https://leetcode.com/problems/two-sum/

Naive is using two for loops to iterate through every number combination.  
Optimal is using memory to store what you've seen before to check if you've previously seen the difference.

Runtime: O(n)  
Memory: O(n)

```js
/**
 * @param {number[]} nums
 * @param {number} target
 * @return {number[]}
 */
var twoSum = function(nums, target) {
    const numsObject = {};
    for (let i = 0; i<nums.length; i++){
        const difference = target-nums[i];
        if (difference in numsObject){
            return[i,numsObject[difference]];
        }
        numsObject[nums[i]] = i;
    }
    
};
```

</details>
<details>
<summary>2. Add Two Numbers</summary>

https://leetcode.com/problems/add-two-numbers/



Runtime: 
Memory:

```js

```

</details>


