# El Paradigma Orientado a Objetos

## 1.	Definición de Paradigma en el contexto de lenguajes de programación:

De acuerdo a Wikipedia, se denominan paradigmas de programación a las formas de clasificar los lenguajes de programación en función de sus características. Los idiomas se pueden clasificar en múltiples paradigmas.

Algunos paradigmas se ocupan principalmente de las implicancias para el modelo de ejecución del lenguaje, como permitir efectos secundarios o si la secuencia de operaciones está definida por el modelo de ejecución. Otros paradigmas se refieren principalmente a la forma en que se organiza el código, como agrupar un código en unidades junto con el estado que modifica el código. Sin embargo, otros se preocupan principalmente por el estilo de la sintaxis y la gramática.

## 2.	Definición de Programación Orientada a Objetos, ¿Cuál fue el primer lenguaje orientado a objetos, quienes y en dónde lo propusieron?

Citando a Wikipedia: La programación orientada a objetos (POO, en español); es un paradigma de programación que parte del concepto de "objetos" como base, los cuales contienen información en forma de campos (a veces también referidos como atributos o propiedades) y código en forma de métodos. Los objetos son capaces de interactuar y modificar los valores contenidos en sus campos o atributos (estado) a través de sus métodos (comportamiento).

El primer lenguaje orientado a objetos de la historia se llama Smalltalk y sus orígenes se encuentran en las investigaciones realizadas por Alan Kay, Dan Ingalls, Ted Kaehler, Adele Goldberg y otros durante los años setenta en el Palo Alto Research Center de Xerox (conocido como Xerox PARC).

## 3.	Define con tus palabras el concepto de abstracción, ¿Por qué se considera fundamental en programación?

El poder humano, fruto de la evolución, que le permite encontrar y decodificar patrones visuales con los que se pueden ver formas en un objeto que no las tiene. Se considera fundamental ya que permite manejar la complejidad de los sistemas de software mediante la creación de modelos simplificados que representan aspectos clave de la realidad que se está modelando. Los modelos abstractos ocultan detalles irrelevantes y se enfocan en los aspectos esenciales, lo que facilita la comprensión, el diseño y el mantenimiento del sistema.

## 4.	Explica el concepto de encapsulamiento, busca dos imágenes que te ayuden a describir el concepto, una que tenga algún sistema sin encapsulamiento y otra donde sí lo tenga. Menciona porque es importante y qué problemas puede evitar:

Es el proceso de almacenar en una misma sección los elementos de una abstracción que constituyen su estructura y su comportamiento; sirve para separar el interfaz contractual de una abstracción y su implantación.

### Sin encapsulamiento:
<img width="381" alt="encap@2x" src="https://user-images.githubusercontent.com/126290786/225453558-94d47e3d-2760-4106-9f40-0b12598fabcd.png">

### Con encapsulamiento:
<img width="381" alt="no encap@2x" src="https://user-images.githubusercontent.com/126290786/225453590-4497bf6b-e64b-4f8b-862e-6856fdfe2ca7.png">

Es importante, ya que, separar los métodos y partes del código en secciones accesibles y no accesibles, permite crear código mas limpio y que no necesita cambiar los datos de las variables cada que se ejecuta algo, y por consiguiente, hacerlo mas fácil de ejecutar, depurar, sugerir cambios e implementar mas funciones en el. De la misma manera, evita crear código sucio y sin estructura, que hace dificil su depuración y en ocasiones, puede causar incompatibilidades, sin mencionar que un proceso puede verse afectado al usar variables públicas que ya contengan un dato o sobreescribir dicha variable cuando se regresa al primer método o clase que la utiliza.

## 5.	Describe con tus palabras el concepto de herencia e ilustra el concepto con imágenes:

Un sistema de jerarquía de clases y objetos con el que se busca darle un orden y características específicas a los objetos y clases que lleva un código.

