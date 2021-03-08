## BELAYA KARYNA

### Contacts:
* Email: belaya.karina1998@gmail.com
* Discord:Karyna Belaya(@belayakaryna)
* Github:[belayakaryna](https://github.com/belayakaryna)

### Skills:
##### Programming Languages:
* Assembler IBM Mainframe;
* JCL;
* Java;
* SQL;
* С++;
* C;
* JavaScript;
* Bash;
* Python;
* Cobol;
* TypeScript.

##### Databases:
* DB2;
* MS SQL Server;
* Oracle;
* PostgreSQL.

##### Operating Systems:
* Windows;
* Linux;
* z/OS;
* BS2000/OSD;
* iOS;
* Android.

##### Web Technologies:
* HTML;
* CSS;
* Bootstrap;
* JSP;
* Servlets;
* Django;
* Angular;
* XML; 
* JSON.

##### Other Skills:
* TCP/IP ;
* UML;
* Visual Studio;
* Eclipse;
* Intellij IDEA;
* NetBeans;
*  PyCharm;
*  Selenium Webdriver;
*  Git;
*  Visual Studio Code.
 

### English: A2-B1

### Education and Training:

#### Education:
* Belarusian State University of Informatics and Radioelectronics, the Faculty of Engineering and Economics, Specialization in “Economics in Electronic Business”, Belarus, Minsk, 2016-2020. 

#### Training:
* IBA courses in BSUIR “DB2 for z/OS”;
* IBA courses in BSUIR “System multiplatform programming”;
* Course in Institute IBA “”Programming Fundamentals in Python”;
* Stepik course “Python programming”;
* Stepik course “Test Automation Using Python and Selenium”;
* Coursera courses “IBM z/OS Mainframe Practitioner”:
 1.“ Introduction to Enterprise Computing”
 2.“Getting Started on Mainframe with z/OS Commands and Panels”
 3.“ Basic System Programming on IBM Z”
 
### Professional experience:

 IBA IT Park: Software Engineer
January 2020-present.
*	Experienced in z/OS and BS2000/OSD operating system usage.
*	Experienced in the software testing
*	Experience in database development and administration.
*	Experienced in WebSphere.
*	Experienced in development of desktop and web applications

### Code Example:

#### JS:
```
function findShort(s){
  arr=s.split(" ")
  let m=arr[0].length
  for (let i = 0; i < arr.length; i++) {
  l=arr[i].length
  if (l<m){
    m=l
  }
  }
  return m
}
```

#### Python:

```
N1 = int(input('Введите номер строки N1 '))
N2 = int(input('Введите номер строки N2 '))
mas1 = []
mas3 = []
try:
    with open(r'D:\F1.txt', 'r', encoding='utf-8') as f:
     for line in f:
       line = line.strip()
       mas1.append(line)  # добавление строк файла в список
     mas2 = mas1[N1-1:N2-1]  # добавление в массив выбранных строк, N1-1 И N2-1 - так как номерация в списке идёт с 0, а номера строк с 1
     for i in mas2:
      if i[0] == 'А':
       mas3.append(i)
     if len(mas3)==0:
         print('Нужных строк не найдено')
     else:
      with open (r'D:\F2.txt', 'w', encoding='utf-8') as ff:
        ff.write('\n'.join(mas3))
      with open(r'D:\F2.txt', 'r', encoding='utf-8') as fff:
        l = fff.readline()
        print(len(l.split(' ')))
except FileNotFoundError:
 print('File not found')
except IOError:
 print("An IOError has occurred!")
 ```
### Summary:
I want to learn front-end development and work in this field. 
Easy to learn and always ready to learn something new.