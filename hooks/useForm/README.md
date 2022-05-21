# useForm Hook

Ejemplo de uso:
```
    const initalForm = {
        name:'',
        age:0,
        email:''
    }
    const [formValues, handleInputChange, reset] = useForm(initailForm);
```

useForm() // Recibe un objeto por defecto