# useForm Hook

Ejemplo de uso:

```
    const initialForm = {
        name: '',
        age: 0,
        email: 'email@email.com'
    };
    
    const [  formValues, handleInputChange, reset ] = useForm( initialForm );
```