# Labwork No. 6

Hi there! This repo is intented for Labwork No. 6 Of Computer Architecture-2 discipline.

Let's test the program by setting  parameter 't' to 4:

![](https://github.com/danilos1/AK_Lab6/blob/main/img/t_4.png)

As we can see, there are time of execution in ns of print command.

This works with two modules: hello1.c and hello2.c (and hello.h, which is the header of hello1.c module), since it is an ```advanced``` task.

Finally, let's check all of three files(hello1.c, hello2.c and hello1.h) using the following command:
```
$KDIR/scripts/checkpatch.pl -f <file_name>
```

The results are showed in the table:

| File name | The result of check |
|--         |--                   |
| ```hello1.h``` |![](https://github.com/danilos1/AK_Lab6/blob/main/img/checkpatch_hello_h.png)|
| ```hello1.c``` |![](https://github.com/danilos1/AK_Lab6/blob/main/img/checkpatch_hello1_c.png)|
| ```hello2.c``` |![](https://github.com/danilos1/AK_Lab6/blob/main/img/checkpatch_hello2_c.png)|


