# Class 8 Notes - Assign vs. Compare && While vs. For

## Assignment and Comparison Operators
Although assignment and comparison operators may both use the `=` sign they do very different things. Assignment operators like `=` `+=` and `-=` change the value of a variable. For example the code below would change the value of our variable to 12.

        let num = 7
        
        num += 5

This is different than comparison operators which measure two values against each other and return true/false. For example the code below would return `false`.

        7 <= 5

## For and While Loops  

I'm gonna be honest these two things seem verrrrry close to me. The biggest difference is that for loops are for when you want to execute a loop x number of times and while loops are for when you want to execute a loop ???? number of times. Below is an example of each. 

        for (i = 0; i < x; i++) {
            console.log(y);
        }

        let i = 0
        while (i < x) {
            console.log(y)
            i++
        }

## Things I want to know more about

Are the two loops I typed above functionally the same? Is one superior to the other in terms of performance?

Are for loops used in the case where either loop is valid to avoid infinite loops?

---

[Home](/reading-notes)|[Class 1](class1) |[Class 2](class2) |[Class 3](class3) |[Class 4](class4) |[Class 5](class5) |[Class 6](class6) |[Class 7](class7) |[Class 8](class8) |
