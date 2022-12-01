# python-exercises

Some exercises for learning python.

1. Rename file

Q1: Write a program that renames all files in a directory and its subdirectories, replacing spaces with underscores. For example, the file "My Program.py" would be renamed to "My_Program.py". Multiple consecutive spaces should be treated as a single space.

Q2: There are some pictures in the directory, and the pictures's name randomly generated. Write a program that renames all pictures in the directory. The new name is the created time of the picture. For example, "2018-01-19_12-34-56.jpg".

Q3: There are some pictures in the directory, and the pictures's name randomly generated. Write a program That renames all pictures in the directory, and the new names are like "1.jpg", "2.jpg", "3.jpg", and so on. If the total number of pictures is more than 10, the new name is like "01.jpg", "02.jpg", "03.jpg", and so on. If the total number of pictures is more than 100, the new name is like "001.jpg", "002.jpg", "003.jpg", and so on.  The order of numbers depends on the created time of the picture.

Q4: Write a program that renames a file. For example, the file "tranning-log.pdf" should be renamed to "第47届世界技能大赛网络系统管理项目训练日志-选手-郑嘉禄-2022.11.30-Linux.pdf". The frist field is fixed, and the other fields are specified by the parameters of the program when it is executed. Please check the validity of the parameters:

* The second field must be chosen between "选手" and "教练".
* The third field must be a valid chinese name.
* The fourth field must be a valid date and not later than today.
* The fifth field must be chosen from "Linux", "Windows", "Network", "English", "TS", "Other".
* All fields must be sepcified unless it has a default value.
  