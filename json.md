## JSON对象

* 方法

```js
JSON.stringify()   
//用于将一个值转为字符串。该字符串应该符合JSON格式，并且可以被JSON.parse方法还原。
//（JSON.stringify(obj, selectedProperties)）还可以接受一个数组，作为第二个参数，指定需要转成字符串的属性。
//还可以接受第三个参数，用于增加返回的JSON字符串的可读性。如果是数字，表示每个属性前面添加的空格（最多不超过10个）；如果是字符串（不超过10个字符），则该字符串会添加在每行前面。

JSON.parse()   //用于将JSON字符串转化成对象。

```


