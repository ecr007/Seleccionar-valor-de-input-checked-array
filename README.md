# Seleccionar-valor-de-input-checked-array

```

var searchIDs = $(".ecr-select-ebl:checkbox:checked").map(function(){
      return $(this).val();
    }).get(); // <----
    console.log(searchIDs);
```
