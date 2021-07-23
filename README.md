# javascript-helper-functions
---

### Filter by some keyword in the entire array

```javascript
var cities = [
    {name: 'Los Angeles', population: '3799621',child: [{id: "child-1"}]},
    {name: 'New York', population: '8175133',child: []},
    {name: 'Old York', population: '1256938',child: [{id: "child-1"}]},
    {name: 'Chicago', population: '2695598',child: [{id: "New York"}]},
    {name: 'Houston', population: '2699451',child: [{id: "child-1"}]},
    {name: 'Philadelphia', population: '1526006',child: [{id: "child-1"}]}
];
cities.filter(city => JSON.stringify(city).toUpperCase().includes('YoR'.toUpperCase()));
```

#### Answer

![image](https://user-images.githubusercontent.com/6780840/126267856-c0596f75-3ce3-46e6-a942-157b62901efa.png)

### Get keys from Array and Object
---
### For Array
```js
let myArray = ['a', 'b', 'c'];
let arrayKeys = myArray.keys();
for(const key of arrayKeys) {
  console.log(key);
}
```

 ![image](https://user-images.githubusercontent.com/6780840/126768879-883e4d4b-fb0f-4c7b-b882-f39d449e444c.png)


### For Object 

```js
 let myObject = {
   a: 'string1',
   b: 42,
   c: 34
 };

 let myKeys = Object.keys(myObject);
 console.log(myKeys);
```

![image](https://user-images.githubusercontent.com/6780840/126769697-bb19b018-15bb-4d5f-809e-a1e7c9bc84a3.png)

