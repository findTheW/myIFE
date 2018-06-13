1. match（）→ 在字符串内检索指定的值，或找到一个或多个正则表达式的匹配。
2. isNaN（）→ 判断是否是数字
3. **属性**是与对象相关的值，**方法**是能够在对象上执行的动作。  
   举例： 汽车的属性：car.weight=850kg，car.color=white   
          汽车的方法：car.start()，car.drive()，car.brake()  
4. **函数**是由事件驱动的或者当它被调用时执行的可重复使用的代码块。
5. 函数名（）：函数运行的结果  
   函数名：函数代码
6. 把数字与字符串相加，结果将成为字符串。例如：5+"5" = 55, "5"+5 = 55
7.  **for/in** 语句循环遍历对象的属性：  
    ``` javascript
    var person={fname:"John",lname:"Doe",age:25};  
    for (x in person)
    {
     txt=txt + person[x];
    }
    ```
8. JavaScript 标签:可以对代码块加上标签  
  ``` javascript
      cars=["BMW","Volvo","Saab","Ford"];
      list:   // 标签
      {
      document.write(cars[0]);
      document.write(cars[1]);
      break list; // 在此break，所以只会输出前面两个
      document.write(cars[2]);
      }
 ```
