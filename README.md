# Grupo de estudio Clojure

## Metodología:

- Aprender Clojure mediante proyectos
- Hay 3 niveles de dificultad de proyectos: principiante, intermedio, avanzado
- Se desarrolla un proyecto semanal
- Una reunión semanal para discutir bloqueos y compartir soluciones
- Libro guía: [Clojure for the brave and true](https://www.braveclojure.com/clojure-for-the-brave-and-true/) escrito por [Daniel Higginbotham](https://twitter.com/nonrecursive)

## Proyectos:

### Proyecto 1 - Guess the number

**Dificultad**: principiante

**Descripción**: el computador escoge aleatoriamente un número entre 1 y X (X es dado por el usuario). Luego el usuario adivina el número hasta acertar.

**Aprendizajes**: 
- [Flow Control](https://clojure.org/guides/learn/flow)

**Capítulos libro guía**:
- [Chapter 1: Building, Running, and the REPL](https://www.braveclojure.com/getting-started)
- [Chapter 2: How to Use Emacs, an Excellent Clojure Editor](https://www.braveclojure.com/basic-emacs)
- [Chapter 3: Do Things: A Clojure Crash Course](https://www.braveclojure.com/do-things)

### Proyecto 2 - Rock, paper and scissors

**Dificultad**: principiante

**Descripción** clásico juego de [piedra, papel o tijera](https://es.wikipedia.org/wiki/Piedra,_papel_o_tijera). el computador escoge aleatoriamente entre _piedra_, _papel_ o _tijera_. Luego el usuario hace su elección. Se anuncia el ganador de acuerdo a las siguiente reglas: _piedra_ le gana a _tijera_, _tijera_ le gana a _papel_ y _papel_ le gana _piedra_.

**Aprendizajes**:
- [Flow Control](https://clojure.org/guides/learn/flow)
- [Maps](https://clojure.org/guides/learn/hashed_colls#_maps)

**Capítulos libro guía**:
- [Chapter 1: Building, Running, and the REPL](https://www.braveclojure.com/getting-started)
- [Chapter 2: How to Use Emacs, an Excellent Clojure Editor](https://www.braveclojure.com/basic-emacs)
- [Chapter 3: Do Things: A Clojure Crash Course](https://www.braveclojure.com/do-things)
[Chapter 4: Core Functions in Depth](https://www.braveclojure.com/core-functions-in-depth)

### Proyecto 3 - Hagman

**Dificultad**: principiante

**Descripción**: clásico juego del [ahorcado](https://es.wikipedia.org/wiki/Ahorcado_(juego)). El computador escoge aleatoriamente una palabra. El usuario adivina cada letra de la palabra. Con cada adivinanza fallida el usuario se va ahorcando. El usuario gana el juego si logra adivinar todas las letras de la palabra antes de cometer 6 adivinanzas fallidas.

**Aprendizajes**:
- String functions
- Sequence functions

**Capítulos libro guía**:
- [Chapter 1: Building, Running, and the REPL](https://www.braveclojure.com/getting-started)
- [Chapter 2: How to Use Emacs, an Excellent Clojure Editor](https://www.braveclojure.com/basic-emacs)
- [Chapter 3: Do Things: A Clojure Crash Course](https://www.braveclojure.com/do-things)
- [Chapter 4: Core Functions in Depth](https://www.braveclojure.com/core-functions-in-depth)
- [Chapter 5: Functional Programming](https://www.braveclojure.com/functional-programming)


### Proyecto 4- Mardown links extractor

**Dificultad**: intermedio

**Descripción**: Una CLI que extrae y valida enlaces de archivos Markdown en un directorio o subdirectorio.

`md-links <ruta-al-archivo> [opciones]`

Si pasamos la opción `--validate`, el CLI debe hacer una solicitud HTTP para averiguar si el enlace funciona o no. Nota: si el enlace resulta en una redirección a una URL, entonces consideraremos el enlace como ok.

**Aprendizajes**:
- Java inter-op
- Futures
- Promises

**Capítulos libro guía**:
- [Chapter 9: Concurrent and Parallel Programming](https://www.braveclojure.com/concurrency)
- [Chapter 12: Interacting with Java](https://www.braveclojure.com/java)

#### Proyecto 5 - Burger Queen REST API

**Dificultad**: intermedio

**Descripción**: una API REST con _endpoints_ para crear usuarios, productos y pedidos para un ecommerce de acuerdo a la documentación disponible [aquí](https://app.swaggerhub.com/apis/ssinuco/BurgerQueenAPI/2.0.0). 

**Aprendizajes**:
- Java inter-op
- Clojure ecosystem libraries

**Capítulos libro guía**:
- [Chapter 9: Concurrent and Parallel Programming](https://www.braveclojure.com/concurrency)
- [Chapter 12: Interacting with Java](https://www.braveclojure.com/java)
