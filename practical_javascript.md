## Interlude - Functions inside of functions
```
var students = ['jone', 'john', 'jane'];
students.forEach(function(name){
  console.log(name);
  })

```

.forEach is a function on array
编程思想 **.forEach is a function that enhances other functions**

function forEach(myArray, myFunction){
  for (var i=0; i<myArray.length; i++){
    myFunction(myArray[i]);
  }
}
