# find-numbers-with-even-digits
leetcode challenge - Javascript


let findNumbers = function(nums) {
    let count = 0
    for (let i = 0; i < nums.length; i++) {
        count += nums[i].toString().length % 2 ? 0 : 1
    }
    return count
};
