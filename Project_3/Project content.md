 Задачи проекта : 
1. Составить приемочный тест - кейс для продукта [ToDo List](https://sky-todo-list.herokuapp.com/)
2. Составить коллекцию в Postman для приемочного ТК
3. Создайть заглушку для двух операций Todo-приложения:
   - На получение списка  задач должен возвращаться массив из 3 и более задач.
   - На создание задачи  должен возвращаться UUID новой задачи: в тело ответа нужно вписать "id": "{{faker 'datatype.uuid'}}” — эта строка сообщит Mockoon, что нужно  использовать генератор данных (datatype) и подставить рандомный UUID.

  ---
  Документация проекта :
   - Приемочный [тест - кейс](https://docs.google.com/spreadsheets/d/13p9S8zqcwzTZ3-FcWgr12GGeLUkLYaFfKDshi44NFpA/edit?usp=sharing )
  #### Postman collection :
-  получить список задач   [List Tasks](https://drive.google.com/file/d/1UVqBw3BOxsfevs2iUJDIxu2Tglv6ZMRW/view?usp=sharing/)
-  добавить задачу [Add Task](https://drive.google.com/file/d/1kRywm6E3fvbyOEawaamZKA4c7k2Dr8sd/view?usp=sharing/)
-  получить список задач [List_Tasks](https://drive.google.com/file/d/1PZs2ynWfmurioMYHNMB5-d7nBKEo03sq/view?usp=sharing)
-   проверить через [UI](https://drive.google.com/file/d/1pbYEELYvV2f_0ZvUl_ACWXxfhpFyRKGf/view?usp=sharing/)
-   удалить задачу [Delete_Task](https://drive.google.com/file/d/1z0wcCS7JhY_ty9a1k3Vfq8Oy5qcgeqhy/view?usp=sharing/)
-   получить список задач [List_Tasks](https://drive.google.com/file/d/1lGioLdKbrco8QxdeMxkANBLGQqoFoM9u/view?usp=sharing/)
-   проверить через [UI](https://drive.google.com/file/d/10CLnNKQVXeA2Ogv4Zn0lx_4KNl6hrHI4/view?usp=sharing/)

#### Mockoon заглушки : 
- получение списка задач [Mockoon](https://drive.google.com/file/d/1DvyYkGWRMyv0vId7Qc-3y23PwgwrN_R1/view?usp=sharing/)
  - запрос в Postman [List](https://github.com/Igor-Maltcev/QA-tester/assets/135959728/c41f2110-09d4-4976-9e45-8d228a44971d)
/)
