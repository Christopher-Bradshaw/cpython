# Cpython

* Philip Guo lectures: https://www.youtube.com/watch?v=LhadeL7_EIU&list=PLzV58Zm8FuBL6OAv1Yu6AwXZrnsFbbR0S


## Where things are

* Main interpreter loop: Python/ceval.c:916. Helpfully labelled `main_loop`.
* Include/Objects: Include has many .h files. Are the include files for the .c files in Objects. Though not a 1 to 1 mapping.
* Lib: standard library (part written in python)
