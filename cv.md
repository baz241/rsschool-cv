# Maksim Kondakov

# Contact Info

* **E-mail:** [manulmanulov425@gmail.com](manulmanulov425@gmail.com)
* **GitHub:** [baz241](https://github.com/baz241)
* **Discord:** [Maxim@baz241]
* **LeetCode:** [baz241](https://leetcode.com/u/baz241/)


# About Me

Now I work in a small local IT company. Further I plan to get a job as a frontend developer. I like to learn new technologies very much.


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

- [CS50 lectures](https://www.youtube.com/channel/UCcabW7890RKJzL968QWEykA)
- [HTML/CSS](https://www.udemy.com/course/webdeveloper/)


# Experience

I have little experience in JS and Frontend development.


# Languages

- Russian
- English