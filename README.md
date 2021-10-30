# Projeto Deep Learning 2021 - Grupo Stonks
Repositório para trabalho final da disciplina de Deep Learning 2021. O projeto consiste em realizar a análise de sentimentos (raiva, alegria, tristeza ou medo) utilizando redes neurais convolucionais (CNN). A mesma análise é realizada passo a passo via CNN manual e também utilizando FastAI para que seja possível comparar os resultados, suas matrizes de confusão e acurácia.

### Problema
A Interação Homem-Computador (IHC) é o campo de conhecimento que concentra estudos de formas de evoluir e aprimorar o relacionamento entre o homem e a máquina, relacionando a ciência da computação, arte, design, linguística, semiótica, sociologia, psicologia e ergonomia para deixar interfaces mais amigáveis e tornar as
interações mais claras e ágeis,por exemplo. 

Graças aos estudos realizados na IHC e suas descobertas, pode-se hoje executar comandos em computadores, celulares, vídeo games, televisores, entre outros, seja por comando de voz, em que o usuário dita uma instrução e o dispositivo a executa, seja por gesto, em que o usuário pode movimentar partes de seu corpo como
braços, dedos ou olhos e o dispositivo reconhece este movimento como uma instrução para executar o comando.

Para contribuir com o reconhecimento de emoções, este trabalho tenta criar um modelo de identificação de raiva, medo, felicidade e tristeza através de redes convolucionais neurais.

### Integrantes
| Nome | Matrícula |
|:------------ |---|
| Rafaella Junqueira | 16/0142628 |
| Iuri Severo | 17/0145514 |
| João Victor Correia | 19/0089792 |

### Dataset

A imagens utilizadas para treinamento das Inteligências Artificais foram adquiridas das seguintes fontes:
* https://github.com/NVlabs/ffhq-dataset
* [Ebner, N., Riediger, M., & Lindenberger, U. (2010). FACES—A database of facial expressions in young, middle-aged, and older women and men: Development and validation. Behavior research Methods, 42, 351-362. doi:10.3758/BRM.42.1.351](http://hdl.handle.net/11858/00-001M-0000-0013-3A21-0)

### Apresentação realizada
[![Slides de apresentacao](https://user-images.githubusercontent.com/43728276/138556910-e7533e96-4059-45f3-8457-8134a94adb36.png)](https://docs.google.com/presentation/d/1HnIknSMhSRsGSx75BQ1MVFpz1JThKH39MdJ2troMQcU/edit?usp=sharing)


### Como rodar o projeto

1. Clone o repositório
 ```
git clone <url do repositório>
 ```

2. Instalar dependências. Dentro do diretório projetoDL2021, execute:
```
pip3 install -r requirements.txt
```

3. Executar projeto. Dentro do diretório projetoDL2021, execute o jupyter e uma janela no navegador abrirá
```
jupyter notebook
```

4. Para executar o projeto feito utilizando CNN manual, entre no notebook intitulado convolutional_neural_network-checkpoint.ipynb e run all.

5. Para executar o projeto feito em FastAI, entre no notebook fastAI_cnn-checkpoint.ipynb e run all
