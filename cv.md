cv.md

# Polovnikov Ivan

### Email: 
ivpolovnkov@hotmail.com

### Education & courses:
2018 - international relations (master), St.Petersburg State University \
2021 - JavaScript basic course at [learn.javascript.ru](https://learn.javascript.ru)

### Hard skills & experience: 
Technical support engineer (2020 - ) \
At basic level can work with **Python**, **Java Script *(native)*** , **Git**, **Linux console**, **Asterisk**

### Soft skills:
Able to grasp new concepts quickly, Highly organized, Technology-focused, Initiative

### Languages:
* Russian (native)
* English (Upper Intermediate)
* Italian (B2)

### Code example: 
[Find The Parity Outlier from codewars.com](https://www.codewars.com/kata/5526fc09a1bbd946250002dc)
```
function findOutlier(integers){
  let evenCounter = 0; 
  let oddCounter = 0;  
  
  for (let num of integers.slice(0,3)) {
    (num % 2 == 0) ? evenCounter++ : oddCounter++;
  }

  let rest = evenCounter > 1 ? 1 : 0;
  
  for (let num of integers) {
    if (Math.abs(num % 2) == rest) return num; 
  }
}
```
