![errosSintatico_cmp](https://user-images.githubusercontent.com/66503956/205922331-eb3f837c-371a-49d0-8f87-affe64d9a91f.png)

### ![icon_vermelho_15](https://user-images.githubusercontent.com/66503956/205958830-c695458a-41a3-47da-b57d-8f5143a258c2.png) Exemplo 01: Falta o '|'

```c
A = 10|
B = 2|
C = 5|

ripetere(A!=0){
  stampa C|
  A = A - 1|
}

stampa A
```
#### ![icon_mau_15](https://user-images.githubusercontent.com/66503956/205960909-177b21be-a580-4a28-96c1-91e336f3a8d2.png) Print do prompt mostrando o erro do código

![erroSintatico](https://user-images.githubusercontent.com/66503956/205964794-c4dbe7b6-573a-48f8-b484-be2cdbbc364c.PNG)


![errosSemantico_cmp](https://user-images.githubusercontent.com/66503956/205922345-8533baa4-08bb-4f8b-be51-3daa738b70be.png)

### ![icon_vermelho_15](https://user-images.githubusercontent.com/66503956/205958830-c695458a-41a3-47da-b57d-8f5143a258c2.png) Exemplo 01: Divisão por zero

```c
a = 3|
b = 5|
c = 7|
d = 9|

divisao = d/0|
stampa divisao|
```

#### ![icon_mau_15](https://user-images.githubusercontent.com/66503956/205960909-177b21be-a580-4a28-96c1-91e336f3a8d2.png) Árvore sintática 

![Arvore_erroSemantico02](https://user-images.githubusercontent.com/66503956/205958362-842f94fb-1c72-41e9-8866-83cb60b350ee.PNG)

#### ![icon_mau_15](https://user-images.githubusercontent.com/66503956/205960909-177b21be-a580-4a28-96c1-91e336f3a8d2.png) Print do prompt mostrando o erro do código

![erroSemantico02](https://user-images.githubusercontent.com/66503956/205958441-23d726ef-43e7-4d37-b0a3-33c4e57c8f90.PNG)

### ![icon_vermelho_15](https://user-images.githubusercontent.com/66503956/205958830-c695458a-41a3-47da-b57d-8f5143a258c2.png) Exemplo 02: Variável recebe ela mesma

```c
a = 10|
a = a|

stampa a|
```

#### ![icon_mau_15](https://user-images.githubusercontent.com/66503956/205960909-177b21be-a580-4a28-96c1-91e336f3a8d2.png) Árvore sintática 

![Arvore_erroSemantico01](https://user-images.githubusercontent.com/66503956/205963012-afce3a71-7b53-40b6-8051-2d9464b670b7.png)

#### ![icon_mau_15](https://user-images.githubusercontent.com/66503956/205960909-177b21be-a580-4a28-96c1-91e336f3a8d2.png) Print do prompt mostrando o erro do código

![erroSemantico01](https://user-images.githubusercontent.com/66503956/205962350-8ed79b67-e50c-4f90-a3de-cbbf4fdb9cc9.PNG)

