![](https://avatars.dzeninfra.ru/get-zen_doc/5285564/pub_610aa8233795427f963ba8de_610ac2a6d1ab86792551d508/scale_1200 
)
<span style="color: yellow; font-size: 100px; font-weight: 900;">Java</span>
<span style="color: white; font-size: 100px; font-weight: 900; ">-Script</span>

JavaScript — мультипарадигменный язык программирования. Поддерживает объектно-ориентированный, императивный и функциональный стили. Является реализацией спецификации ECMAScript (стандарт ECMA-262).

JavaScript обычно используется как встраиваемый язык для программного доступа к объектам приложений. Наиболее широкое применение находит в браузерах как язык сценариев для придания интерактивности веб-страницам.

Основные архитектурные черты:

динамическая типизация;

слабая типизация;

автоматическое управление памятью;

прототипное программирование;

функции как объекты первого класса.

![Alt-текст](https://teachandstudy.ru/media/uploads/course_logo/EzgdmaCQuT84bgDL4fhXZS.jpg
 "Заголовок изображения")

![](https://open.zeba.academy/wp-content/uploads/2020/01/JavaScript-vs-Java.png )


# Что такое `JavaScript`?


Java Script это динамический язык программирования и он пока что единственый часто используемый язык для front-end разработчиков. 

JavaScript был создан в `1995` году и с тех пор стал одним из самых популярных языков программирования в мире. Он является основным языком для веб-разработки на стороне клиента, что означает, что он работает прямо в браузере пользователя.

# Основы JavaScript

В Java Script переменные можно объявить с помощью ключевых слов `var`, `let` или `const`.

```javascript
let name = 'John';
const age = 30;
```

# Типы данных


## JavaScript: Примитивы и Объекты

### Примитивы

В JavaScript существует 7 типов примитивных данных:

*1.* **Number**: представляет числовые значения, например, `24`, `24.50` и т.д.

*2.* **String**: представляет последовательность символов, например, `"hello"`, `"world"` и т.д.

*3.* **Boolean**: представляет логическое значение: `true` или `false`.

*4.* **Undefined**: представляет неопределенное значение.

*5.* **Null**: представляет нулевое значение.

*6.* **Symbol**: представляет уникальное значение, которое не равно любому другому значению.

*7.* **BigInt**: представляет целые числа произвольной точности.

## Объекты

Объекты в JavaScript могут быть определены как набор пар ключ-значение. Ключи в объекте являются строками, а значения могут быть любого типа, включая другие объекты. Это позволяет создавать сложные структуры данных.


Пример объекта:


```javascript
let SpiderMan = {
  name: "Pit",
  age: 20,
  isGraduated: true
}; 
```
-------------

JavaScript имеет несколько основных типов данных:

`Number`: для чисел любого типа: целочисленные значения, числа с плавающей точкой, etc.

`String`: для строк. Строка может быть объявлена с помощью одинарных или двойных кавычек.

`Boolean`: для true и false.

`Object`: для более сложных структур данных.

`Array`: для упорядоченных списков данных.

# Функции 

Функции в JavaScript можно определить с помощью ключевого слова `function`:

```javascript
function greet(name) {
  return 'Hello, ' + name;
}
```


# Разница frontend и backend

 ![Alt-текст]( https://professii-online.ru/wp-content/uploads/frontend-i-backend.png
 "Заголовок изображения")

Frontend
Frontend, также известный как “клиентская сторона”, относится к тому, что пользователь видит и взаимодействует непосредственно. Это все, что отображается в браузере пользователя: текст, стили, изображения, кнопки, формы и т.д.

Основные технологии, используемые в frontend-разработке, включают HTML, CSS и JavaScript.

Backend
Backend, или “серверная сторона”, относится к тому, что происходит за кулисами. Это сервер, где хранятся данные, происходит обработка запросов, выполняется бизнес-логика и т.д.

Backend-разработчики используют различные языки программирования, такие как Java, Python, Ruby, Node.js, PHP и другие. Они также работают с базами данных, такими как MySQL, PostgreSQL, MongoDB и т.д.

Взаимодействие Frontend и Backend
Frontend и backend взаимодействуют друг с другом с помощью HTTP-запросов и ответов. Когда пользователь выполняет действие на веб-странице (например, нажимает кнопку), frontend отправляет запрос на backend. Затем backend обрабатывает этот запрос, взаимодействует с базой данных при необходимости, и отправляет ответ обратно на frontend, который обновляет веб-страницу в соответствии с полученными данными.

В общем, frontend отвечает за то, как сайт выглядит и взаимодействует с пользователем, а backend - за обработку данных и выполнение бизнес-логики. Оба эти компонента важны для создания полноценного веб-приложения.



# Какие есть типы данных в `JS` ?
![Alt-текст](https://miro.medium.com/v2/resize:fit:1400/1*l_ZDRMLFUVaIO38p9Qkzvw.jpeg "Заголовок изображения")


В JavaScript существует восемь типов данных: числа (number), строки (string), логические значения (boolean), null (отсутствие значение), undefined (не определенное значение), большие числа (BigInt), а также объект (object) и символ (symbol).

`Number — число`

`String — строка`


`Boolean — логическое значение (true/false)`

`Undefined — специальное значение undefined`

`Symbol — символ`

`BigInt — предназначен для представления очень больших целых чисел`

`Null — представляет одно специальное значение — null (отсутствие значения)`

`Object — комплексный объект`





# Виды функций

## `Declaration and Expression`
![](https://cf.ppt-online.org/files1/slide/a/aUFst5BldgikR8YOwzPCpjLHof0q7GZ9vE4XIQ/slide-23.jpg)



### `example of declaration: `

Функции Declaration, или объявление функций, определяются с использованием ключевого слова function, за которым следует имя функции. Вот пример функции Declaration:

```javascript
function greet(name) {
  return 'Привет, ' + name;
}
```


### `example of expression: `

Функции Expression, или выражения функций, определяются путем присвоения анонимной функции переменной. Вот пример функции Expression:

```javascript
let greet = function(name) {
  return 'Привет, ' + name;
};
```


Разница между `Declaration и Expression`
Основное различие между функциями Declaration и Expression заключается в том, что функции Declaration поднимаются и могут быть вызваны до того, как они были объявлены, в то время как функции Expression не могут быть вызваны до того, как они были определены.

`Оба типа функций могут быть полезны в разных ситуациях, и выбор между ними зависит от конкретных требований вашего кода.`



## Hoisting - Поднятие

Поднятие или `hoisting` — это механизм в JavaScript, в котором переменные и объявления функций, передвигаются вверх своей области видимости перед тем, как код будет выполнен.


![Alt-текст](https://miro.medium.com/v2/resize:fit:828/format:webp/1*ZlSOYK-1a0GvSrfX0b6YeA.png "Заголовок изображения")

# Scopes

![](https://avatars.mds.yandex.net/i?id=a2a13124d02bac0a327790e4181f118a7a1cf0e1-9067973-images-thumbs&n=13 )

`*Область видимости – это некоторая сущность JavaScript, которая определяет границы действия переменных.*`

Виды scope в JS

4 вида: 

Global scope - к примеру у нас есть функция а снаружи в main() написан допустим let b мы можем его вызвать потому что оно глобальное для функций

Function scope
допустим у нас есть let b в функции и мы в main() не можем его вызвать потому что это так не работает и невозможно.


Block scope = condition and loop

Module scope = ??

![](https://miro.medium.com/v2/resize:fit:1400/1*KxHwVbB0zhnSVrhrWtT-gg.jpeg )

var = function scope


hoisted: 

let and cost когда мы их вызываем за раннее то происходит технически хоистинг и одновременно нет они попадают в tdz мертвая зона 

var = cout : undefined

функция declaration можно вызвать без проблем но это хоистинг

# `Examples of scopes` 

```javascript
// глобальная переменная
let a = 5;
{
  // локальная переменная
  let b = 17;
}
```


```javascript
if (true) {
  // локальная переменная
  let b = 17;
  // выведем значение переменной b в консоль
  console.log(b); // 17
}
console.log(b); // Uncaught ReferenceError: b is not defined
```

```javascript
// глобальная область видимости
function salute(welcomeText) {
  console.log(welcomeText);
}

salute('Привет'); // вызов функции salute
salute('Здравствуйте'); // вызов функции salute
```
---

В JavaScript, строки представляются как объекты `String`, и у них есть множество полезных методов. Вот некоторые из них:

- **length**: Это свойство возвращает длину строки.
```javascript
let str = 'Hello, world!';
console.log(str.length);  // Вывод: 13
```

- **charAt()**: Этот метод возвращает символ в указанной позиции.
```javascript
let str = 'Hello, world!';
console.log(str.charAt(0));  // Вывод: 'H'
```

- **indexOf()**: Этот метод возвращает индекс первого вхождения указанной подстроки в строке.
```javascript
let str = 'Hello, world!';
console.log(str.indexOf('world'));  // Вывод: 7
```

- **substring()**: Этот метод возвращает подстроку между двумя указанными индексами.
```javascript
let str = 'Hello, world!';
console.log(str.substring(7, 12));  // Вывод: 'world'
```

- **slice()**: Этот метод возвращает новую строку, извлеченную из строки с использованием начального и конечного индекса.
```javascript
let str = 'Hello, world!';
console.log(str.slice(7, 12));  // Вывод: 'world'
```

- **split()**: Этот метод разделяет строку на массив подстрок.
```javascript
let str = 'Hello, world!';
console.log(str.split(' '));  // Вывод: ['Hello,', 'world!']
```

- **replace()**: Этот метод заменяет указанное значение на другое.
```javascript
let str = 'Hello, world!';
console.log(str.replace('world', 'JavaScript'));  // Вывод: 'Hello, JavaScript!'
```

- **toUpperCase()** и **toLowerCase()**: Эти методы преобразуют строку в верхний или нижний регистр соответственно.
```javascript
let str = 'Hello, world!';
console.log(str.toUpperCase());  // Вывод: 'HELLO, WORLD!'
console.log(str.toLowerCase());  // Вывод: 'hello, world!'
```
-----
# `Examples: `
```javascript
let str = 'hello';
console.log(str.charAt(str.length - 1));
console.log(str.charAt(1));


let str = 'hello';
console.log(str.at(-1));
console.log(str.at(1));



let str1 = 'hello';
let str2 = 'world';
let res = str1.concat(str2);
let res2 = str1.concat(' s1lvack ');
let res2 = str1.concat('    ', s1lvack ');
console.log(res2);
console.log(res);


let str = 'Qadami Qurbon';
let str4 = 'Qadami Qurbon Qadami Qurbon Qadami Qurbon Qadami Qurbon'
let str2 = str.replace('Qurbon', 'Bilol')
let str3 = str4.replaceAll('Qurbon', 'Bilol')


console.log(str2);
console.log(str3);



let str = 'Lorem ipsum dolor';

let arr = str.split('');

let arr2 = str.split(' ');
let arr3 = str.split();

console.log(arr);
console.log(arr2);
console.log(arr3);




let str = 'lorem ipsum dolor ipsum';
let sub = str.substring(0,5); // minusa kabul namekna
let sub2 = str.slice(-5); // minusa kabul mekn
console.log(sub);

console.log(sub2);


let str = 'lLorem ipsum LOOROROR dolor ipsum';

console.log(str.toUpperCase());


console.log(str.toLowerCase());


let str = '                             lLorem ipsum LOOROROR dolor ipsum                    ';

console.log(str.trim());


let str = 'lLorem ipsum LOOROROR dolor ipsum';
console.log(str.includes('lLorem'));


let str = 'Hello';
console.log(str.repeat(3));


```



# Math.floor()

Это такой математический метод который убирает число с остатком
## example

```javascript

if(a == 0.12){
  a = 0;
}

```



# Math.round()

Этот математический метод округляет число если остаток достигает 5 или превышяет 

## example

```javascript

if(a == 0.5){
  a = 1;
}

```


# Math.ceil()

Этот математический метод всегда округляет вверх и возвращает наименьшее целое число, которое больше или равно данному числу

```javascript
let a = Math.ceil(0.60); // a будет равно 1
let b = Math.ceil(0.40); // b будет равно 1
let c = Math.ceil(5);    // c будет равно 5
let d = Math.ceil(5.1);  // d будет равно 6
let e = Math.ceil(-5.1); // e будет равно -5
let f = Math.ceil(-5.9); // f будет равно -5

```

![](https://i.ytimg.com/vi/s3O5uHHPuRA/maxresdefault.jpg )

# <span style='font-size: 90px;'> `Массивы в JavaScript`</span>


## Определение

Массив в JavaScript - это высокоуровневый объект, похожий на список, который может содержать элементы любого типа.

```javascript
let array = [1, 2, 3, 4, 5];

```



# push()

```javascript
array.push(6); // array становится [1, 2, 3, 4, 5, 6]

```




# pop()

```javascript
array.pop(); // возвращает 6, array становится [1, 2, 3, 4, 5]

```

# concat()
Метод concat() используется для объединения двух или более массивов. Этот метод не изменяет существующие массивы, а вместо этого возвращает новый массив.


```javascript
let arr1 = [1, 2, 3];
let arr2 = [4, 5, 6];
let arr3 = arr1.concat(arr2);
console.log(arr3); // [1, 2, 3, 4, 5, 6]
```

# slice()
Метод slice() в JavaScript используется для извлечения части массива и создания нового массива, не изменяя исходный. Вот пример использования:


```javascript
let arr = [1, 2, 3, 4, 5];
let arr2 = arr.slice(1, 3);
console.log(arr2); // [2, 3]
```

# forEach()
Метод forEach() выполняет указанную функцию один раз для каждого элемента в массиве.


```javascript
let arr = [1, 2, 3, 4, 5];
arr.forEach(function(item, index, array) {
  console.log(item); // выводит каждый элемент массива
});
```

# map()
Метод map() создает новый массив с результатами вызова указанной функции для каждого элемента исходного массива.


```javascript
let arr = [1, 2, 3, 4, 5];
let arr2 = arr.map(function(item, index, array) {
  return item * 2; // удваивает каждый элемент массива
});
console.log(arr2); // [2, 4, 6, 8, 10]
```

# find()
Метод find() возвращает первый элемент в массиве, который удовлетворяет предоставленному условию. Если ни один элемент не удовлетворяет условию, возвращается undefined.


```javascript
let arr = [1, 2, 3, 4, 5];
let found = arr.find(function(element) {
  return element > 3;
});
console.log(found); // 4
```

# filter()
Метод filter() создает новый массив со всеми элементами, которые проходят тест, предоставленный в виде функции.


```javascript
let arr = [1, 2, 3, 4, 5];
let filtered = arr.filter(function(item) {
  return item > 3;
});
console.log(filtered); // [4, 5]
```

# reduce()
Метод reduce() применяет функцию к аккумулятору и каждому значению массива (слева направо), чтобы свести его к одному значению.



```javascript
let arr = [1, 2, 3, 4, 5];
let sum = arr.reduce(function(accumulator, currentValue) {
  return accumulator + currentValue;
});
console.log(sum); // 15
```

# sort()
Метод sort() сортирует элементы массива на месте и возвращает массив. Сортировка не обязательно устойчива. По умолчанию сортировка происходит в лексикографическом порядке.



```javascript
let arr = [1, 10, 5, 2];
arr.sort();
console.log(arr); // [1, 10, 2, 5]
```
```javascript
let arr = [1, 10, 5, 2];
arr.sort(function(a, b) {
  return a - b;
});
console.log(arr); // [1, 2, 5, 10]
```

# includes()

Метод includes() определяет, содержит ли массив определенный элемент, возвращая в ответе true или false.



```javascript
let arr = [1, 2, 3, 4, 5];
console.log(arr.includes(2)); // true
console.log(arr.includes(6)); // false
```

# join()

Метод join() объединяет все элементы массива в строку. Элементы разделяются указанным разделителем. Если разделитель не указан, элементы разделяются запятой.



```javascript
let arr = ['Hello', 'World'];
console.log(arr.join()); // 'Hello,World'
console.log(arr.join(' ')); // 'Hello World'
console.log(arr.join('-')); // 'Hello-World'
```

# indexOf()
Метод indexOf() возвращает первый индекс, по которому данный элемент может быть найден в массиве, или -1, если такого индекса нет.

```javascript

let arr = [1, 2, 3, 4, 5];
console.log(arr.indexOf(3)); // 2
console.log(arr.indexOf(6)); // -1


```

# splice()
Метод splice() в JavaScript используется для изменения содержимого массива путем удаления, замены или добавления элементов. Вот пример использования:


```javascript
let arr = [1, 2, 3, 4, 5];
arr.splice(2, 1); // начиная с позиции 2, удалить 1 элемент
console.log(arr); // [1, 2, 4, 5]

arr.splice(2, 0, 3); // начиная с позиции 2, не удалять элементы, добавить 3
console.log(arr); // [1, 2, 3, 4, 5]

```

# toString()
Метод toString() преобразует объект в строку.



```javascript
let num = 123;
console.log(num.toString()); // "123"

```
# toReversed()
Хотя в JavaScript нет встроенного метода toReversed(), вы можете легко создать свою функцию для переворачивания строки:


```javascript
function toReversed(str) {
  return str.split('').reverse().join('');
}

console.log(toReversed("Hello")); // "olleH"

```

# `*Нахождение по массиву*`

```javascript
for(let i = 0; i < array.length; i++) {
    console.log(array[i]);
}

array.forEach(element => console.log(element));

```


![Alt-текст](https://fuzeservers.ru/wp-content/uploads/a/5/3/a53d6fb9fa7dbfda81a1e48b7613bc82.png "Заголовок изображения")


# push() example

![Alt-текст](https://miro.medium.com/v2/resize:fit:948/0*AVR2-oiS_HQQd2PI.png "Заголовок изображения")


# Объекты в JavaScript

Объект в JavaScript - это неупорядоченная коллекция свойств, состоящая из пар ключ-значение.

## Создание объекта

Объект можно создать с помощью фигурных скобок `{...}`:

```javascript
let user = {}; // пустой объект

user.name = "John"; // добавляет свойство "name" со 

значением "John"

user.age = 30; // добавляет свойство "age" со значением 30


alert(user.name); // "John"

alert(user["age"]); // 30
```
```javascript

let user = {};

user.name = "John"; // добавить свойство

let name = user.name; // прочитать 
свойство

delete user.name; // удалить свойство

"name" in user; // проверить на наличие свойства
```

# <span style='font-size: 90px;'> `Callbacks`</span>

# forEach()
Метод forEach() выполняет указанную функцию один раз для каждого элемента в массиве.


```javascript
let arr = [1, 2, 3, 4, 5];
arr.forEach(function(item, index, array) {
  console.log(item); // выводит каждый элемент массива
});
```

# map()
Метод map() создает новый массив с результатами вызова указанной функции для каждого элемента исходного массива.


```javascript
let arr = [1, 2, 3, 4, 5];
let arr2 = arr.map(function(item, index, array) {
  return item * 2; // удваивает каждый элемент массива
});
console.log(arr2); // [2, 4, 6, 8, 10]
```

# find()
Метод find() возвращает первый элемент в массиве, который удовлетворяет предоставленному условию. Если ни один элемент не удовлетворяет условию, возвращается undefined.


```javascript
let arr = [1, 2, 3, 4, 5];
let found = arr.find(function(element) {
  return element > 3;
});
console.log(found); // 4
```

# filter()
Метод filter() создает новый массив со всеми элементами, которые проходят тест, предоставленный в виде функции.


```javascript
let arr = [1, 2, 3, 4, 5];
let filtered = arr.filter(function(item) {
  return item > 3;
});
console.log(filtered); // [4, 5]
```

# reduce()
Метод reduce() применяет функцию к аккумулятору и каждому значению массива (слева направо), чтобы свести его к одному значению.



```javascript
let arr = [1, 2, 3, 4, 5];
let sum = arr.reduce(function(accumulator, currentValue) {
  return accumulator + currentValue;
});
console.log(sum); // 15
```

# sort()
Метод sort() сортирует элементы массива на месте и возвращает массив. Сортировка не обязательно устойчива. По умолчанию сортировка происходит в лексикографическом порядке.



```javascript
let arr = [1, 10, 5, 2];
arr.sort();
console.log(arr); // [1, 10, 2, 5]
```
```javascript
let arr = [1, 10, 5, 2];
arr.sort(function(a, b) {
  return a - b;
});
console.log(arr); // [1, 2, 5, 10]
```


-------



# <span style='font-size: 50px;'> `SPREAD & REST`</span>


# <span style='font-size: 50px;'> `DESTRUCTING`</span>

```javascript


```

-----------------------

# <span style='font-size: 50px;'> `OBJECT`</span>
## Что такое *object?*
- *Object*(объект) - это то,что мы видим.

***Object* может принимать несколько значений.*Object* состоит из *property*,а *property* состоит из ключа и *значения***.

После каждого *property* нужно ставить запятую.

# Методы *Object*
## *1.* entries()

*entries* - превращает объект в массив (*array*).

## *2.* keys()

*keys* - берёт из объекта только ключи и ставит их в массив (*array*).все ключи он делает отдельными элементами массива.

## *3.* values()

*values* - берёт из объекта только его значения и ставит их в массив (*array*).все значения (*value*) он делает отдельными элементами массива.

# *Distucturing* в *object.*

- *Distucturing* в Объктах отличается от distucturing в *array*.В нём мы прописываем ключи объекта.!Но ключи,которые мы прописываем в *distucturing* должны совпадать названиями и ключами объекта.

# *Spread*

- Если мы хотим отделить второй объект от основного,чтобы новые значения не прописывались сразу на основной,то используем *spread.* Она пишется тримя точками в круглых скобках.То есть  метод *spread* делает два одинавых объекта с разными ссылками,адрессами.

# *This*

- В *JavaScript* *this* — это ссылка на какой-то объект. Особенность в том, что объект, на который ссылается this , может меняться в зависимости от контекста вызова. Это как показать пальцем на что-то в коде и сказать *«Вот, я имею в виду вот этот объект».*
\