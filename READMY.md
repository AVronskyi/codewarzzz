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
 function reverseList(list) {л
   let a = [];
   for (let i = list.length -1; i >= 0; i--){
   a.push(list[i]); 
   }
   return a
 }
 ```
 *new solution