# Recognize

__Пример кода:__
```js
captcha = new Captcha({
    key:'ваш-key'
});
captcha.recognize(data, function(err, code){
    if(err) throw err;
    console.log(code); //распознанная капча
});
```
__Получение баланса:__
```js
captcha.balanse(function(err, price){
    if(err) throw err;
    console.log(price);
});
```

__Ошибки:__
