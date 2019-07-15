hello
 ===
 https://www.codewars.com/kata/determine-offspring-sex-based-on-genes-xx-and-xy-chromosomes/train/javascript
 ```javascript
 function chromosomeCheck(sperm) {
   return sperm == 'XY' ? "Congratulations! You're going to have a son.": "Congratulations! You're going to have a daughter."
 }
 ```
https://www.codewars.com/kata/thinkful-logic-drills-traffic-light/train/javascript
```javascript
function updateLight(current) {
   if (current === 'green') {
     return 'yellow';
   } else if (current === 'yellow') {
     return 'red';
   } else if (current === 'red') {
     return 'green';
   }
 }
 ```
 ```javascript
 function switchItUp(number){
   var words = ['Zero', 'One', 'Two', 'Three', 'Four', 'Five', 'Six', 'Seven', 'Eight', 'Nine'];
   return words[number];
 }
 ```
 ```javascript
 function greet(name){
   if(name === "Johnny") {
     return "Hello, my love!";
     } else return "Hello, " + name + "!";
 }
 ```
 www.codewars.com
 ```javascript
 function spongeMeme(sentence) {
   let res = '';
   for (let i = 0; i < sentence.length; i++) {
     res += (i % 2) ? sentence[i].toLowerCase() : sentence[i].toUpperCase();
   }
   return res;
 }
 ```
 Reverse List Order
 ```javascript
 function reverseList(list) {
   let a = [];
   for (let i = list.length -1; i >= 0; i--){
   a.push(list[i]); 
   }
   return a
 }
 ```
 new solution
 '''
'''javascript
function solution(str){
  let rev = '';
  for (let i = str.length -1; i >= 0; i--){
  rev = rev + str[i];
  }
  return rev;
}
```
```javascript
function reverseNumber(n) {
  if (n >= 0) {
  let rn = n.toString().split('').reverse();
  return +(rn.join(''));
  } else {
  n = n * (-1);
  let rn = n.toString().split('').reverse();
  return (-1) * (+(rn.join('')));
  }
}
```

```javascript
function toBinary(n){
  return +n.toString(2);
}
```
add new text
 ```javascript
 function reverseList(list) {
   let a = [];
   for (let i = list.length -1; i >= 0; i--){
   a.push(list[i]);
   }
   return a
 }
 ```
new solution
 '''
'''javascript
function solution(str){
  let rev = '';
  for (let i = str.length -1; i >= 0; i--){
  rev = rev + str[i];
  }
  return rev;
}
```
```javascript
function solution(str){
  return str.split('').reverse().join('');
}
```
```javascript
function typeOfSum(a, b) {
  return typeof (a + b);// good luck
}
```
```javascript
function repeatStr (n, s) {
  return s.repeat(n);
}
```
```javascript
function isDivideBy(num, a, b) {
  return num % a === 0 && num % b === 0;
}
```
```javascript
function nthEven(n){
/*  let res = 0;
  let j = 0;
  for(let i = 1; i<n; i++){
    j += 2;
  }
  return j;*/
  return n*2-2;
}
```
```javascript
function points(games) {
  let count = 0;
  games.forEach(item =>{
    if(item[0] > item[2]) count +=3;
    if(item[0] === item[2]) count +=1;
  })
  return count;
}
```
```javascript
function greet (name, owner) {
  return name === owner ? 'Hello boss' :   'Hello guest';
}
```
```javascript
function averageString(str) {
  if (str === '') return 'n/a';
  let arr = ['zero', 'one', 'two', 'three', 'four', 'five', 'six', 'seven', 'eight', 'nine'];
  let arrStr = str.split(' ');
  let sum = 0;
    for (let i = 0; i < arrStr.length; i++) {
      sum +=arr.indexOf(arrStr[i]);
      if(arrStr[i] === '' || !arr.includes(arrStr[i])) return 'n/a';
    }
    let avg = Math.floor(sum / arrStr.length);

    return arr[avg];

}
```
```javascript
function palindrome(num) {
  if (typeof num !== 'number' || num < 0) return 'Not valid';
  if(num < 10) return false;
  num = num.toString().split('').sort();
  let count = 0;
  for(let i = 0; i< num.length - 1; i){
    if(num[i] === num[i+1]){
      count = count + 2;
      i = i + 2;
    } else i++;
  }
  if(num.length === count || num.length === count +1){
    return true;
  } else return false;
}
```
```javascript
function explode(x){
  let res = [];
  let score = 0;

  for(let i = 0; i<x.length; i++){
    if (+x[i]) score += x[i];
  }
  if (score === 0) return 'Void!';
  for(let i = score; i>0; i--){
    res.push(x);
  }
  console.log(score);
  return res;
}
```
```javascript
function isDivideBy(num, a, b) {
  return num % a === 0 && num % b === 0;
}
```
```javascript
function crap(x, b, c){
  const str = x.toString();
  if(str.includes('D')) return 'Dog!!';
  const cC = str.split('@').length -1;
  return b * c >= cC ? 'Clean': 'Cr@p';
}