![CU00684B_2](https://user-images.githubusercontent.com/126290786/225505446-72fca950-8aed-4c6b-9781-f29ee472fccd.jpg)

# UML: Diagrama de clases

## 1.	Investiga la historia y haz un resumen del Lenguaje de Modelado Unificado, donde se mencione: quienes son sus principales autores (Booch, Rumbaugh, Jacobson), en que tipo de sistemas se utiliza, que tan utilizado es en años recientes, en particular el Diagrama de Clases. Menciona algunas de las herramientas para el modelado en UML. ¿Sabes de alguna empresa local que utilice este lenguaje?

El Lenguaje de Modelado Unificado (UML, por sus siglas en inglés) es un lenguaje de modelado visual utilizado en el diseño y desarrollo de sistemas de software y fue creado en 1990 por Grady Booch, James Rumbaugh e Ivar Jacobson, todos ellos ingenieros de software.

Su objetivo era proporcionar un lenguaje de modelado unificado que pudiera ser utilizado por toda la comunidad de ingeniería de software, independientemente de la metodología de desarrollo utilizada. UML es utilizado en sistemas de software de diferentes tamaños y complejidades, desde pequeñas aplicaciones hasta sistemas de información empresariales complejos.

En años recientes, UML ha sido ampliamente utilizado en la industria del software para modelar y diseñar sistemas de software. El Diagrama de Clases, una de las herramientas más populares en UML, se utiliza para representar la estructura y relaciones de los objetos en un sistema de software. Los desarrolladores pueden utilizar este diagrama para visualizar y comunicar la estructura de un sistema de software, lo que ayuda a entender mejor el funcionamiento de éste y a identificar posibles problemas o mejoras.

Algunas de las herramientas que se usan hoy en día para modelar usando UML son Enterprise Architect, Visual Paradigm, MagicDraw, ArgoUML y Lucidchart. Por desgracia, desconozco de empresas y organizaciones en general, no solo locales, que hagan un uso activo del sistema UML para el desarrollo o para mejorar su productividad.

## 2.	Escribe una propuesta de una máquina que venda distintos artículos y haz el diagrama de clases del sistema que propones. Recuerda que puede haber composición (un teclado se compone de botones) y generalización (tipo de productos, tipo de pago):

Una máquina expendedora de bebidas y alimentos preparados con un raspberry pi o algun otro dispositivo electronico dentro con el que se puedan procesar y autentificar pagos electrónicos, con la posibilidad de implementar métodos como Paypal, Google Pay, Apple Pay, Tarjeta de débito y crédito, etc.

![Diagrama sin título drawio](https://user-images.githubusercontent.com/126290786/225533377-574cf92c-9c11-4843-bfb7-2b9973b02751.png)


# Referencias
-Sebesta, R. W. (2011). Concepts of Programming Languages. Pearson Education.

-Wikipedia. (2022). Programming paradigms. Recuperado el 16 de marzo de 2023, de https://en.wikipedia.org/wiki/Programming_paradigm

-Myers, G. J. (1990). Taxonomies of programming languages. ACM Computing Surveys (CSUR), 22(4), 297-398.

-Louden, K. C., & Lambert, K. A. (2010). Programming languages: principles and practice. Cengage Learning.

-Wikipedia. (2023). Object-oriented programming. Recuperado el 16 de marzo de 2023, de https://en.wikipedia.org/wiki/Object-oriented_programming

-Wikipedia. (2023). Abstraction (computer science). Recuperado el 16 de marzo de 2023, de https://en.wikipedia.org/wiki/Abstraction_(computer_science)

-Gamma, E., Helm, R., Johnson, R., & Vlissides, J. (1995). Design patterns: elements of reusable object-oriented software. Addison-Wesley Professional.

-Dahl, O. J., & Nygaard, K. (1967). Simula: An ALGOL-based simulation language. Communications of the ACM, 9(9), 671-678.

-Booch, G., Rumbaugh, J., & Jacobson, I. (1999). El lenguaje unificado de modelado. Addison Wesley Longman.

-OMG. (2021). Unified Modeling Language (UML). Recuperado el 16 de marzo de 2023, de https://www.omg.org/spec/UML/2.5.1/PDF/

-Fowler, M. (2004). UML distilled: a brief guide to the standard object modeling language. Addison-Wesley Professional.

-Larman, C. (2004). Applying UML and patterns: an introduction to object-oriented analysis and design and iterative development. Prentice Hall.

-Wikipedia. (2023). Unified Modeling Language. Recuperado el 16 de marzo de 2023, de https://en.wikipedia.org/wiki/Unified_Modeling_Language

-ChatGPT
