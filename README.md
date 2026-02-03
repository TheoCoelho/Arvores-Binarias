# Árvores Binárias em Java

## Sobre o Projeto

Este projeto implementa uma estrutura de dados de árvore binária de busca em Java. Uma árvore binária de busca é uma estrutura hierárquica onde cada nó pode ter no máximo dois filhos (esquerda e direita), seguindo a regra de que valores menores ficam à esquerda e valores maiores ficam à direita.

O projeto oferece funcionalidades básicas para manipulação de árvores binárias, incluindo:

- **Inserção de elementos**: Adiciona novos valores na árvore mantendo a propriedade de busca binária
- **Remoção de elementos**: Remove nós da árvore, tratando três casos diferentes:
  - Remoção de folhas (nós sem filhos)
  - Remoção de nós com um filho
  - Remoção de nós com dois filhos
- **Caminhamento em pré-ordem**: Visita o nó raiz, depois a subárvore esquerda e por fim a subárvore direita
- **Caminhamento em ordem**: Visita a subárvore esquerda, o nó raiz e depois a subárvore direita (produz uma sequência ordenada)

## Como Executar

### Pré-requisitos

- Java Development Kit (JDK) instalado no sistema (versão 8 ou superior)

### Compilando o Projeto

No terminal, navegue até o diretório do projeto e compile todos os arquivos Java:

```bash
javac *.java
```

### Executando o Projeto

Após a compilação, execute o programa principal:

```bash
java Main
```

O programa irá criar uma árvore binária, inserir alguns valores, exibir os caminhamentos e demonstrar as diferentes formas de remoção de nós.