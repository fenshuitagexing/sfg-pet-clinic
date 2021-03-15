# sfg-pet-clinic
An online pet clinic built with spring framework

### 1. Create a new project

Use the built-in Spring Initializr of IntelliJ IDEA, and choose the maven dependencies as follow:

![image-20210314113238319](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20210314113238319.png)



Create a Model package, add some POJOs into it.

### 2. Refactor the project

Move the guru.springframework.sfgpetclinic.SfgPetClinicApplication.class (which has the main() method ) to the pet-clinic-web Module

Move the Model to the pet-clinic-data Module

When remodeling and clicking dragging stuff inside of IntelliJ, need to do a refresh.

(Click the Maven tab on the right side, then click the Reimport All Maven Projects)

![image-20210315072313018](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20210315072313018.png)





