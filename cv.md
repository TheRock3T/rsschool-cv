## Dzmitry Rudakou

___

### Front-end Developer

___

## Contacts:

- **Phone**: +375333212247
- **Email**: dimarudakoff2001@gmail.com
- **Telegram**: https://t.me/therock3t
- **LinkedIn**: https://www.linkedin.com/in/dmitry-rudakov-78098a20a

---

## About myself:

I started learning web development in 2021.

I chose this direction because I liked to turn my fantasies into reality, at first it was very difficult to understand anything, thanks to the educational material on YouTube, then I started gaining experience thanks to small joint projects. When I failed five interviews, I didn't stop there and continued my journey of learning, as each failure made me stronger.

---

## My skills:

- HTML5
- CSS3
- SCSS
- JavaScript
- Vue JS
- Vuex
- jQuery
- Node.js
- Git, Github, BitBucket, Gitlab
- Figma
- WebStorm / PhpStorm / VSCODE
---
## Code example (codewars):
### Convert string to camel case
```javascript
function toCamelCase(str) {
  return str.split(/-|_/).map((item, index) => {
    return index < 1 ? item : item.toUpperCase().split('').map((item, index) => index < 1 ? item.toUpperCase(): item.toLowerCase()).join('')
  }).join('')
}
```

### Maximum subarray sum

```javascript
var maxSequence = function (arr) {
  if (!arr.filter(num => num > 0).length) return 0
  else {
    let maxSum = 0
    for (let i = 0; i < arr.length; i++) {
      let fixedNum = 0
      for (let z = i; z < arr.length; z++) {
        fixedNum += arr[z]
        maxSum = Math.max(maxSum, fixedNum)
      }
    }
    return maxSum
  }
}

```

### Anagram Detection

```javascript
let isAnagram = function(test, original) {
  return test.toLowerCase().split('').sort().join('') === original.toLowerCase().split('').sort().join('')
}

```

---

## Education

- Grodno State Polytechnical College - Computer systems and networks (2017-2021)

---
## Languages:

- English - A1
- Russian - Native
