# Resume

## 1. Name
   
Misha Shiryakov  

## 2. Contact info
   
+375298507430 - МТС  
[Link to VK](https://vk.com/mishaptfb)  
Email - mishashiryakov@gmail.com

## 3. Summary  
   
I would like to become a part of community that creates practically everything in our modern world.  
Learning new information every day, communication with smart people and creating useful projects  
 is my goal.

## 4. Skills  
   
   I am learning Java Script right now. Also I passed some courses on HTML&CSS.

## 5. Code examples   
   
## Is a number prime?
   
    function isPrime(num) {  
      if (num <= 1) return false;

      for(let i = 2; i <= Math.sqrt(num); i++) {  
        if (num % i == 0) return false;  
      }  
      return true;
    }

## Find The Duplicated Number in a Consecutive Unsorted List

    function findDup( arr ){  
      arr.sort(function compareNumbers(a, b) {  
        return a - b;  
      });

      for(let i = 0 ; ; i++) {  
        if (i == arr[i]) return i;  
      }
    }

## Anagram Detection

    var isAnagram = function(test, original) {  

      test = test.toLowerCase().split('').sort().join();  
      original = original.toLowerCase().split('').sort().join();  

      return (test == original) ? true : false;  
    };  

