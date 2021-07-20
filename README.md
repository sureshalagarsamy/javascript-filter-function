#### javascript-filter-function
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
