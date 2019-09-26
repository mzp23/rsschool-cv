# Vitaliy Sliusar CV

## Contact info:

- city: Dnipro
- mobile: +380734155584
- email: mzgme23@gmail.com
- telegram: amzp23

## Summary:

Well motivated to get new knowlegs in CSS HTML JS and improve old. Has experience with common front-end development tools.

## Skills:

- HTML5
- CSS3
- SASS
- JavaScript
- NPM

## Code examples:

[IP Validation Kata](https://www.codewars.com/kata/515decfd9dcfc23bb6000006) <br/>
My solution:

```javascript
function isValidIP(str) {
  const regEx = /\n| |e/g;
  if (regEx.test(str)) return false;
  let ip = str.split(".");
  if (ip.length < 4 || ip.length > 4) return false;
  let valid = ip.every(
    item => item && (item >= 0 && item <= 255) && !item.match(/^0\d{1,2}/)
  );
  return valid;
}
```
## Experience:

In most cases i'am practise on [codewars](https://www.codewars.com/users/mzp23)

## Education:

**2008-2013** Dnipropetrovsk National University of Railway Transport
  
## English level:

Pre-Intermediate