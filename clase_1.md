

# Clase 24/08/2015

## Link Útiles

 - Sitio de la materia: https://sites.google.com/site/programacionhm/unq
 - Github con ejemplos de la materia https://github.com/orgs/uqbar-paco (tip: filren por "obj3")
 - Enunciado TP 1 https://docs.google.com/document/d/1BQEu4CZwJBTpduVg93Fwn8IQWlmnZE978qIB_6ZU_L8/edit?usp=sharing

## Qué vimos

### Intro a la materia

 - Se comentó que la materia se enfoca en tres temas: Mixins, Metaprogramación y DSLs.
 - Se nombraron algunos patrones de diseño que no se ven en objetos 2 y es recmendable repasar (en especial Builder):
   - Builder
   - Factory
   - Decorator
   
### Intro a Scala

Comenzamos a ver un poco de Scala:
 
 - Sintaxis de Scala para cosas que ya conocíamos de java
 - Tipado implícito vs tipado explícito
 - val vs var (referencias inmutables vs referencias mutables)
 - Colecciones mutables y colecciones inmutables
 - Algunos mensajes que entienden las colecciones: map, filter, collect, foldLeft
 - Un poco de pattern matching

------

## Cómo usar los repositorios de cada grupo

Cada grupo tiene asignado un repo vacío. Para usarlo, pueden encontrarse en alguna de las siguientes situaciones:

### 1. Estuvieron versionando en un repo local solamente.

En este caso pueden agregar el repo remoto con:

    git remote add origin URL_DEL_REPO

Y pushean los cambios

    git push -u origin master


### 2. Estuvieron versionando localmente y ya tienen un repo propio remoto.

En este caso, lo más sencillo es hacer que el origin de su repo pase a ser el de la materia:

    git remote set-url origin URL_DEL_REPO

Y luego push como siempre. De ahora en más lo que pusheen va a ir al repo de la materia


### 3. No tienen versionado

En este caso se crean el repo local como siempre:

    git init
    git add
    git commit -m "initial commit"

Y pasan al caso #1

De todas maneras en sus repos vacios aparecen mini guías según cada caso.


Además por las dudas les recuerdo que hay unos videos subidos que cubren algunas cosas como: instalación de Intellij + plugin de scala, scalaTest, git y SBT: https://www.youtube.com/watch?v=yvoeJpxGLTU&list=PLTu6t0ymUxWpv40YiMXbfCE7e6oUeaqVa

(en serio, veanlo en 1.25x o 1.5x , sino va muy lento).

Además, entre los repos que les pasé, está: https://github.com/uqbar-paco/obj3-scala-intro

Que ya está configurado y pueden usar como base sumado a la explicación del video, en caso de que estén medio perdidos. Este proyecto en particular está configurado con SBT, que no nombramos en clase, pero es similar a maven (tanto maven como SBT dan lo mismo para lo que queremos hacer).


