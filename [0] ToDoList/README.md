# ToDoList-with-Django



### 1. 메모할 내용을 적고 `메모하기!`를 누르면 아래에 메모가 적힙니다

![](C:\Users\hyesu\Desktop\1.PNG)



### 2. 완료된 메모는 `완료`를 누르면 삭제됩니다

![](C:\Users\hyesu\Desktop\2.PNG)



---





# WEB : ToDoList

- settings.py

  ​	to_do_app이라는 이름의 app을 생성합니다

![image-20200923125807700](C:\Users\hyesu\AppData\Roaming\Typora\typora-user-images\image-20200923125807700.png)

- urls.py

  처음 페이지를 to_do_app의 urls.py 로 넘겨줍니다

![image-20200923125735670](C:\Users\hyesu\AppData\Roaming\Typora\typora-user-images\image-20200923125735670.png)



# APP : to_do_app

- urls.py

  기본창, createTodo창, deleteTodo창을 생성

![image-20200923130134312](C:\Users\hyesu\AppData\Roaming\Typora\typora-user-images\image-20200923130134312.png)



- views.py

  urls.py에서 수행할 함수를 적습니다

![image-20200923130224840](C:\Users\hyesu\AppData\Roaming\Typora\typora-user-images\image-20200923130224840.png)



- models.py

  DB에 저장될  table을 지정해줍니다

![image-20200923130411401](C:\Users\hyesu\AppData\Roaming\Typora\typora-user-images\image-20200923130411401.png)

- templates > to_do_app > index.html

  - createTodo

    ![image-20200923130638131](C:\Users\hyesu\AppData\Roaming\Typora\typora-user-images\image-20200923130638131.png)

  

  - deleteTodo

    ![image-20200923130714746](C:\Users\hyesu\AppData\Roaming\Typora\typora-user-images\image-20200923130714746.png)