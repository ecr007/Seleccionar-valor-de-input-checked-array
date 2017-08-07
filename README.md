# Seleccionar-valor-de-input-checked-array

```

var searchIDs = $(".ecr-select-ebl:checkbox:checked").map(function(){
      return $(this).val();
    }).get(); // <----
    console.log(searchIDs);
```

# Seleccionar o Deseleccionar checkbox con un boton

```
function toggle(source) {
    var checkboxes = document.querySelectorAll('input[type="checkbox"]');
    for (var i = 0; i < checkboxes.length; i++) {
        if (checkboxes[i] != source)
            checkboxes[i].checked = source.checked;
    }
}

```
