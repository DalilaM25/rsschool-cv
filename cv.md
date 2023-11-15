# Darya Mikhaylova

## Contacts

- Location: Tomsk, Russia
- Phone: +7 9016102511
- Email: melissa25.dm@gmail.com
- GitHub: [DalilaM25](https://github.com/DalilaM25)

## About Me

I improved my soft skills while working in sales. I always wanted to connect my life with front-end development. There is great motivation to learn and now apply hard skills.

## Skills

* HTML (Basic)
* CSS (Basic)
* JavaScript (Elementary)
* Git

## Code Example

```JavaScript
function calculator(string) {
    string = string.toUpperCase();
    let arr = string.split(' ');
    let a, b, resA, resB;

  let arab = [1,2,3,4,5,6,7,8,9,10];
  let roman = ['I','II','III','IV','V','VI','VII','VIII','IX','X'];

  let romanToArab0 = (array) => {
    for (let i = 0; i <= roman.length; i+=1) {
      if ( array[0] == roman[i] ) {
          resA = arab[i];
      } else if (array[2] == roman[i]) {
          resB = arab[i];
      }
    }
  };
  romanToArab0(arr);
  console.log(resA, resB);

  if (resA == undefined) {
       a = Number(arr[0])
  } else {
       a = Number(resA)
  };


  if (resB == undefined) {
      b = Number(arr[2])
  } else {
      b = Number(resB)
  };

  function checkNumbers(a, b, arr) {
      if (!(Number.isInteger(a)) || !(Number.isInteger(b)) ||
      a > 10 || b > 10 ||
      a < 1 || b < 1) {
      throw new Error('Ошибка проверки на целостность или диапазон');
     } else if(arr.length > 3) {
      throw new Error('Ошибка проверки на количество операндов');
     }
    }

         switch (arr[1]) {
           case '+':
             result = a + b;
             break;
           case '-':
             result = a - b;
             break;
           case '*':
             result = a * b;
             break;
           case '/':
             result = parseInt(a / b);
             break;
             default:
              throw new Error('Ошибка проверки знаков операций')
     }
     return (result);
       }
```

## Experience

## Education

University: Tomsk Polytechnic University, Biotechnology Master’s Degree (2018)

## Courses:

Yandex Practicum "Frontend developer" (in progress)

## English

A2 (Understand technical documentation)
