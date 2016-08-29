## Return statement
if you don't return anything from a function, it will be undefined

## There should be a way to create delete buttons
view.createDeleteButton = function(){
  var elem = document.createElement('button');
  elem.textContent = "Delete";
  return elem;
}
