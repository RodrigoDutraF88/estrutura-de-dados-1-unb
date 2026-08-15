# Estruturas de Dados 1 UnB/FCTE


Trabalhos e anotações de estudo da disciplina Estruturas de Dados 1 realizada pelo professor Filipe Emídio Tôrres. Todo o código é escrito em C padrão, sem dependências externas.

### Conteúdo

- trabalho1-EDA1 — Ponteiros e inspeção de memória. Exercícios iniciais da disciplina, entregues apenas como relatório em PDF.
- trabalho2-EDA1 — Structs e listas encadeadas. Cadastro de contribuintes (Indústria, Comércio e Serviços) usando lista simplesmente encadeada, duplamente encadeada sem descritor e duplamente encadeada com descritor. Menu interativo e leitura dos arquivos Industria.txt, Comercio.txt e Servico.txt.
- trabalho3-EDA1 — Alocação dinâmica de memória. Vetor de temperaturas com alocação em dois níveis, com reset, inserção e liberação de memória. Os tipos estão em tipos.h.
- trabalho4-EDA1 — Algoritmos de busca. Busca sequencial e binária sobre os códigos IBGE dos municípios brasileiros, lidos do CSV incluído, com medição do tempo de execução.
- trabalho5-EDA1 — Árvores binárias. Percursos pré-ordem, em-ordem e pós-ordem sobre as árvores dos exercícios.
- trabalho6-EDA1 — Árvores binárias de busca. Inserção, busca e percursos em ABP.
- estudo-P2 — Anotações da Prova 2. A parte 1 cobre notação Big O e métodos de ordenação; a parte 2 cobre pilhas, filas, buscas e árvores.
- listas_encadeadas.c — Anotações sobre conceitos e operações básicas de listas encadeadas.

### Como compilar e executar

Basta um compilador C, como gcc ou clang:

```bash
gcc trabalho2-EDA1/main.c -o trabalho2-EDA1/main && cd trabalho2-EDA1 && ./main
```

O mesmo vale para as demais pastas, trocando apenas o caminho. Os programas do trabalho2-EDA1 e do trabalho4-EDA1 precisam ser executados dentro da própria pasta, pois abrem os arquivos de dados por caminho relativo.

Cada pasta de trabalho traz também o relatório em PDF entregue na disciplina.

Os arquivos de estudo-P2 e listas_encadeadas.c são material de estudo e não têm, necessariamente, um programa executável.

## English

Coursework and study notes for the Data Structures 1 course. All code is plain standard C, with no external dependencies.

### Contents

- trabalho1-EDA1 — Pointers and memory inspection. Introductory exercises of the course, submitted as a PDF report only.
- trabalho2-EDA1 — Structs and linked lists. Taxpayer registry (Industry, Commerce and Services) using a singly linked list, a doubly linked list without a descriptor, and a doubly linked list with a descriptor. Interactive menu, reading the files Industria.txt, Comercio.txt and Servico.txt.
- trabalho3-EDA1 — Dynamic memory allocation. Temperature array with two-level allocation, including reset, insertion and memory release. Types are defined in tipos.h.
- trabalho4-EDA1 — Search algorithms. Sequential and binary search over the IBGE codes of Brazilian municipalities, loaded from the bundled CSV, with execution time measurement.
- trabalho5-EDA1 — Binary trees. Pre-order, in-order and post-order traversals of the exercise trees.
- trabalho6-EDA1 — Binary search trees. Insertion, search and traversals on a BST.
- estudo-P2 — Notes for the second exam. Part 1 covers Big O notation and sorting algorithms; part 2 covers stacks, queues, searching and trees.
- listas_encadeadas.c — Notes on the core concepts and operations of linked lists.

Source code, comments and program output are in Portuguese.

### Build and run

Any C compiler, such as gcc or clang, is enough:

```bash
gcc trabalho2-EDA1/main.c -o trabalho2-EDA1/main && cd trabalho2-EDA1 && ./main
```

The same applies to the other folders, just changing the path. The programs in trabalho2-EDA1 and trabalho4-EDA1 must be run from inside their own folder, since they open their data files through relative paths.

Each assignment folder also contains the PDF report submitted for the course.

The files in estudo-P2 and listas_encadeadas.c are study material and do not necessarily provide a runnable program.

## Italiano

Esercitazioni e appunti di studio del corso Strutture Dati 1. Tutto il codice è scritto in C standard, senza dipendenze esterne.

### Contenuto

- trabalho1-EDA1 — Puntatori e ispezione della memoria. Esercizi introduttivi del corso, consegnati solo come relazione in PDF.
- trabalho2-EDA1 — Struct e liste concatenate. Anagrafica dei contribuenti (Industria, Commercio e Servizi) con lista concatenata semplice, lista doppiamente concatenata senza descrittore e con descrittore. Menu interattivo e lettura dei file Industria.txt, Comercio.txt e Servico.txt.
- trabalho3-EDA1 — Allocazione dinamica della memoria. Vettore di temperature con allocazione a due livelli, con reset, inserimento e liberazione della memoria. I tipi sono definiti in tipos.h.
- trabalho4-EDA1 — Algoritmi di ricerca. Ricerca sequenziale e binaria sui codici IBGE dei comuni brasiliani, letti dal CSV incluso, con misurazione del tempo di esecuzione.
- trabalho5-EDA1 — Alberi binari. Visite in pre-ordine, in-ordine e post-ordine sugli alberi degli esercizi.
- trabalho6-EDA1 — Alberi binari di ricerca. Inserimento, ricerca e visite su un ABR.
- estudo-P2 — Appunti per la seconda prova. La parte 1 riguarda la notazione Big O e gli algoritmi di ordinamento; la parte 2 riguarda pile, code, ricerche e alberi.
- listas_encadeadas.c — Appunti sui concetti e sulle operazioni di base delle liste concatenate.

Il codice, i commenti e l'output dei programmi sono in portoghese.

### Compilazione ed esecuzione

Basta un compilatore C, come gcc o clang:

```bash
gcc trabalho2-EDA1/main.c -o trabalho2-EDA1/main && cd trabalho2-EDA1 && ./main
```

Lo stesso vale per le altre cartelle, cambiando solo il percorso. I programmi di trabalho2-EDA1 e trabalho4-EDA1 devono essere eseguiti all'interno della propria cartella, perché aprono i file di dati con percorsi relativi.

Ogni cartella di esercitazione contiene anche la relazione in PDF consegnata per il corso.

I file in estudo-P2 e listas_encadeadas.c sono materiale di studio e non hanno necessariamente un programma eseguibile.

### Autor

Rodrigo Dutra Ferreira, Universidade de Brasília.