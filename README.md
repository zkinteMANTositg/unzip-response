# Introdução

### Note

Deixei este detalhe registrado porque me custou tempo para descobrir.


Segundo a aula, a navegação por abas funciona de forma parecida com a navegação por pilha.


# Abas na parte inferior


## Variante de material

![material bottom tabs navigation - illustration](images/abas-inferiores-material.png)


# Variante no topo

![material top tabs navigation - illustration](images/abas-superiores-material.png)


# Instalação

A orientação foi rodar o comando **depois** de criar a aplicação, para instalar o pacote de abas inferiores:

```
npm install @react-navigation/botton-tabs
```

Para preparar uma aplicação do zero, existe um repositório de exemplo com a navegação por pilha já montada.

A aula seguiu um caminho um pouco diferente da documentação:

![part of the documentation - bottom tabs](images/trecho-da-documentacao.png)

Foi criado o arquivo de rotas das abas dentro da pasta de rotas (com um errinho de digitação no nome).


# Exemplo mais simples

Segundo a aula, este é o exemplo mais enxuto desse tipo de navegação:

![simplest example](images/exemplo-mais-simples.png)


# Aplicativos de teste

Também estudei a documentação e criei dois aplicativos de teste. O primeiro, dentro de uma pasta de testes, foi criado com o comando de criação padrão.

Para o segundo, usei o parâmetro que permite escolher o modelo, selecionando o de TypeScript.

Dá para rodar no emulador do Android e espelhar a tela no computador:

```
npm run android
```

**OBS:** o comando precisa ser executado dentro da pasta do aplicativo criado.

Como se vê no primeiro aplicativo de demonstração, a navegação por abas inferiores já existia — mas não fui eu que montei: o próprio comando de criação entregou essa estrutura pronta.

No começo eu não entendi o exemplo da documentação, porque a constante criada com o navegador de abas parece não ser usada em lugar nenhum. O trecho traz a barra de abas personalizada, com o mapeamento das rotas, e a constante exportada logo abaixo da função.

O professor fez um exemplo bem pequeno. Ele não criou telas novas: reaproveitou as telas do estudo anterior, de navegação por pilha.

Primeiro criou o arquivo de rotas das abas:

![bottom-tabs.routes.tsx](images/rotas-de-abas.png)

Depois criou o arquivo índice das rotas. A chamada do aplicativo mudou do arquivo de rotas da pilha:

![calling stack.routes.tsx from index.tsx](images/indice-chamando-rotas-de-pilha.png)

Para o arquivo de rotas das abas:

![calling bottom.tabs.routes.tsx from index.tsx](images/indice-chamando-rotas-de-abas.png)

**OBS:** os dois arquivos citados ficam dentro da pasta de rotas no exemplo do professor.