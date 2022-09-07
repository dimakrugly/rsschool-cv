## [*https://rs.school/*]('rsschool')
---
# Dmytro Torop
---
### **Contacts**:

#### GitHub: dimakrugly
#### Discord: dimakrugly#0651
#### Mail: young-z@i.ua
---

### **About myself**:

#### Sales Manager in Cersanit SA, learning Javascript and Front-End technologies in RSSchool
---
### **My Code Example**
```
let val, i = 0, arr = [];
 while (val != 0) {
    val = +prompt("Enter value " + (i+1));
    if (val % 2) {
        arr[i] = val;
        i++;
        if (i == 20) {
            break
        }
    }
}
 
let max = Math.max(...arr);
 
for (let i = 0; i < arr.length; i++) {
    for (let k = 0; k < (max - arr[i]) / 2; k++) {
        console.put(" ");
    }
    for (let j = 0; j < arr[i]; j++) {
        console.put("*");
    }
    console.log();
}

```