# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First we need to open the required the from which we need to copy the text.

### Step 2:
Using keyword "with" to open the required file.

### Step 3:
Again using the with keyword to open the empty file.

### Step 4:
The empty file is open by using 'W' which is used to write only.

### Step 5:
The for function is used to take each line from the main file

### Step 6:
Write() is used to write the lines of main file to the empty file or to the directed file.

### PROGRAM:
```
with open("text.txt","r") as f1:
    data=f1.read()
with open("data.txt","w") as f2:
    f2.write(data)
```
### text file
```
with open("text.txt",'w')as fp:
  fp.write("Hello World")
  fp.write("\nWelcome to Python")
  fp.write("\nHave a Good Day")
```
### empty file
```
with open("data.txt","w") as fd:
 fd.write("")
```
### copy file
```
with open("data.txt","r") as f2:
  data1=f2.read()
  print(data)
```
### OUTPUT:

![Screenshot 2023-12-25 140032](https://github.com/feryjfgkuyfgewjfgew/copy-file/assets/150319377/6d1eb50c-0e2f-4419-9590-ab217b118be0)

![Screenshot 2023-12-25 140053](https://github.com/feryjfgkuyfgewjfgew/copy-file/assets/150319377/5f212904-8dba-45d9-ac8c-38dccd746ec9)


```

### RESULT:
Thus the program is written to copy the contents from one file to another file.
