
# Junior Developer Resume

1. **First Name, Last Name:**  
Juliana, Sadovskaya
2. **Contact Info** *(everal ways to contact you)***:**  
juliana.sad07@gmail.com
3. **Summary** *(your goal, wishes, reveal what is important for you, what do you want and why. Some kind of self-presentation. In case of lack of experience  Junior Developer sells his/her potential, his/her passion and ability to learn fast. You shouldn't think that everybody is going to teach you when you come to the workplace. Rather being a Junior means always learning new things from everywhere etc.)***:**  
Promising, quickly trained, active
4. **Skills** *(e.g. programming languages, frameworks, methodologies, version control, tools etc.)***:**  
CSS, HTML, JavaScript
5. **Code examples** *(LATEST)***:**  


* **Kata**:  
Count characters in your string  
**Solution**:  
```javascript
function count (string) {  
  const arrSort = string.split('').sort();
  let result = {};
  let count = 1;
  if (string.length !== 0) {
    for (let i = 1; i < string.length; i++){
      if (arrSort[i] === arrSort[i - 1]){
        count++;
      } else {
        result[arrSort[i-1]] = count;
        count = 1;
      }
    }
    result[arrSort[string.length-1]] = count;
  }
   return result;
}
```

* **Kata**:  
Is a number prime?  
**Solution**:  
```javascript
function isPrime(num) {
  let a = 0;
  if (num <= 1){
    a = 0;
  } else if (num === 2 || num === 3){
    a = 1;
  } 
  if(num > 2){
    for (let i = 2; i <= Math.sqrt(num); i++){
      if (num % i) {
        a = 1;
      } else {
        a = 0;
        break;
      }
    }
  } 
  return !!a;
}
```

* **Kata**:  
Currying functions: multiply all elements in an array  
**Solution**:  
```javascript	
function multiplyAll (arr) {
  return function(n) {
    return arr.map((cur) => cur * n);
  }
}
```

6. **Experience** *(for a Junior Dev it means all kinds of experience: coding tests, projects from courses, freelance projects - wherever they had the opportunity to demonstrate skills they have. Also it would be awesome if you add links to source code)***:**  
[Codecademy](http://codecademy.com) (CSS, HTML, JavaScript), [Codewars](http://codewars.com) (6 kyu)
7. **Education** *(including courses, seminars, lectures, online learning)***:**   
BSU, Mechanic and Mathmatic faculty, specialist
8. **English** *(elaborate on what kind of practice you had, if any, how long it lasted and so on)***:**   
A2