<!-- HEADINGS -->

# my title
## my title h2
### my title h3
#### my title h4
##### my title h5
###### my title h6

<!-- italic -->
this in an *italic* text

<!-- strong -->
this in an **strong** text

<!-- strikethrough -->
this is a ~~strikethrough~~ text

<!-- ul -->
* apple
    * apple 2
* orange
    * asadsdadssd
* etc

<!-- ol -->
1. apple
    1. apple 2
2. orange
3. etc

<!-- links -->
[faztweb.com](https://www.faztweb.com)

[faztweb.com](https://www.faztweb.com "Custom title")

<!-- Quotes -->
> this is a quote

<!-- lines -->
---
___

<!-- code -->
`console.log('hello world')`

```python
import random


def run():
    numero_aleatorio = random.randint(1, 100)
    numero_elegido = int(input('Elige un número del 1 al 100: '))
    while numero_elegido != numero_aleatorio:
        if numero_elegido < numero_aleatorio:
            print('Busca un número más grande')
        else:
            print('Busca un número más pequeño')
        numero_elegido = int(input('Elige otro número: '))
    print('¡Ganaste!')

if __name__ == '__main__':
    run()
```

```java
System.out.println("Hello World");
```

```html
<h1>Hello World</h1>
```

<!-- tables -->
| Tables        | Are           | Cool  |
| ------------- | :------------:| ----: |
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centred       |   $12 |
| zebra stripes | are neat      |    $1 |

<!-- images -->
![visual studio code logo](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/2048px-Visual_Studio_Code_1.35_icon.svg.png)

![visual studio code logo](python.png "python logo")

<!-- GITHUB MARKDOWN -->
* [X] TASK 1
* [] TASK 2
* [] TASK 3
* [] TASK 4
