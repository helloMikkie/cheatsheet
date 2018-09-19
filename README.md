# cheatsheet

## chrome antialiaze
```css
*{
  -webkit-font-smoothing: antialiased;
  }
```
## Text outline via css
``` css
.outline{
  color: #fff;
  text-shadow:
   -1px -1px 0 #000,
    1px -1px 0 #000,
    -1px 1px 0 #000,
     1px 1px 0 #000;
}
```
## custom fonts
```css
@font-face{
       font-family:'Lab-Grotesk';
       font-style: normal;
       font-weight: 600;
       src: url(fonts/LabGrotesque-Bold.woff2), url(fonts/LabGrotesque-Bold.woff);
   }
```
# Javascript
## random Number difference

```js
const randomNumber = function(min,max){
  return Math.floor(Math.random() * (max - min + 1)) + min
}

console.log(
  randomNumber(0,10)
  
)
```
