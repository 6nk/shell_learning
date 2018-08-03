##  环境变量

设置全局变量的方法：先创建局部变量，然后导出到全局环境中，使用export命令

- my_variable="I am Global now"
- export my_variable

修改子shell中全局变量的值并不会影响到父shell中该变量的值，但可以影响子shell的子shell中的值