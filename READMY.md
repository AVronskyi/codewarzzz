hello
 ===
 *https://www.codewars.com/kata/determine-offspring-sex-based-on-genes-xx-and-xy-chromosomes/train/javascript
 ```javascript
 function chromosomeCheck(sperm) {
   return sperm == 'XY' ? "Congratulations! You're going to have a son.": "Congratulations! You're going to have a daughter."
 }
 ```
*https://www.codewars.com/kata/thinkful-logic-drills-traffic-light/train/javascript
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
 *www.codewars.com
 ```javascript
 function spongeMeme(sentence) {
   let res = '';
   for (let i = 0; i < sentence.length; i++) {
     res += (i % 2) ? sentence[i].toLowerCase() : sentence[i].toUpperCase();
   }
   return res;
 }
 ```
 *Reverse List Order
 ```javascript
 function reverseList(list) {
   let a = [];
   for (let i = list.length -1; i >= 0; i--){
   a.push(list[i]); 
   }
   return a
 }
 ```
 *new solution
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
*
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
 *new solution
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