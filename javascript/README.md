# Javascript Coding Style

以下的內容大部分參考 [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)

## 空白

  - 使用四個空白來縮排
  
    ```javascript
    function() {
    ∙∙∙∙var name;
    }
    ```
    
  - 將空白放在左大括號之前
  
    ```javascript
    // bad
    function test(){
        console.log('test');
    }

    // good
    function test() {
        console.log('test');
    }
    ```
    
  - 等號兩邊要有空白
  
    ```javascript
    // bad
    var x=y+5;

    // good
    var x = y + 5;
    ```

## 逗號

  - 不要將逗號放在前面
  
    ```javascript
    // bad
    var once
      , upon
      , aTime;

    // good
    var once,
        upon,
        aTime;

    // bad
    var hero = {
        firstName: 'Bob'
      , lastName: 'Parr'
      , heroName: 'Mr. Incredible'
      , superPower: 'strength'
    };

    // good
    var hero = {
        firstName: 'Bob',
        lastName: 'Parr',
        heroName: 'Mr. Incredible',
        superPower: 'strength'
    };
    ```

## 分號

  - 每一個 expression 或 statement 最後一定要加上分號
  
    ```javascript
    // bad
    (function() {
         var name = 'Skywalker'
         return name
    })()

    // good
    (function() {
         var name = 'Skywalker';
         return name;
    })();
    ```

## 字串

  - 使用單引號來組成字串
  
    ```javascript
    var name = 'John Doe';
    ```

## 變數

  - 宣告變數時，前面一定要加上 var
  
    ```javascript
    // bad
    superPower = new SuperPower();

    // good
    var superPower = new SuperPower();
    ```
