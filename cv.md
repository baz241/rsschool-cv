# My name

# Contact Info

* **E-mail:** [maksim.kondakov.0@gmail.com](maksim.kondakov.0@gmail.com)
* **GitHub:** [baz241](https://github.com/baz241)
* **Discord:**
* **LeetCode:** [baz241](https://leetcode.com/u/baz241/)


# About Me

Some info


# Skills

* HTML
* CSS
* JavaScript
* Git/GitHub
* Figma


# Code examples

```js
    const maxSubarray = (nums, k) => {
    let left = 0;
    let right = 0;
    let max;
    let sum = 0;
    for (right; right < nums.length; right++) {
        sum += nums[right];
        if (right - left === k - 1) {
            if (max === undefined) {
                max = sum;
            } else if (sum > max) {
                max = sum;
            }
            sum -= nums[left];
            left += 1;
        }
    }
    return max / k;
}
```

# Education

Some education


# Experience

Some experience


# Languages

- Russian
- English