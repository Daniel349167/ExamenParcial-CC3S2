# ExamenParcial-CC3S2


## Parte2
![image](https://github.com/Daniel349167/ExamenParcial-CC3S2/assets/62466867/23316343-cd5f-4c90-b0da-07b5f666679e)

 ![image](https://github.com/Daniel349167/ExamenParcial-CC3S2/assets/62466867/4e13725c-62f7-4691-96df-b6f2e268d895)

 ![image](https://github.com/Daniel349167/ExamenParcial-CC3S2/assets/62466867/bfa01a81-f590-4eb5-b2a0-569d3deb601a)

![image](https://github.com/Daniel349167/ExamenParcial-CC3S2/assets/62466867/d9546909-9606-4329-b7c9-d1d42dc0d0d4)

### 1. ¿Qué está pasando con rails generate scaffold todo description:string?

Este comando realiza varias tareas:

Crea un modelo llamado "Todo" con un atributo "description" de tipo "string".
Crea un controlador "TodosController" con métodos para manejar operaciones CRUD.
Genera vistas para las operaciones CRUD.
Crea una migración que define cómo crear la tabla "todos" en la base de datos.

![image](https://github.com/Daniel349167/ExamenParcial-CC3S2/assets/62466867/940e4925-327e-4962-a2e1-c7e13b2b60ba)

### 2. ¿Qué hace bundle exec rake db:migrate?
Ejecuta las migraciones de la base de datos que aún no se han aplicado. En el caso de esta aplicación, creará una nueva tabla llamada "todos" con una columna "description".
![image](https://github.com/Daniel349167/ExamenParcial-CC3S2/assets/62466867/c9f3ed61-6fac-48c9-bbb4-f27e91bf2ee2)


### 3.Agregar Migración fecha de vencimiento
![image](https://github.com/Daniel349167/ExamenParcial-CC3S2/assets/62466867/abc1c873-3289-4c45-b76a-bd98f076f577)

### 4. Nuevas rutas y acción del controlador
![image](https://github.com/Daniel349167/ExamenParcial-CC3S2/assets/62466867/dae6baad-6a35-48fc-bc80-931e258cc401)
![image](https://github.com/Daniel349167/ExamenParcial-CC3S2/assets/62466867/b23fa45b-8444-48f8-9193-af84af6880d1)

- resultado:

![image](https://github.com/Daniel349167/ExamenParcial-CC3S2/assets/62466867/816f7482-f289-4265-b735-269bcc253c10)
![image](https://github.com/Daniel349167/ExamenParcial-CC3S2/assets/62466867/fa44a442-e618-46ad-ba50-ffd71b026e03)

### Preguntas:
- Agrega un nuevo atributo al modelo Todo y actualiza las vistas para mostrar y editar el nuevo campo. Para propósitos de práctica digamos que queremos agregar un nuevo campo booleano llamado "done" con un valor predeterminado de falso.
![image](https://github.com/Daniel349167/ExamenParcial-CC3S2/assets/62466867/4c0989eb-ac04-407c-bd7a-9e213b158752)
![image](https://github.com/Daniel349167/ExamenParcial-CC3S2/assets/62466867/1479e974-ae56-4390-b231-1f47040d0a0e)
![image](https://github.com/Daniel349167/ExamenParcial-CC3S2/assets/62466867/c4c03069-8a9b-4ae2-b190-c68b4028c00c)
![image](https://github.com/Daniel349167/ExamenParcial-CC3S2/assets/62466867/7c482ff6-03ef-45eb-b87e-d84bbb23b619)



- Cambia el esquema de enrutamiento. Debes suponer que queremos una nueva ruta new_todo para ir a una página que crea un nuevo ítem Todo
![image](https://github.com/Daniel349167/ExamenParcial-CC3S2/assets/62466867/209418ce-f8a6-475a-87b3-378c56e3ff47)
![image](https://github.com/Daniel349167/ExamenParcial-CC3S2/assets/62466867/015824df-0b56-45d1-9f92-f25e2b856d6a)

- Establece todos#index como la página de inicio de la aplicación.
![image](https://github.com/Daniel349167/ExamenParcial-CC3S2/assets/62466867/ee4766ff-2d9c-4270-b42f-4a707c533dc5)

- Enumera todas las migraciones. ¿Cuál es el comando para volver a una versión anterior de la base de datos? Muestra los resultados.
![image](https://github.com/Daniel349167/ExamenParcial-CC3S2/assets/62466867/18c1a833-2820-4797-a519-8a818f10f5eb)

El comando es:
```shell
rails db:migrate:down VERSION=numero_de_version
```

![image](https://github.com/Daniel349167/ExamenParcial-CC3S2/assets/62466867/0e8142b7-3003-4f2e-bd73-968dd0dc1fcf)









 
 
 
 
 
