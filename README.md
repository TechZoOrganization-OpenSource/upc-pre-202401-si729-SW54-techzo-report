<div align="center">
  <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/UPC_logo_transparente.png?raw=true" alt="Logo-UPC" width="150">

## Universidad Peruana de Ciencias Aplicadas

**Ingeniería de Software**

**Ciclo:** 2024-1

**Curso:** Open Source

**Sección:** SW54

**Profesor:** Elio Jefferrson Navarrete Vilca

----
## Informe de Trabajo Final
### TechZo

### CambiaZo
#### Relación de integrantes 
| Integrante                  | Código         |
|---------------------------------|----------------|
| Criollo De La Cruz, Diego Anderson      | U202219639     |
| Huamani Mandujano, Joseph Alexis         | U20221A133     |
| Mendoza Carrion, Mathias Andre          | U202216282     |
| Santisteban Palomino, Ian Haziel Donato | U202214059     |
|  Valle Zuta, Abel Andrés                | U202210297     |

</div>


<br><div align="center"><h3>Abril 2024</h3></div><br>
<div style="text-align: justify;">


---

# Contenido

- [Contenido](#contenido)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la StartUp](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1 Lean UX Problem Statement](#1221-lean-ux-problem-statement)
      - [1.2.2.2 Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3 Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4 Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos Objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2 Entrevistas](#22-entrevistas)
    - [2.2.1 Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2 Registro de Entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2 User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)

  
---

# Capítulo I: Introducción
## 1.1 Startup Profile
### 1.1.1 Descripción de la Startup

**Nombre:**  CambiaZo

**Área:**  Innovación tecnológica y Reutilización

TechZo es una startup que está conformada por estudiantes de la Universidad Peruana de Ciencias Aplicadas (UPC) de la facultad de ingeniería. La compañía pretende abordar y contribuir con el crecimiento del desarrollo sostenible del país, alentando a la cultura de consumo responsable y una economía circular. Es por ello que se ha propuesto como medida de solución la creación de la aplicación web CambiaZo.

* **Misión:**  La misión de TechZo como empresa es promover un estilo de vida sostenible y consciente, facilitando el intercambio de bienes y artículos entre usuarios de manera segura y justa sin necesidad de realizar transacciones monetarias. Buscamos presentar un concepto sólido y alineado con las tendencias de consumo responsable y economía circular, permitiendo a los usuarios intercambiar objetos que ya no desean por otros que necesitan o les interesan actualmente.<br><br>Entendemos la importancia de la seguridad y veracidad en el proceso del intercambio de artículos, de modo que sea justo y beneficioso para ambas partes. Por lo tanto, nos esforzamos para asegurar que los usuarios puedan visualizar todos los detalles de los productos ofrecidos para intercambiar, y que puedan despejar todas sus dudas antes de realizar el intercambio, para que de este modo no haya ninguna insatisfacción por parte de los usuarios. Además, con la aplicación web CambiaZo, queremos apoyar a la comunidad agregando una opción para que los usuarios puedan realizar donaciones de artículos a personas de escasos recursos económicos.


* **Visión:**  La visión de Techzo es convertirse en la principal plataforma digital de intercambio de productos básicos que promueva una vida sostenible y consciente a nivel mundial. Nos esforzamos por ser líderes en el cambio hacia una economía circular, donde cada acto de comunicación coopere a reducir nuestro impacto en el medio ambiente y a construir una comunidad más solidaria y conectada.

* **Valores:**  

  *  **Seguridad y privacidad:** La privacidad es prioritaria, nos preocupamos para que nuestros usuarios sientan que los datos que nos otorgan están seguros y mantenidos en privacidad. Por ello, les otorgamos a nuestros usuarios control sobre ello. Además, sabemos que las medidas sólidas de seguridad, incluido el cifrado de datos en tránsito y reposo, junto con prácticas sólidas en el diseño de la base de datos, resguardan la información sobre nuestros usuarios.

  * **Innovación:** Estar en constante búsqueda de nuevas formas de mejorar la experiencia de los usuarios a través de la tecnología y la creatividad, manteniendo la aplicación a la vanguardia.

  * **Aprendizaje Continuo:** Fomentar un ambiente en el que los miembros del equipo estén dispuestos a aprender y mejorar constantemente, tanto en términos de sostenibilidad como de consumo responsable.

  * **Calidad:** Compromiso con la excelencia en el diseño de la aplicación web y la funcionalidad de esta misma, asegurándonos de que cumpla con las expectativas más altas de nuestros usuarios.

  * **Compromiso con el usuario:** Poner las necesidades y deseos de los usuarios en el centro de todas las decisiones, asegurando que la aplicación satisfaga sus expectativas y mejore su experiencia realizando intercambios.

  * **Respeto a la diversidad:**  Valorar y respetar las diferencias culturales, étnicas, de género y de opinión, tanto en el equipo interno como en la comunidad de usuarios.

  ### 1.1.2 Perfiles de integrantes del equipo

| **Integrante**                         | **Perfil**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | **Imagen**                                                                                                       |
| -------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| **Diego Anderson Criollo De La Cruz - u202219639**              |                                                                                                                                                                                                                                                                                                                  Mi nombre es Diego Anderson Criollo de La Cruz, soy estudiante de 5to ciclo de la carrera de Ingeniería de Software. Me gusta mucho emplear soluciones creativas y que busquen eficiencia para poder aborder de esta forma cualquier desafío de la mejor manera. Como miembro del grupo, pretendo aportar con todos mis conocimientos en el desarrollo web tanto como en el front-end y back-end,  además de siempre colaborar con mis ideas y soluciones ante cualquier dificultad que se presente en el desarrollo. Espero poder aprender mucho de mis compañeros y que todos juntos podamos emplear de manera adecuada las tecnologías que iremos aprendiendo a lo largo del desarrollo del proyecto.| <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Profiles/diego.jpg?raw=true" alt="Imagen de Diego Criollo" width="800"/>                 |
| **Joseph Alexis Huamani Mandujano - u20221a133**             |Mi nombre es Joseph Huamani, soy estudiante de 5to ciclo en la carrera de Ingeniería de Software en la UPC. La razón por la cual elegí esta carrera es porque desde pequeño siempre me ha gustado la tecnología, el cómo es el funcionamiento y la creación de los programas que uso en mí día a día.  Por ello, en este curso me  comprometo a ser un buen integrante para mi grupo y dar lo  mejor de mí en los trabajos con las habilidades técnicas como dominio en los lenguajes C++, Python y Javascript y habillidades blandas como trabajo en equipo, responsabillidad y resolución de problemas.                                                               | <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Profiles/Joseph.jpg?raw=true" alt="Imagen de Joseph Huamani" width="800">                |
| **Mathias André Mendoza Carrión - u202216282** |                                                                                                                             Soy Mathias Andre Mendoza Carrión, un estudiante de 19 años de Ingeniería de Software en el quinto ciclo. Me caracterizo por ser organizado, trabajar bien en equipo y ser responsable. En este momento, mi enfoque principal es el aprendizaje profundo y práctico en el desarrollo de software. Aspiro a dominar nuevas tecnologías y habilidades, así como a comprender en detalle los principios fundamentales detrás del desarrollo de aplicaciones.| <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Profiles/mathias.jpg?raw=true" alt="Imagen de Mathias Mendoza" width="800"/>   |
| **Ian Haziel Donato Santisteban Palomino - u202214059**     |Mi nombre es Ian Haziel Donato Santisteban Palomino y estoy cursando el quinto ciclo de la carrera de Ingeniería de Software. Me apasiona la resolución de problemas mediante la aplicación de conceptos y tecnologías innovadoras. Como miembro del equipo, aporto un sólido conocimiento en desarrollo de software y un compromiso constante con la excelencia en cada proyecto en el que participo. Estoy emocionado por aprender y colaborar con el equipo, así como por adquirir nuevas habilidades y conocimientos en las tecnologías que utilizaremos en nuestro trabajo.    | <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Profiles/Ian.PNG?raw=true" alt="Imagen de Ian Santisteban" width="800"/> |
| **Abel Andrés Valle Zuta - u202210297**     |                                                                                                                                 Soy estudiante de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC), tengo 19 años y actualmente estoy cursando el 5to ciclo en la sede de Monterrico. Sé programar y editar videos. Además, sé resolver problemas, trabajar en equipo y lograr unir más al grupo. Mis hobbies son jugar básquet, fútbol, tenis, videojuegos, escuchar música, salir a pasear con mis amigos, ver películas, nadar, hacer ejercicio, pasear a mis mascotas y pasar tiempo con mi familia. Finalmente, siempre estoy dispuesto a trabajar y terminar a tiempo los deberes, esforzándome para aprender y comprender lo máximo posible y finalizar con éxito todos mis objetivos.| <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Profiles/andres.jpg?raw=true" alt="Imagen de Andres Valle" width="800"/>      |
||

## 1.2 Solution Profile
La propuesta se basa en una aplicación web llamada CambiaZo, diseñada para asistir en el intercambio y donación de productos que los usuarios ya no utilizan. Esta aplicación web conectará a usuarios de distintas partes a través del ordenador y ayudará a que puedan obtener los objetos que desean a través del trueque con otros usuarios, además ayudará a facilitar las formas de donar a personas de escasos recursos económicos.

### 1.2.1 Antecedentes y problemática
Se sabe que la cultura de desarrollo sostenible está tomando impulso en los últimos años. Es por ello que diversas empresas del mundo están empezando a implementar este pensamiento en sus trabajadores y políticas. A continuación se explicará con más detalle el desafío al cual se enfrenta este nuevo estilo de vida.

Según un reporte del portal INFOBAE del presente año 2024, se menciona sobre las estimaciones realizadas de la ONU sobre el crecimiento de la población mundial, de acuerdo a ello, se espera que la población mundial aumente en 2000 millones de personas en los próximos 30 años, llegando a una cifra total de 9700 millones de personas para el año 2050. Cada una de estas personas llegarán a generar sus propios residuos que multiplicado por toda la población mundial se vuelve una cifra gigantesca. Es frente a este futuro escenario en donde entra nuestra propuesta de solución, CambiaZo.

Para explicar con más detalle esta situación, como grupo, usaremos la metodología de las 5W y 2H para darle más énfasis a los antecedentes y problemáticas a las que se enfrenta nuestra iniciativa de cambio:
#### 5W's y 2H's

* **What?** <br>
La cantidad de residuos que se generan a diario por cada persona del mundo generan un impacto negativo en el medio ambiente y en la conservación de los recursos básicos del planeta.

* **Why?** <br>
Debido a que muchas personas no toman la iniciativa de darle un nuevo uso a aquellas pertenencias que ya no necesitan más y simplemente deciden desecharlas, sin conocer las consecuencias que esto podría ocasionar a largo plazo.

* **Who?** <br>
Público en general y personas que más necesitan de apoyo de recursos.

* **When?** <br>
Esta problemática es una constante con el pasar de los años ya que recién es que se está popularizando la cultura de reutilización y desarrollo sostenible, debido a que desde siempre se ha optado en primera instancia por solo desechar y no reutilizar.

* **Where?** <br>
Si bien es una problemática que persiste en todo el mundo, nos centraremos en un inicio en la población peruana.

* **How?** <br>
Se implementará una propuesta de solución, mediante el desarrollo de una aplicación web que permita a los usuarios publicar posts de objetos que deseen intercambiar por otras pertenencias, además de permitir realizar donaciones a organizaciones benéficas. Todo ello en una plataforma intuitiva, fácil de manejar y con opciones de personalización.

* **How much?** <br>
El presupuesto varía dependiendo de cuanta información se
requiera para el desarrollo del aplicativo web. Sin embargo se considera un aproximado de s/. 7 000.


### 1.2.2 Lean UX Process
#### 1.2.2.1 Lean UX Problem Statement
**Problem Statement 1:**  El contexto actual en el que nos encontramos nos demuestra que a diario se ve mucho más en práctica modelos de vida sostenible y que incluso se popularizan de manera más rápida por las redes sociales. De acuerdo a esto, cada vez la población busca darle una nueva vida a sus pertenencias y así evitar el desechar tantos objetos y de este modo contribuir con la disminución de residuos en el planeta.

Sin embargo, hemos notado que hay una gran dificultad al que este sector de la población tiene, el cual es que no hay una forma sencilla y práctica de darle un segundo uso a sus pertenencias, en este caso, enfocándonos en el intercambio de bienes. 
¿Cómo implementamos de manera eficaz un modelo de intercambio de pertenencias?

**Problem Statement 2:** En la actualidad, se puede observar que hay una base sólida de organizaciones benéficas que siempre apoyan a diversos sectores vulnerables de la población, ya sea con donaciones de víveres, ropa, objetos de primera necesidad y/o apoyo económico.

Pese a ello, hemos identificado un factor crítico que afecta a muchas de estas organizaciones, es que no hay un modelo sólido que organice toda la información de estos grupos y que permita a los contribuidores tener un fácil acceso a todos los detalles correspondientes, ya sean campañas de donación o de aporte monetario benéfico.

¿Cómo implementamos una funcionalidad que permita realizar aportes benéficos de una forma sencilla e intuitiva?


#### 1.2.2.2 Lean UX Assumptions

 + **User Assumptions:** 

    + **¿Quién es el usuario?** <br> Nuestros usuarios son todo el público que esté interesado en darle un nuevo uso a sus pertenencias, intercambiandolas por otras con alguien que sí las necesite. Además de ello, va dirigido a personas que deseen donar a ciertas organizaciones benéficas registradas en la plataforma.

    + **¿Dónde encaja nuestro producto en su trabajo o en su vida?**<br> Nuestro producto encaja en el estilo de vida de nuestros usuarios, al querer impulsar una forma de vida sostenible y una economía cíclica respecto a los bienes de las personas

    + **¿Cuándo y cómo se utiliza nuestro producto?**<br> Nuestro producto es usado cuando los usuarios sientan que ya no necesitan más una pertenencia y en vez de solo desecharla, darle un nuevo uso para alguien más, intercambiándose por algo que sí necesite o realizando donaciones a organizaciones benéficas para aquellos que más lo necesitan.


    + **¿Qué problemas resuelve nuestro producto?**<br>Cambiazo simplifica el intercambio y la donación de objetos, ofreciendo una plataforma segura y conveniente que promueve la reutilización y reduce el desperdicio. Con medidas de seguridad integradas, aborda las preocupaciones sobre transacciones fraudulentas, proporcionando una solución completa para una experiencia de intercambio confiable y sostenible.


    + **¿Qué características son importantes?**<br> Que sea fácil de usar, intuitiva y que contenga las funcionalidades necesarias para que la experiencia del usuario sea la mejor, con opción de filtros para la búsqueda de ciertos artículos y/o también la inclusión de un chat privado entre usuarios para que puedan comunicarse y coordinar el intercambio, si es que ambos están de acuerdo con las pertenencias que ofrecen y desean recibir.

    + **¿Cómo debe verse y comportarse nuestro producto?**<br> Nuestro producto debe tener una interfaz amigable para todos el público en general, incluir solo funcionalidades básicas y necesarias para no saturar a los usuarios con demasiada información.Además de ello debe mantenerse siempre con actualizaciones que vayan mejorando la optimización del proyecto.

 + **Business Outcomes:** 

    1. **Creo que nuestros usuarios necesitan** tener un medio seguro y fácil de usar para poder realizar intercambios y/o donaciones de manera sencilla y eficaz.

    2. **Estas necesidades se pueden resolver con** una aplicación web que tenga una interfaz intuitiva y que ofrezca que usuarios del Perú puedan realizar publicaciones de intercambio de sus pertenencias y solicitar cierto producto a cambio.

    3. **Nuestros usuarios iniciales son** el público en general del Perú que desee ser parte del cambio por un estilo de vida sostenible.

    4. **El valor #1 que un cliente quiere de nuestro servicio es que** ofrezca una forma rápida y sencilla de realizar publicaciones de intercambio y que tenga un sistema sólido para que los involucrados puedan coordinar el proceso respectivo con facilidad.

    5. **El usuario también puede obtener beneficios adicionales como**  tener un número ilimitado de publicaciones sobre intercambios que pueda realizar, además de poder obtener un “Boost” diario para que sus publicaciones siempre tengan preferencia al momento que aparezca tras una búsqueda por algún otro usuario.

    6. **Vamos a adquirir la mayoría de nuestros clientes a través de** publicidad en redes sociales tales como Instagram, Tiktok y Facebook, con una estrategia que promocione principalmente el impacto positivo que generaría el aplicar esta práctica de reutilización en el medio ambiente a largo plazo.

    7. **Haremos dinero a través de** ofrecer una suscripción premium que ofrecerá ciertos beneficios que hagan de su experiencia en CambiaZo mucho más satisfactoria y fácil.

    8. **Nuestras competencias principales son** grupos de Facebook que se dedican al intercambio, Me Sirve, HazTruequing y Trueques.

    9. **Los venceremos debido a** las funcionalidades que incluimos en nuestra propuesta de solución, además de la propia diferenciación de CambiaZo que tiene como logo principal, el ser un impulso para un cambio en la sociedad, el tener un estilo de vida sostenible.

    10. **Nuestro mayor riesgo es** que los usuarios no encuentren intercambios justos y puedan llegar a frustrarse por ello.

    11. **Resolveremos esto a través de** un proceso de verificación y control sobre la información que cada usuario coloca al momento de hacer un intercambio, para que no haya inconvenientes de posibles intercambios injustos o de broma.

#### 1.2.2.3 Lean UX Hypothesis Statements
**Creemos que** al tener una plataforma sólida **para**  poder realizar publicaciones de intercambios, los usuarios podrán contribuir con la metodología de una economía cíclica y de formar parte de un estilo de vida sostenible.<br>
**Sabremos que es cierto** cuando las estadísticas de cuántos intercambios se van realizando al día sean más de 30, esto demostrará que nuestra propuesta de solución realmente está fomentando la reutilización de los objetos de las personas en general.

**Creemos que**  permitir la interacción entre los usuarios al momento de mostrar interés por un artículo, ayudará a que puedan coordinar el intercambio de mejor manera <br>**Sabremos que lo habremos logrado**  cuando se refleje a través de los comentarios, que más del 50% de los usuarios resalte el sistema de comunicación entre usuarios, previo al intercambio.


**Creemos que**  al tener la opción de realizar donaciones a personas de escasos recursos económicos, facilitará a los usuarios que deseen donar objetos que ya no utilizan, a hacerlo y a contribuir con este acto solidario.<br>**Sabremos que esto es cierto**  cuando la cantidad de usuarios que han donado a través de nuestra plataforma, supere el 10% de usuarios registrados dentro de la aplicación cada mes.



#### 1.2.2.4 Lean UX Canvas
La aplicación **CambiaZo**  es una plataforma digital diseñada para que los usuarios puedan deshacerse de los objetos que ya no desean tener, intercambiándolos por otros artículos que desean de otros usuarios. Además, tiene como objetivo principal convertirse en la plataforma digital líder de intercambio de productos, promoviendo una vida consciente y sostenible a nivel mundial.

<table>
    <tr>
        <td valign="top" >
            <div align="center"> 
                <b>Problema de negocios</b> 
            </div><br>
            <p>El mayor factor de todo esto es la falta de accesibilidad y sencillez a la hora de buscar la forma de intercambiar bienes.<br><br>¿Cómo podemos crear una forma sencilla de encontrar personas que</p><br>
        </td>
        <td rowspan="2" valign="top">
            <div align="center"> 
                <b>Ideas de las soluciones</b> 
            </div><br>
            <p>Una aplicación con la cual se pueda realizar intercambios de productos. Además de tener un apartado donde los usuarios puedan registrar los objetos que deseen donar.<br><br> En caso el usuario no considere conveniente el intercambio, tiene la opción de cancelarlo y seguir buscando a otros usuarios.
            </p>
        </td>
            <td valign="top">
            <div align="center"> 
                <b>Resultados Comerciales</b> 
            </div><br>
            <p>Priorizar que los usuarios estén conformes con los intercambios realizados.<br><br>Obtener un financiamiento adicional para el crecimiento de la empresa.<br><br>Aumentar el alcance de la aplicación a través de las redes sociales.</p>
            </td>
        </tr>
    <tr>
        <td valign="top">
            <div align="center"> 
                <br><b>Usuarios y Clientes</b> 
            </div><br>
            <p>Personas que desean intercambiar objetos que ya no usan.</p>
        </td>
        <td valign="top">
            <div align="center"> 
                <br><b>Beneficios del usuario</b> 
            </div><br> 
            <p>Ahorro de dinero.<br><br>Deshacerse de objetos que ya no desean.<br><br>Obtención de nuevos artículos.<br><br></p>
        </td>
    </tr>
    <tr>
        <td valign="top">
            <div align="center"> 
                <br><b>Hipótesis</b> 
            </div><br>
            <p>Creemos que con nuestra aplicación, ayudaremos a promover la metodología de economía cíclica y un estilo de vida sostenible.<br><br>Creemos que al utilizar nuestra aplicación, las personas podrán realizar fácilmente el intercambio de sus objetos que ya no desean.</p><br>
        </td>
        <td valign="top">
            <div align="center"> 
                <br><b>¿Qué es lo más importante que necesitamos aprender primero? </b> 
            </div><br>
            <p>Conocer las preguntas más comunes de los usuarios.<br><br>Conocer las características más importantes de los productos.<br><br>Implementar medidas de seguridad sólidas para proteger los datos de los usuarios.</p><br>
        </td>
        <td valign="top">
            <div align="center"> 
                <br><b>¿Cuál es la menor cantidad de trabajo que necesitamos hacer para resolver las dudas y para hacer lo siguiente más importante?</b> 
            </div><br>
            <p>Dejar una opción para que los usuarios puedan dejar sus comentarios en general sobre el uso de la aplicación e ideas de cómo mejorarla.<br><br>Realizar encuestas mensualmente para conocer el nivel de satisfacción de nuestros usuarios con la aplicación.</p><br>
        </td>
    </tr>
</table>

## 1.3 Segmentos Objetivo
Esta sección incluye la descripción de los segmentos asociados al dominio del problema, incluyendo características geográficas y demográficas. Por lo tanto, con el fin de desarrollar un producto que satisfaga las necesidades de nuestros clientes, TechZo se enfocará en los siguientes segmentos de la población:
+ **Personas adultas que desean obtener nuevos artículos (Intercambiadores):**<br>
Las personas mayores de edad pueden usar “CambiaZo” para deshacerse de los productos que ya no desean tener y adquirir nuevos artículos de su interés.
    + **Características demográficas:** Personas entre 18 y 45 años de edad que poseen artículos que ya no utilizan ni desean, y están interesados en intercambiarlos por otros que sí les interesen o necesiten.<br>
    + **Características geográficas:** Personas que residen en Perú.<br><br>


+ **Personas adultas que desean donar artículos que ya no utilizan (Donantes):**<br>
“Cambiazo” es fundamental como herramienta para realizar donaciones, ya que permite que personas de escasos recursos puedan recibir donaciones de objetos de personas que ya no utilizan sus artículos y desean donarlos.
    + **Características demográficas:** Personas entre 15 y 60 años de edad con la voluntad de donar objetos propios que ya no utilizan a personas de escasos recursos económicos.
    + **Características geográficas:** Personas que residen en Perú.<br><br>


---

# Capítulo II: Requirements Elicitation & Analysis


## 2.1 Competidores

En esta sección se identificarán los mejores referentes para posteriormente realizar un análisis competitivo que nos ayudará a saber nuestro posicionamiento y el valor agregado que ofreceremos en el mercado. 

Según la investigación, se descubrieron apps webs y/o aplicaciones similares. Sin embargo, estamos considerando tres competidores directos o indirectos que se parezcan más a nuestra startup.

* **Trueques.com**<br>
Plataforma que ofrece una amplia gama de servicios de intercambio, incluidos intercambios de servicios y artículos de segunda mano. Los usuarios pueden buscar y publicar ofertas de intercambio, así como participar en eventos y actividades comunitarias relacionadas con el intercambio.

* **HazTruequing**<br>
Plataforma en línea que permite a los usuarios intercambiar servicios y artículos de segunda mano de manera fácil y segura. Los usuarios pueden publicar lo que tienen disponible para el intercambio y buscar lo que necesitan, creando así una comunidad de intercambio activa y diversa.


* **Me Sirve**<br>
Aplicación móvil que ofrece una forma conveniente de intercambiar y adquirir artículos de segunda mano. Los usuarios pueden publicar lo que tienen para intercambiar, buscar lo que necesitan y comunicarse directamente con otros usuarios para concretar los intercambios.

### 2.1.1 Análisis Competitivo

En esta sección se realizará el análisis competitivo de los competidores identificados en la sección inicial con el objetivo de tener una idea más clara sobre nuestro producto frente a los competidores y aprender para mejorar nuestro producto.

<table>
<thead>
  <tr>
    <th colspan="6">Competitive Analysis Landscape<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td colspan="2">¿Por qué llevar a cabo este análisis?</td>
    <td colspan="4">Este análisis se lleva a cabo para poder investigar, analizar y comparar el comportamiento de los competidores directos o indirectos en el mercado</td>
  </tr>
  <tr>
    <td colspan="2">
        <div align="center">
    		Nombre
		</div>
    </td>
    <td>
		<div align="center">
    		Cambiazo<br>
		</div>
	</td>
    <td>
		<div align="center">
    	    Trueques.com
		</div>
	</td>
    <td>
			<div align="center">
    		Haztruequing
			</div>
		</td>
    <td>
			<div align="center">
    		Me Sirve
			</div>
		</td>
  </tr>
  <tr>
    <td colspan="2">
        <div align="center">
    		Logo
		</div>
    </td>
    <td>
			<div align="center">
				<img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/logo-cambiazo.PNG?raw=true" alt="Cambiazo logo" width="150">
			</div>
		</td>
    <td>
			<div align="center">
				<img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Competitors/logo-trueques.PNG?raw=true" alt="Trueques.com logo" width="150">
			</div>
		</td>
    <td>
			<div align="center">
				<img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Competitors/logo-haztruequing.png?raw=true" alt="Haztruequing logo" width="150">
			</div>
		</td>
    <td>
			<div align="center">
				<img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Competitors/logo-mesirve.png?raw=true" alt="Me sirve logo" width="150">
			</div>
		</td>
  </tr>
  <tr>
    <td rowspan="2">Perfil</td>
    <td>Overview</td>
    <td>App Web que conecta a personas interesadas en darle un nuevo uso a sus pertenencias mediante intercambios o donaciones, enfocándose en la sostenibilidad y la economía circular.</td>
    <td>Página Web para intercambio de bienes y servicios entre usuarios, fomentando la economía colaborativa y la reutilización de recursos.</td>
    <td>Plataforma para intercambiar servicios y artículos de segunda mano de manera gratuita, promoviendo un estilo de vida sostenible y consciente.</td>
    <td>App para intercambiar bienes y servicios de manera segura y eficiente, promoviendo la reutilización y la solidaridad entre usuarios.</td>
  </tr>
  <tr>
    <td>Ventaja Competitiva <br>¿Qué valor ofrece a los clientes?</td>
    <td>Intercambio de productos o servicios. Donación de objetos a ONGs afiliadas</td>
    <td>Intercambio directo de bienes y servicios sin dinero, fomentando la reutilización y colaboración.</td>
    <td>Intercambio de servicios y artículos de segunda mano, promoviendo un estilo de vida sostenible.</td>
    <td>Intercambio bienes y servicios, promoviendo la reutilización y la solidaridad.
</td>
  </tr>
  <tr>
    <td rowspan="2">Perfiles de Marketing<br></td>
    <td>Mercado Objetivo<br></td>
    <td>Personas interesadas en  intercambiar o donar sus pertenencias.</td>
    <td>Personas que buscan intercambiar productos y servicios</td>
    <td>Personas interesados en intercambiar servicios y artículos de segunda mano</td>
    <td>Usuarios interesados en darle un nuevo propósito a sus pertenencias mediante intercambios.</td>
  </tr>
  <tr>
    <td>Estrategias de marketing</td>
    <td>Publicidad en Foros y Redes sociales</td>
    <td>Publicidad en redes sociales</td>
    <td>Publicidad en redes sociales</td>
    <td>Publicidad en redes sociales</td>
  </tr>

  <tr>
    <td rowspan="3">Perfil de Producto<br></td>
    <td>Productos &amp; Servicios</td>
    <td>Intercambiar bienes o servicios, donar a ONGs</td>
    <td>Intercambiar bienes o servicios</td>
    <td>Intercambiar bienes o servicios</td>
    <td>Intercambiar bienes o servicios</td>
  </tr>
  <tr>
    <td>Precios y Costos</td>
    <td>Free y Premium desde $2.99 por mes</td>
    <td>Free</td>
    <td>Free</td>
    <td>Free y Premium $2.99 por mes</td>
  </tr>
  <tr>
    <td>Canales de Distribución (Web y/o Móvil)</td>
    <td>Web y móvil</td>
    <td>Web</td>
    <td>Web</td>
    <td>Móvil</td>
  </tr>
  <tr>
    <td rowspan="4">Análisis SWOT</td>
    <td>Fortalezas</td>
    <td>Conexión intuitiva para intercambiar o donar objetos.<br><br>Amplia variedad de opciones para los usuarios.<br><br>Posibilidad de personalización en los intercambios.<br><br>Incorporación de automatización e innovación en la plataforma.</td>
    <td>Plataforma intuitiva para intercambiar bienes y servicios.<br><br>Amplia variedad de opciones disponibles.<br><br>Posibilidad de personalizar los intercambios.</td>
    <td>Plataforma confiable y amplia con una gran base de usuarios.<br><br>Compromiso con la sostenibilidad y la economía circular.</td>
    <td>Plataforma intuitiva y segura para intercambiar bienes y servicios.<br><br>Variedad de opciones disponibles para los usuarios.<br><br>Interfaz fácil de usar para una experiencia positiva.</td>
  </tr>
  <tr>
    <td>Debilidades</td>
    <td>Limitaciones en la disponibilidad de objetos y servicios.<br><br>Posibles dificultades técnicas en la gestión de transacciones y seguridad de datos.</td>
    <td>Posibles dificultades para garantizar la equidad en los intercambios.<br><br>Limitaciones técnicas que puedan afectar la funcionalidad.</td>
    <td>Posibles desafíos relacionados con la competencia de otras plataformas y la seguridad de las transacciones.</td>
    <td>Posibles desafíos con seguridad de transacciones y gestión de reclamos.</td>
  </tr>
  <tr>
    <td>Oportunidades</td>
    <td>Aprovechar la conciencia creciente sobre sostenibilidad y consumo responsable.<br><br>Desarrollar alianzas con ONGs para ampliar el impacto social.<br><br>Expandir la plataforma a nivel nacional e internacional.</td>
    <td>Expandir la plataforma para incluir nuevas categorías de productos y servicios.<br><br>Establecer alianzas con organizaciones benéficas para ampliar el impacto social.</td>
    <td>Expandir la plataforma a nivel nacional e internacional.</td>
    <td>Aprovechar la conciencia creciente sobre economía colaborativa y sostenibilidad.<br><br>Expandir la plataforma con más servicios y funciones para mejorar la experiencia.</td>
  </tr>
  <tr>
    <td>Amenazas</td>
    <td>Al ser una aplicación nueva, puede que no tenga la demanda esperada.<br><br>Competencia de otras plataformas.<br>Cambios en las preferencias del usuario.</td>
    <td>Mejor organizacion del sitio web<br><br>Cambios en las preferencias del usuario.</td>
    <td>Mejor interfaz, mas amigable e intuitiva<br><br>Cambios en las preferencias del usuario.</td>
    <td>Mejorar la seguridad de datos y privacidad de usuarios.<br><br>Cambios en las preferencias del usuario.</td>
  </tr>
</tbody>
</table>


### 2.1.2 Estrategias y tácticas frente a competidores

En esta sección se analizarán las estrategias y tácticas que se usarán para aprovechas las debilidades de la competencia y afrontar sus fortalezas. De la misma forma con las amenazas y oportunidades de la competencia.

Hemos empleado el análisis FODA para identificar las oportunidades y amenazas en el mercado, así como para evaluar nuestras fortalezas y debilidades internas. Este enfoque nos ha permitido concebir estrategias y tácticas adecuadas en consonancia con nuestro entorno y los recursos disponibles en base a nuestros dos segmentos objetivos.


**Estrategia de Diferenciación:** 

+ Para satisfacer las necesidades del **Segmento de Intercambiadores**, nos enfocamos en ofrecer una plataforma de intercambio intuitiva y dinámica que permita a los usuarios encontrar fácilmente los artículos deseados y realizar intercambios de manera rápida y segura. Implementaremos funciones avanzadas de búsqueda y filtros personalizables para facilitar la búsqueda de nuevos artículos.

+ Para el **Segmento de Donadores**, nos distinguimos al proporcionar una experiencia de donación gratificante y transparente. Estableceremos alianzas con organizaciones benéficas para ampliar las opciones de donación.

**Estrategia de Liderazgo en Costos:** 

+ Para el **Segmento de Intercambiadores**, nos comprometemos a mantener tarifas de intercambio competitivas y transparentes, y a ofrecer promociones especiales y descuentos para incentivar la participación activa en la plataforma.

+ En cuanto al **Segmento de Donaciones**, nuestra estrategia se centra en ofrecer una plataforma de donación sin costos ocultos ni tarifas adicionales. Nos comprometemos a garantizar que el proceso de donación sea completamente gratuito y accesible para todos los usuarios.

**Estrategia de Marketing:**

Para ambos segmentos, implementaremos una estrategia de marketing centrada en la sensibilización y la educación sobre los beneficios del intercambio y la donación. Desarrollaremos contenido informativo y atractivo que destaque las ventajas económicas, ambientales y sociales de participar en nuestra plataforma.

**Tácticas:**
- Creación de campañas publicitarias dirigidas a cada segmento objetivo para resaltar los beneficios específicos de la plataforma de intercambio y donación.
- Implementación de programas de referidos para incentivar la participación de usuarios existentes y expandir nuestra base de usuarios.
- Desarrollo de funciones adicionales en la plataforma, como sistemas de valoración y comentarios, para aumentar la confianza y la participación de los usuarios.
- Establecimiento de alianzas con organizaciones locales y empresas para promover eventos de intercambio y donación, generando así mayor visibilidad y compromiso con la comunidad.


## 2.2 Entrevistas

En esta sección se abordará la investigación en base a la información que se obtendrá de los segmentos entrevistados con el objetivo de conocer mejor a nuestros segmentos objetivos y aprender de ellos y sus procesos.



### 2.2.1 Diseño de entrevistas

**Preguntas sobre información personal**

*	¿Cuál es su nombre completo?
*	¿Qué edad tienes?
*	¿A qué te dedicas?
*	¿Cuál es tu estado civil?
*	¿En qué ciudad resides?
*	¿Eres extrovertido o calmado?
*	¿Eres una persona que toma decisiones analizando los hechos o te dejas llevar por tus sentimientos?
*	¿Qué smartphone posee? ¿Android o IOS?
*	¿Usas aplicaciones o programas en especial? ¿Cuáles?<br><br>


**Segmento objetivo 1:** Personas adultas que desean obtener nuevos artículos (Intercambiadores)

**Introducción:**

Buenos días/tardes/noches, mi nombre es [Nombre del entrevistador], y en esta ocasión tengo el agrado de poder entrevistar a [Nombre del entrevistado], quien es una persona que le gusta obtener nuevos objetos a través del intercambio.
Desde ya quiero agradecerle por su presencia y tiempo que me está brindando.

**Inmersión:**

1. ¿De qué forma se contacta con otras personas al momento de querer intercambiar alguno de los objetos que ya no usa?
2. ¿Cómo ha sido su experiencia previa con aplicaciones de intercambio de productos?
3. ¿Qué tipo de productos considera más viables para intercambiar a través de una plataforma web?

**Indagación:**

4. ¿Cuáles son las principales preocupaciones o dudas que tendría al utilizar una aplicación de intercambio de productos por primera vez?
5. ¿Qué características o funciones consideraría primordiales para sentirse seguro y cómodo al realizar intercambios en línea?
6. ¿Cómo cree usted que una plataforma web de intercambio de objetos podría fomentar la confianza entre los usuarios para realizar intercambios justos y seguros?
7. ¿Qué tipo de productos considera que tendrían mayor demanda por parte de personas de su edad y ubicación geográfica?

**Verificación:**

8. ¿Qué medidas tomaría para estar seguro de que los productos que está intercambiando cumplen con sus expectativas?
9. ¿Cómo cree que la comunidad de usuarios podría contribuir a garantizar la veracidad de los productos ofrecidos dentro de la plataforma?
10. ¿Qué fuentes utilizaría para verificar la confiabilidad de una plataforma de intercambios en línea como CambiaZo?

**Medición:**

11. ¿Qué beneficios espera obtener al utilizar una aplicación como CambiaZo en comparación con otros métodos de adquisición de productos?
12. ¿Cómo considera que las personas pueden contribuir al desarrollo de una comunidad más sostenible y consciente en su ciudad?
13. ¿Cuál considera que es el mayor desafío que enfrenta la sociedad en Lima en la actualidad para mantener un consumo consciente, y cómo cree que podría tratarse?

**Cierre:**

Bueno esto ha sido todo por esta ocasión, una vez más quisiera agradecerle por su tiempo, muchas gracias y hasta luego.<br><br>

**Segmento objetivo 2:** Personas adultas que desean donar artículos que ya no utilizan (Donantes)

**Introducción:**

Buenos días/tardes/noches, mi nombre es [Nombre del entrevistador], y en esta ocasión tengo el agrado de poder entrevistar a [Nombre del entrevistado], quien es una persona que le gusta realizar donaciones a personas de escasos recursos.
Desde ya quiero agradecerle por su presencia y tiempo que me está brindando.

**Inmersión:**

1. ¿De qué forma ha realizado donaciones a personas con escasos recursos económicos?
2. ¿Cómo ha sido su experiencia previa con la donación de artículos a personas necesitadas o a organizaciones benéficas?
3. ¿Qué tipo de artículos consideraría más adecuados para donar a través de una plataforma como CambiaZo?

**Indagación:**

4. ¿Cuáles son las principales preocupaciones que tendría al utilizar una aplicación como CambiaZo por primera vez?
5. ¿Qué funciones o características buscaría en una plataforma web al momento de querer realizar una donación en línea?
6. ¿Cómo cree que una plataforma como CambiaZo podría aumentar la cantidad de donaciones en el Perú?

**Verificación:**

7. ¿Cómo podría una plataforma como CambiaZo garantizar la transparencia y autenticidad de las donaciones realizadas?
8. ¿Qué importancia le otorgaría a la posibilidad de seguir el destino de sus donaciones y conocer el impacto que tienen en la comunidad receptora?
9. ¿Qué criterios utilizaría para verificar la confiabilidad y legitimidad de una plataforma de donaciones en línea como CambiaZo?

**Medición:**

10. ¿Qué beneficios espera obtener al realizar donaciones utilizando CambiaZo en comparación con otros métodos de donación tradicionales?
11. ¿Cómo mediría el impacto de sus donaciones a través de una plataforma web como CambiaZo en términos de ayudar a personas necesitadas?
12. ¿Qué cambios o mejoras le gustaría ver en la funcionalidad de CambiaZo para que se convierta en una herramienta más efectiva para donar artículos?
13. ¿Cómo cree que el uso de aplicaciones en las que puede donar, como CambiaZo, podría contribuir al desarrollo de una comunidad más solidaria y conectada en Lima?

**Cierre:**

Bueno esto ha sido todo por esta ocasión, una vez más quisiera agradecerle por su tiempo, muchas gracias y hasta luego.<br><br>



### 2.2.2 Registro de entrevistas

En esta sección presentamos los registros de las entrevistas que hicimos para cada segmento objetivo de nuestra aplicación.


**Segmento Intercambiadores**<br>

<table style="undefined;table-layout: fixed; width: 910px">
<colgroup>
<col style="width: 220px">
<col style="width: 700px">
</colgroup>
<thead>
  <tr>
    <th colspan="2">Entrevista #1<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Jorge Manuel</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Pacheco Huanca</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>20 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>La Molina</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Google Chrome, Zoom</td>
  </tr>
  <tr>
    <td>Motivacion</td>
    <td>Obtener objetos deseados de manera más sencilla</td>
  </tr>
  <tr>
    <td>Frustracion</td>
    <td>Dificultades en obtener objetos de calidad a través de grupos de Facebook</td>
  </tr>
  <tr>
    <td>Tecnologias</td>
    <td>Laptop Windows, Smartphone Android</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Google Chrome</td>
  </tr>
  <tr>
    <td>Evidencia</td>
    <td><div align="center">
				<img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Interviews/entrevista-Jorge-Pacheco.PNG?raw=true" alt="Entrevista Jorge Pacheco">
			</div></td>
  </tr>
  <tr>
    <td>Link</td>
    <td>
		<p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202214059_upc_edu_pe/EfemrVI6sklMmFq2I8QUaPcBSw6TXKgSJ5Nwc-Yu2_BztQ?e=abYbaJ&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D" title="Title">Microsoft Stream</p>
		</td>
  </tr>
  <tr>
    <td>Duracion<br></td>
    <td>
		 00:00 min - 4:59 min 
		</td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td>En la entrevista con Jorge Pacheco, logramos conocer acerca de su experiencia al querer realizar intercambios, los cuales realiza por grupos de Facebook o con amigos pero no siempre logra intercambiar u obtener los objetos que desea o en la calidad que los espera. Además, indicó que le gustaría tener la opción de tener una aplicación como CambiaZo para realizar intercambios, ya que considera que sería una forma más sencilla de realizar intercambios. También agregó que le gustaría que en la aplicación se implemente una opción que muestre los valores de los objetos para poder realizar un intercambio justo, un chat entre usuarios, y reseñas de los usuarios que han realizado intercambios. Comentó adicionalmente que los miedos que tiene al usar este tipo de aplicaciones o realizar intercambios, es que le entreguen algún producto el cuál no era el que se esperaba o en mal estado, y que desea que se mantenga con privacidad los datos personales de cada usuario.<br>Finalmente indicó que sí considera que en Lima se puede contribuir con el desarrollo de una comunidad más sostenible al reutilizar las cosas, siendo honestos y justos.
</td>
  </tr>
</tbody>
</table>


<table style="undefined;table-layout: fixed; width: 910px">
<colgroup>
<col style="width: 220px">
<col style="width: 700px">
</colgroup>
<thead>
  <tr>
    <th colspan="2">Entrevista #2<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Edu Orlando</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Gutierrez Vasquez</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>19 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>La Molina</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Zoom, Discord</td>
  </tr>
  <tr>
    <td>Motivacion</td>
    <td>Seguridad y calidad en intercambios de productos</td>
  </tr>
  <tr>
    <td>Frustracion</td>
    <td>Limitaciones de seguridad y calidad en Facebook</td>
  </tr>
  <tr>
    <td>Tecnologias</td>
    <td>Laptop Windows, Smartphone Android</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Google Chrome, Firefox</td>
  </tr>
    <tr>
    <td>Evidencia</td>
    <td>
      <div align="center">
				<img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Interviews/entrevista-Edu-Gutierrez.PNG?raw=true" alt="Entrevista Edu Gutierrez">
			</div>
    </td>
  </tr>

  <tr>
    <td>Link</td>
    <td>
		<p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202214059_upc_edu_pe/EfemrVI6sklMmFq2I8QUaPcBSw6TXKgSJ5Nwc-Yu2_BztQ?e=abYbaJ&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D" title="Title">Microsoft Stream</p>
		</td>
  </tr>
  <tr>
    <td>Duracion<br></td>
    <td>
		 5:00 min - 9:55 min 
		</td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td>
    En la entrevista con Edu, se revelaron detalles sobre su experiencia y preferencias en cuanto a realizar intercambios de objetos. Edu suele contactarse con otras personas para intercambiar objetos a través de Facebook y WhatsApp, pero encuentra limitaciones en estas plataformas en términos de seguridad y calidad de los productos.Considera que una plataforma como Cambiazo sería de gran ayuda para simplificar este proceso. Además, mencionó que le gustaría que la plataforma implementara funciones como un sistema de verificación de identidad y calidad de los productos, así como un sistema de evaluaciones entre usuarios para garantizar la confianza y seguridad en los intercambios. Edu también señaló que los productos de ocio y entretenimiento tendrían mayor demanda entre personas de su edad y ubicación geográfica. <br>En cuanto a sus preocupaciones, destacó la seguridad de las transacciones y la calidad de los productos ofrecidos. Para garantizar la calidad de los productos, Edu se basaría en las descripciones detalladas, las fotos proporcionadas por los usuarios y las evaluaciones de otros usuarios. También considera que la comunidad de usuarios podría contribuir a garantizar la veracidad de los productos ofrecidos dentro de la plataforma mediante la retroalimentación honesta y la denuncia de prácticas fraudulentas.<br>En términos de beneficios esperados al utilizar una aplicación como Cambiazo, Edu espera una mayor variedad de productos y una experiencia de intercambio más segura. Además, considera que el intercambio de productos usados puede contribuir al desarrollo de una comunidad más sostenible y consciente en su ciudad. 

</td>
  </tr>
</tbody>
</table>

<table style="undefined;table-layout: fixed; width: 910px">
<colgroup>
<col style="width: 220px">
<col style="width: 700px">
</colgroup>
<thead>
  <tr>
    <th colspan="2">Entrevista #3<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Marcela Moraima</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Perinango Castro</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>18 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>Ate</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Zoom</td>
  </tr>
  <tr>
    <td>Motivacion</td>
    <td>Relizar intercambios seguros</td>
  </tr>
  <tr>
    <td>Frustracion</td>
    <td>No obtener lo que busca al realizar intercambios a través de Facebook.</td>
  </tr>
  <tr>
    <td>Tecnologias</td>
    <td>iPhone, Laptop Windows</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Google Chrome</td>
  </tr>
    <tr>
    <td>Evidencia</td>
    <td>
      <div align="center">
				<img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Interviews/entrevista-Marcela-Moraima.PNG?raw=true" alt="Entrevista Marcela Perinango">
			</div>
    </td>
  </tr>
  <tr>
    <td>Link</td>
    <td>
		<p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202214059_upc_edu_pe/EfemrVI6sklMmFq2I8QUaPcBSw6TXKgSJ5Nwc-Yu2_BztQ?e=abYbaJ&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D" title="Title">Microsoft Stream</p>
		</td>
  </tr>
  <tr>
    <td>Duracion<br></td>
    <td>
		 9:56 min - 14:50 min 
		</td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td>En la entrevista con Marcela, pudimos conocer un poco más sobre su experiencia acerca de los intercambios, de los inconvenientes que ha tenido al no tener una plataforma como tal para poder realizarlos, ya que según su experiencia solo ha podido intercambiar objetos mediante grupos de WhatsApp o Facebook y que no fue una gran experiencia debido a que la plataforma no era la indicada para ello. Además de ello, profundizó más en el tema sobre las características que le gustaría tener si es que hubiera una plataforma sólida para poder realizar intercambios con otras personas. Una de las características que más resaltó, fue el hecho de incluir alguna garantía a los usuarios, ya que según lo que menciona, pueden haber casos en donde les entreguen productos defectuosos y los hagan pasar como totalmente funcionales y que resulte en una pérdida y frustración para el usuario, en vez de sentirse conforme con el intercambio. Para finalizar, nos habló un poco sobre su perspectiva de sí es que realmente aquí en Lima se está ampliando la cultura por un desarrollo sostenible, comentó que lamentablemente el Perú y sobre todo la capital, tiene un estilo de vida que está muy arraigada al consumismo y al desechar las cosas sin darle la oportunidad de darle utilidad a alguien que tal vez sí lo necesite
</td>
  </tr>
</tbody>
</table><br><br>


**Segmento Donadores**<br>

<table style="undefined;table-layout: fixed; width: 910px">
<colgroup>
<col style="width: 220px">
<col style="width: 700px">
</colgroup>
<thead>
  <tr>
    <th colspan="2">Entrevista #1<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Jeremy Joel</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Quispe Andia</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>19 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>San Juan de Lurigancho</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Zoom</td>
  </tr>
  <tr>
    <td>Motivacion</td>
    <td>Contribuir con los mas necesitados, donando alimentos y ropa</td>
  </tr>
  <tr>
    <td>Frustracion</td>
    <td>Preocupaciones sobre el destino de las donaciones.</td>
  </tr>
  <tr>
    <td>Tecnologias</td>
    <td>Computadora Windows, iPhone</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Firefox</td>
  </tr>
    <tr>
    <td>Evidencia</td>
    <td>
      <div align="center">
				<img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Interviews/entrevista-Jeremy-Quispe.PNG?raw=true" alt="Entrevista Jeremy Quispe">
			</div>
    </td>
  </tr>
  <tr>
    <td>Link</td>
    <td>
		<p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202214059_upc_edu_pe/EfemrVI6sklMmFq2I8QUaPcBSw6TXKgSJ5Nwc-Yu2_BztQ?e=abYbaJ&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D" title="Title">Microsoft Stream</p>
		</td>
  </tr>
  <tr>
    <td>Duración<br></td>
    <td>
		 14:51 min - 19:47 min 
		</td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td>En la entrevista con Jeremy Quispe, logramos conocer acerca de su experiencia al realizar donaciones a organizaciones benéficas, mencionando el impacto que tiene en las personas necesitadas para mejorar su calidad de vida. Indica que los artículos que le parecen más adecuados para donar a través de CambiaZo son alimentos, ropa y juguetes. Menciona que sus principales preocupaciones al utilizar por primera vez nuestra aplicación sería la seguridad de sus datos y la confiabilidad de la plataforma. Además considera que para aumentar la cantidad de donaciones en el país se pueden realizar campañas de sensibilización y colaboraciones con influencers para aumentar la visibilidad. También nos comenta que le parece muy importante seguir el destino de sus donaciones y el impacto que ha tenido. Finalmente, Jeremy indica que al usar CambiaZo espera tener una experiencia de donación más conveniente y directa, y que le parece que CambiaZo es una gran forma de fomentar la solidaridad al ofrecer de una manera más fácil de ayudar a los más necesitados en la comunidad.
</td>
  </tr>
</tbody>
</table>


<table style="undefined;table-layout: fixed; width: 910px">
<colgroup>
<col style="width: 220px">
<col style="width: 700px">
</colgroup>
<thead>
  <tr>
    <th colspan="2">Entrevista #2<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Hernan Emilio</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Morales Calderon</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>19 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>San Juan de Lurigancho</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Zoom,Word</td>
  </tr>
  <tr>
    <td>Motivacion</td>
    <td>Donar su ropa a personas necesitadas</td>
  </tr>
  <tr>
    <td>Frustracion</td>
    <td>Limitaciones de tiempo para buscar alguna ong</td>
  </tr>
  <tr>
    <td>Tecnologias</td>
    <td>Laptop Windows, Smartphone Android</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Google Chrome</td>
  </tr>
   <tr>
    <td>Evidencia</td>
    <td>
      <div align="center">
				<img src="https://github.com/TechZo-Organization/upc-pre-202401-si730-SW51-techzo-report/blob/main/Resources/Interviews/entrevista-Hernan-Morales.PNG?raw=true" alt="Entrevista Hernan Morales">
			</div>
    </td>
  </tr>
  <tr>
    <td>Link</td>
    <td>
		<p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202214059_upc_edu_pe/EfemrVI6sklMmFq2I8QUaPcBSw6TXKgSJ5Nwc-Yu2_BztQ?e=abYbaJ&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D" title="Title">Microsoft Stream</p>
		</td>
  </tr>
  <tr>
    <td>Duracion<br></td>
    <td>
		 19:48 min - 23:35 min 
		</td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td>
    Durante la entrevista, Hernan compartió su experiencia y perspectiva sobre el proceso de donación a través de su participación en actividades de caridad y su interacción con plataformas dedicadas a esta causa. Destacó su compromiso con contribuciones significativas, incluyendo alimentos no perecederos, vestimenta en buen estado y juguetes, los cuales destinó a instituciones benéficas locales y hogares de acogida para niños desfavorecidos en su comunidad.Asimismo, Hernán enfatizó la importancia de la seguridad de los datos personales y la confiabilidad de los sistemas utilizados en estas plataformas, destacando la necesidad de contar con funcionalidades de protección que aseguren la integridad de la información personal y financiera de los donantes.Además, manifestó su interés en seguir de cerca el progreso de sus donaciones y su impacto en la comunidad, así como en mantenerse informado sobre el prestigio de la plataforma, su transparencia en la gestión de fondos y los testimonios de otros usuarios. Hernán expresó su deseo de una experiencia de donación más accesible y sencilla, y sugirió mejoras en la interfaz de usuario y una mayor variedad de opciones de donación específicas para fomentar la solidaridad y proporcionar un medio más fácil para ayudar a quienes más lo necesitan en la comunidad.


</td>
  </tr>
</tbody>
</table>

<table style="undefined;table-layout: fixed; width: 910px">
<colgroup>
<col style="width: 220px">
<col style="width: 700px">
</colgroup>
<thead>
  <tr>
    <th colspan="2">Entrevista #3<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Nombre</td>
    <td>Carlos Arturo</td>
  </tr>
  <tr>
    <td>Apellidos</td>
    <td>Adrianzen Flores</td>
  </tr>
  <tr>
    <td>Edad</td>
    <td>20 años</td>
  </tr>
  <tr>
    <td>Distrito</td>
    <td>Miraflores</td>
  </tr>
  <tr>
    <td>Aplicaciones Usadas</td>
    <td>Zoom, Discord</td>
  </tr>
  <tr>
    <td>Motivacion</td>
    <td>Donar a lo mas necesitados a traves de la iglesias</td>
  </tr>
  <tr>
    <td>Frustracion</td>
    <td>Experimenta dificultades al llevar un canasto lleno de ropa para donar.</td>
  </tr>
  <tr>
    <td>Tecnologias</td>
    <td>Smatphone Android, Laptop Windows</td>
  </tr>
	<tr>
    <td>Browsers</td>
    <td>Firefox</td>
  </tr>
   <tr>
    <td>Evidencia</td>
    <td>
			<div align="center">
				<img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Interviews/entrevista-Arturo-Adrianzen.PNG?raw=true" alt="Entrevista Arturo Adrianzen">
			</div>
    </td>
  </tr>
  <tr>
    <td>Link</td>
    <td>
		<p><a target="_blank"  href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202214059_upc_edu_pe/EfemrVI6sklMmFq2I8QUaPcBSw6TXKgSJ5Nwc-Yu2_BztQ?e=abYbaJ&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D" title="Title">Microsoft Stream</p>
		</td>
  </tr>
  <tr>
    <td>Duración<br></td>
    <td>
		 23:36 min - 28:51 min 
		</td>
  </tr>
  <tr>
    <td>Resumen</td>
    <td>Durante nuestra conversación con Arturo, exploramos su experiencia en intercambios y los desafíos que ha enfrentado al no tener una plataforma dedicada para realizarlos. Arturo compartió sus vivencias al realizar donaciones a la iglesia, describiendo las dificultades que encontró al llevar un canasto lleno de ropa, lo cual consideró una tarea tediosa. Propuso la idea de que, para facilitar el proceso de donación de objetos, sería conveniente que alguien se encargará de recogerlos, evitando así la molestia de tener que trasladarse hasta el lugar de donación. Además, resaltó la importancia de garantizar seguridad para los usuarios, sugiriendo medidas como la presentación de una foto que confirme la realización de la donación, con el fin de evitar cualquier tipo de desconfianza. Arturo realiza una sugerencia final y significativa para Cambiazo, el cual, sería crear conciencia sobre la importancia de cada objeto donado para las personas necesitadas. Esto podría lograrse mediante la divulgación de testimonios conmovedores de aquellos que se han visto directamente afectados por estas donaciones, lo que, a su vez, podría inspirar a más personas a contribuir y seguir apoyando esta noble causa de forma continua.
</td>
  </tr>
</tbody>
</table><br><br>

### 2.2.3 Análisis de entrevistas

En esta sección presentaremos el análisis de cada entrevista realizada por cada segmento objetivo. Con el fin de tener una información concisa para el desarrollo de nuestra aplicación.

**Segmento objetivo 1:** Personas adultas que desean obtener nuevos artículos (Intercambiadores).<br>


Lo que hemos podido notar después de realizar las entrevistas al primer segmento, es que siempre que desean realizar intercambios de objetos usan redes sociales como WhatsApp y Facebook, sin embargo su experiencia no ha sido buena, ya que suelen tener problemas o inseguridades al realizarlo, ya que no tienen ninguna garantía de que el producto que les va a llegar es el que desean o está en buen estado. Los 3 usuarios consideran que CambiaZo sería una gran herramiento y les ayudaría mucho para poder realizar trueques, las principales funciones que sugirieron añadir son que se muestre un valor aproximado del producto, reseñas de los usuarios, sistema de verificación de identidad y calidad de los productos y añadir una garantía a los usuarios. Finalmente, todos los entrevistados consideran que sí es posible que CambiaZo ayude a que Lima avance en el desarrollo para ser una comunidad más sostenible.

**Análisis por medio de herramientas estadísticas:**


<div align="center">
	<img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Stadistics/segmento-objetivo-1-grafica-1.PNG?raw=true" alt="Estadistica 1">
</div>


Las respuestas de nuestros entrevistados evidencian que sería beneficioso y útil para una gran cantidad de la población, lo cual también se comprueba con un estudio realizado del año 2015 al 2017 por la Universidad Nacional del Altiplano, Puno, en el cuál se obtuvo que el motivo principal por el cual las personas realizan trueques es por la falta de dinero.


<div align="center">
	<img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Stadistics/segmento-objetivo-1-grafica-2.PNG?raw=true" alt="Estadistica 2"><br><br>
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Stadistics/segmento-objetivo-1-grafica-3.PNG?raw=true" alt="Estadistica 3"><br><br>
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Stadistics/segmento-objetivo-1-grafica-4.PNG?raw=true" alt="Estadistica 4"><br><br>
</div>

Como se puede apreciar en los gráficos, nuestros entrevistados suelen usar las redes sociales para intercambiar objetos, sin embargo el 100% de los entrevistados no se siente seguro al utilizar estos medios, ya que todos han tenido alguna mala experiencia al utilizarlos para querer realizar un trueque.


<div align="center">
	<img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Stadistics/segmento-objetivo-1-grafica-5.PNG?raw=true" alt="Estadistica 5"><br><br>
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Stadistics/segmento-objetivo-1-grafica-6.PNG?raw=true" alt="Estadistica 6"><br><br>
</div>

Finalmente, podemos observar que nuestros entrevistados suelen realizar intercambios muy frecuentemente, y que todos estarían dispuestos a utilizar CambiaZo como su medio principal para realizar trueques.<br><br>


**Segmento objetivo 2:** Personas adultas que desean donar artículos que ya no utilizan (Donantes).<br>


Al finalizar de realizar las entrevistas a nuestro segundo segmento objetivo, logramos identificar que cada vez que han querido realizar donaciones, han atravesado por situaciones un poco tediosas, como el tener que llevar su donación hasta lugares lejanos, no encontrar una forma sencilla de realizar la donación y no obtener el seguimiento de su donación o una evidencia que se realizó la donación. Por lo que consideran que CambiaZo sería una gran herramienta para brindar ayuda a personas de escasos recursos, ya que de esta forma consideran que sería más simple, sencillo y seguro de hacerlo, justo por ello sugirieron que se haga un rastreamiento de la donación y una evidencia cuando llegue a su lugar de destino. Además indicaron que sería de gran ayuda realizar campañas de sensibilización y colaboraciones con influencers, para que de este modo, más personas se logren enterar acerca de cómo CambiaZo está ayudando a transformar la vida de las personas con necesidades económicas, y consecuentemente, más personas se sumen y comienzen a donar o donen más seguido.

**Análisis por medio de herramientas estadísticas:**



<div align="center">
	<img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Stadistics/segmento-objetivo-2-grafica-1.PNG?raw=true" alt="Estadistica 7"><br><br>
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Stadistics/segmento-objetivo-2-grafica-2.PNG?raw=true" alt="Estadistica 8"><br><br>
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Stadistics/segmento-objetivo-2-grafica-3.PNG?raw=true" alt="Estadistica 9"><br><br>
</div>

Según la encuesta realizada a nuestros entrevistados, obtuvimos que suelen donar mensual o anualmente, además todos consideran que el proceso para realizar donaciones no es sencillo y la mayoría ha tenido algún inconveniente al momento de querer realizar alguna donación.

<div align="center">
	<img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Stadistics/segmento-objetivo-2-grafica-4.PNG?raw=true" alt="Estadistica 10"><br><br>
</div>

Podemos apreciar que la mayoría de nuestros entrevistados considera que los objetos más adecuados para donar son juguetes y ropa.

<div align="center">
	<img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Stadistics/segmento-objetivo-2-grafica-5.PNG?raw=true" alt="Estadistica 11"><br><br>
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Stadistics/segmento-objetivo-2-grafica-6.PNG?raw=true" alt="Estadistica 12"><br><br>
</div>

Finalmente, todos los entrevistados indicaron a través de la votación que estarían dispuestos a utilizar CambiaZo como su principal medio de donación, y que gracias a CambiaZo aumentaría la frecuencia de donaciones que realizan, lo cuál sería ampliamente beneficioso para las personas de escasos recursos económicos.



## 2.3 Needfinding

Para crear un producto que cumpla con las necesidades específicas de un cliente, Cambiazo se dedicará a identificar los User persona, User Task Matrix, User Journey Maps y Empathy Mapping.

### 2.3.1 User Personas

Después de analizar las entrevistas de nuestro segmento objetivo, nuestra tarea es definir el perfil del usuario ideal con el que estamos tratando. Hemos elaborado los perfiles de usuario teniendo en cuenta las personalidades y cualidades identificadas en cada entrevista. A continuación, se presentan las user personas resultantes de la investigación:

<b>Usuario Intercambiador</b><br>

<div align="center">

[![User Persona 1](https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/NeedFinding/user-persona-1.PNG?raw=true)](https://uxpressia.com/w/ODLU6/p/WUMVh)
</div>

Enlace: [User Persona en UXPRESSIA](https://uxpressia.com/w/ODLU6/p/WUMVh)
<br><br>

<b>Usuario Donador</b><br>

<div align="center">

[![User Persona 2](https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/NeedFinding/user-persona-2.PNG?raw=true)](https://uxpressia.com/w/5DZd7/p/C7wKs)
</div>

Enlace: [User Persona en UXPRESSIA](https://uxpressia.com/w/5DZd7/p/C7wKs)
<br><br>



### 2.3.2 User Task Matrix

Con el fin de elaborar un Task Matrix adecuado para el proyecto, se han considerado los dos segmentos objetivo, producto del análisis de entrevistas, es decir, Intercambiador y Donador.



<b>Usuario Intercambiador</b><br>

<div align="center">
<table style="undefined;table-layout: fixed; width: 636px">
<colgroup>
<col style="width: 263px">
<col style="width: 150px">
<col style="width: 150px">
</colgroup>
<thead>
  <tr>
    <th rowspan="2"><div align="center">USER TASK</div><br></th>
    <th colspan="2"><div align="center">Intercambiador <br>Carlos Flores<br></div></th>
   
  </tr>
  <tr>
    <th>Frecuencia</th>
    <th>Importancia</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Buscar objetos para intercambiar<br></td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Contactar Usuarios para Intercambiar<br></td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Coordinar Condiciones del Intercambio<br></td>
    <td>Alta</td>
    <td>Media</td>
  </tr>
  <tr>
    <td>Confirmar Acuerdo de Intercambio<br></td>
    <td>Media</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Evaluar Experiencia de Intercambio<br></td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
</tbody>
</table>
</div><br><br>

<b>Usuario Donador</b><br>

<div align="center">
<table style="undefined;table-layout: fixed; width: 636px">
<colgroup>
<col style="width: 263px">
<col style="width: 150px">
<col style="width: 150px">
</colgroup>
<thead>
  <tr>
    <th rowspan="2"><div align="center">USER TASK</div><br></th>
    <th colspan="2"><div align="center">Donador <br>Mariana Okinawa<br></div></th>
   
  </tr>
  <tr>
    <th>Frecuencia</th>
    <th>Importancia</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Buscar organizaciones para donar<br></td>
    <td>Media</td>
    <td>Alta</td>
  </tr>
  <tr>
     <td>Seleccionar Artículo para Donar<br></td>
    <td>Media</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Coordinar Entrega de Donación<br></td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Preparar Artículos para Donación<br></td>
    <td>Media</td>
    <td>Media</td>
  </tr>
  <tr>
    <td>Entregar Donación a la Organización<br></td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
</tbody>
</table>
</div>

### 2.3.3 User Journey Mapping

En esta sección, se desarrollan los User Journey Maps para cada User Persona, proporcionando una visión completa del recorrido del usuario desde el inicio hasta el final. Estos mapas representan la situación actual (As-Is) de cada segmento, sin ofrecer soluciones. 

<b>Segmento Intercambiadores</b><br>

Mediante este artefacto se explicará y comprenderá como los usuarios del segmento Cliente realizan sus actividades para alcanzar sus objetivos desde su perspectiva.

<div align="center">

[![User Journey Mapping.](https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/NeedFinding/user-journey-map-1.PNG?raw=true)](https://uxpressia.com/w/ODLU6/m/85V7e)
</div>


Enlace: [User Journey Mapping en UXPRESSIA](https://uxpressia.com/w/ODLU6/m/85V7e)


<b>Segmento Donadores</b><br>

Mediante este artefacto se explicará y comprenderá como los usuarios del segmento Empresa realizan sus actividades para alcanzar sus objetivos desde su persepctiva.

<div align="center">

[![User Journey Mapping.](https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/NeedFinding/user-journey-map-2.PNG?raw=true)](https://uxpressia.com/w/ODLU6/m/ZJfdG)
</div>


Enlace: [User Journey Mapping en UXPRESSIA](https://uxpressia.com/w/ODLU6/m/ZJfdG)


### 2.3.4 Empathy Mapping

Lo siguiente a evaluar como parte del needfinding es a nuestros segmentos objetivos a través de empathy maps, con el objetivo de conocer mejor a nuestros segmentos objetivos e identificar sus necesidades profundas.

<b>Segmento Intercambiadores</b><br>

<div align="center">

[![Empathy Mapping.](https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/NeedFinding/empathy-map-1.PNG?raw=true)](https://uxpressia.com/w/ODLU6/p/lPmO3)
</div>


Enlace: [Empathy Mapping en UXPRESSIA](https://uxpressia.com/w/ODLU6/p/lPmO3)
<br>

<b>Segmento Donadores</b><br>

<div align="center">

[![Empathy Mapping.](https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/NeedFinding/empathy-map-2.PNG?raw=true)](https://uxpressia.com/w/ODLU6/p/pKfKi)
</div>


### 2.3.5 As-Is Scenario Mapping

En esta sección, abordaremos el As-Is Scenario Mapping para ambos segmentos, donde describiremos cómo deben configurarse las experiencias durante cada fase.<br><br>
<b>Segmento Intercambiadores</b><br>


<div align="center">

[![As-Is Scenario Mapping.](https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/As-Is/as-is-scenario-1.PNG?raw=true)](https://miro.com/welcomeonboard/QmU3aWdWM21SdGwzeFR6Tm90cUhkZG5mQW5ZZDNVMGJpTHJkSk9xaWU3U1ZvcnhLNjRJMnVJRFo4Z3J0bnNMWHwzNDU4NzY0NTU2Nzc0MzI2MzAxfDI=?share_link_id=453144500996)
</div>

Enlace: [As-Is Scenario Mapping en Miro](https://miro.com/welcomeonboard/QmU3aWdWM21SdGwzeFR6Tm90cUhkZG5mQW5ZZDNVMGJpTHJkSk9xaWU3U1ZvcnhLNjRJMnVJRFo4Z3J0bnNMWHwzNDU4NzY0NTU2Nzc0MzI2MzAxfDI=?share_link_id=453144500996)
<br>

<b>Segmento Donadores</b><br>

<div align="center">

[![As-Is Scenario Mapping.](https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/As-Is/as-is-scenario-2.PNG?raw=true)](https://miro.com/welcomeonboard/QmU3aWdWM21SdGwzeFR6Tm90cUhkZG5mQW5ZZDNVMGJpTHJkSk9xaWU3U1ZvcnhLNjRJMnVJRFo4Z3J0bnNMWHwzNDU4NzY0NTU2Nzc0MzI2MzAxfDI=?share_link_id=453144500996)
</div>


Enlace: [As-Is Scenario Mapping en Miro](https://miro.com/welcomeonboard/QmU3aWdWM21SdGwzeFR6Tm90cUhkZG5mQW5ZZDNVMGJpTHJkSk9xaWU3U1ZvcnhLNjRJMnVJRFo4Z3J0bnNMWHwzNDU4NzY0NTU2Nzc0MzI2MzAxfDI=?share_link_id=453144500996)<br><br>


## 2.4 Ubiquitous Language
En esta sección, se establece un glosario de términos clave del dominio de negocio, conforme al enfoque de Ubiquitous Language propuesto por Eric Evans en Domain-Driven Design. Este glosario proporciona definiciones claras y sin ambigüedades de los conceptos utilizados en el ámbito específico del problema y la solución abordados, facilitando una comunicación efectiva entre todos los miembros del equipo.

+ **Subscription (Subscripción):** An arrangement where users sign up for a service or access to a product on a recurring basis, often for a specific duration, in exchange for certain benefits or features. Subscriptions typically involve the payment of a recurring fee, and they may offer various levels or tiers of access, each providing different features, benefits, or limitations. Users may subscribe to gain access to premium content, exclusive features, or enhanced functionality within the platform.


+ **Plan (Plan):** Different tiers or levels of subscription offering varying features, benefits, or limitations. Plans are structured to cater to the diverse needs and preferences of users, providing options that align with their usage patterns, budget constraints, or desired level of engagement. These plans may be designed to cater to different user segments, such as casual users, power users, or businesses, and they often dictate the scope of access and available features within the platform.


+ **Exchange (Intercambio):** The act of swapping objects between users, typically facilitated by the platform. Exchanges may involve the direct trade of items between users, where one user offers an object in exchange for another object offered by a different user. Alternatively, exchanges may involve indirect transactions facilitated by the platform, where users list objects they wish to exchange, and the platform matches them with other users interested in those items. Exchanges promote the circulation of goods within the community, fostering a collaborative and sustainable consumption model.


+ **Guarantees (Garantías):** Assurances provided by the platform to users regarding the quality, authenticity, or condition of exchanged objects. Guarantees serve to instill confidence in users, assuring them that the objects they receive through exchanges meet certain standards and expectations. These guarantees may include policies for verifying the authenticity of items, conducting quality inspections, or providing recourse in the event of disputes or issues with exchanged objects.


+ **Advertisements (Anuncios)** Promotional content displayed on the platform to generate interest or revenue. Advertisements may take various forms, including banner ads, sponsored content, or targeted promotions, and they are often tailored to the interests, preferences, or demographics of users. Advertisements may be used to promote relevant products, services, or events to users, and they may serve as a source of revenue for the platform through advertising partnerships or pay-per-click arrangements.


+ **Donation (Donaciones):** Contributions made by users in the form of objects or monetary support to individuals or organizations. Donations reflect acts of generosity and altruism within the community, allowing users to support causes they care about or assist those in need. Users may donate objects they no longer need or use, providing them to individuals or organizations that can benefit from them. Additionally, users may make monetary donations to support charitable initiatives, nonprofit organizations, or community projects facilitated by the platform.


+ **Physical Donation (Donación física):** Donating physical objects by providing an address for drop-off. Physical donations involve the transfer of tangible items from one user to another, typically through arrangements for pickup or delivery. Users may offer physical donations to other users directly, arranging for the exchange of objects through personal interactions or logistics coordinated within the platform. Physical donations contribute to resource sharing and waste reduction efforts, enabling users to repurpose or recycle items they no longer need.


+ **Monetary Donation (Donación monetaria):** Contributing money to a specified account, typically belonging to a non-profit organization. Monetary donations involve the transfer of funds from one user to another, often in support of charitable causes, humanitarian efforts, or community initiatives. Users may donate money to nonprofit organizations, charitable foundations, or crowdfunding campaigns endorsed by the platform, providing financial support to causes aligned with their values or interests. Monetary donations may be used to fund various projects, programs, or activities that benefit the community or address societal needs.


+ **Transaction (Transacción):** A financial exchange or operation carried out between users or involving the platform. Transactions encompass a wide range of interactions within the platform, including purchases, sales, exchanges, donations, or payments. Users engage in transactions to acquire, exchange, or transfer goods, services, or funds, utilizing the platform's features and functionalities to facilitate these exchanges securely and efficiently. Transactions may involve the transfer of virtual assets, such as digital currency or credits, as well as the exchange of physical goods or monetary payments.


+ **Categories (Categorías):** Groupings or classifications used to organize objects, organizations, or content for easier navigation and searchability. Categories serve as a taxonomy or hierarchical structure within the platform, grouping related items or entities based on shared characteristics, attributes, or properties. Users can browse or filter content within specific categories to narrow down their search results and find relevant information more efficiently. Categories may be predefined by the platform or created dynamically based on user-generated content, reflecting the diverse interests and preferences of the community.


+ **User Limit (Límite de usuario):** The maximum number of objects a user can publish or display on the platform within a given timeframe. User limits impose restrictions on the quantity or volume of content that individual users can contribute or showcase within the platform, preventing abuse, spam, or excessive clutter. These limits may be enforced to maintain a balanced and equitable distribution of resources among users, ensuring fair access to platform features and functionalities. Users may encounter user limits based on their subscription level, account status, or platform policies, with options to increase limits through upgrades or premium memberships.


+ **Space Allocation (Asignación de espacio):** The allocation of virtual real estate or capacity on the platform for users to publish or display their objects. Space allocation involves the provision of digital resources, such as storage capacity, bandwidth, or display area, to accommodate user-generated content within the platform. Users are allotted a certain amount of space or resources based on their subscription plan, account settings, or platform privileges, dictating the extent to which they can contribute or showcase objects, advertisements, or other content. Space allocation may be managed dynamically to accommodate fluctuations in user activity or demand, optimizing resource utilization and user experience within the platform.


+ **User (Usuario):** An individual who interacts with the platform, either by subscribing, publishing objects, or engaging in exchanges. Users represent the primary stakeholders and participants within the platform ecosystem, contributing content, generating activity, and shaping the community dynamics. Users may vary in their roles, behaviors, and preferences, ranging from content creators and contributors to consumers and participants. The platform's features, functionalities, and policies are designed to cater to the needs, interests, and expectations of users, fostering a positive and engaging user experience.<br><br>


---
# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping
En esta sección, abordaremos el To-Be Scenario Mapping para ambos segmentos, donde describiremos cómo deben configurarse las experiencias durante cada fase.


<b>Segmento Intercambiadores</b><br>

<div align="center">

[![To-Be Scenario Mapping.](https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/To-Be/to-be-scenario-1.PNG?raw=true)](https://miro.com/welcomeonboard/cndoaHZpeWJQalZSYTZ2UGVFbnFOdTVUWVZxQ2k2RGF2dkRsS2IzUkdxYlZ4bDFwWHVudVRmYXN2Sng4TzFVWHwzNDU4NzY0NTU2Nzc0MzI2MzAxfDI=?share_link_id=867992439188)
</div>

Enlace: [To-Be Scenario Mapping en Miro](https://miro.com/welcomeonboard/cndoaHZpeWJQalZSYTZ2UGVFbnFOdTVUWVZxQ2k2RGF2dkRsS2IzUkdxYlZ4bDFwWHVudVRmYXN2Sng4TzFVWHwzNDU4NzY0NTU2Nzc0MzI2MzAxfDI=?share_link_id=867992439188)
<br>

<b>Segmento Donadores</b><br>

<div align="center">

[![To-Be Scenario Mapping.](https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/To-Be/to-be-scenario-2.PNG?raw=true)](https://miro.com/welcomeonboard/cndoaHZpeWJQalZSYTZ2UGVFbnFOdTVUWVZxQ2k2RGF2dkRsS2IzUkdxYlZ4bDFwWHVudVRmYXN2Sng4TzFVWHwzNDU4NzY0NTU2Nzc0MzI2MzAxfDI=?share_link_id=867992439188)
</div>

Enlace: [To-Be Scenario Mapping en Miro](https://miro.com/welcomeonboard/cndoaHZpeWJQalZSYTZ2UGVFbnFOdTVUWVZxQ2k2RGF2dkRsS2IzUkdxYlZ4bDFwWHVudVRmYXN2Sng4TzFVWHwzNDU4NzY0NTU2Nzc0MzI2MzAxfDI=?share_link_id=867992439188)





## 3.2. User Stories
En esta sección, profundizaremos en la definición y elaboración de las User Stories relacionadas con nuestro proyecto. Las User Stories son una herramienta fundamental en el desarrollo de software y proyectos de diseño centrados en el usuario.


**EPICS**

|**Epic ID**|**Título**|**Descripción**|**Criterio de aceptación**|**Relación (EPIC ID)**|
| - | - | - | - | - |
|**EP01**|**Gestión de Cuenta de Usuario**|Como usuario, quiero tener el control total sobre mi cuenta para gestionarla según mis necesidades.|<p>**Escenario 1: Registro de Usuario**</p><p></p><p>Dado que  un nuevo usuario accede a la aplicación por primera vez,</p><p>Cuando completa el formulario de registro con su dirección de correo electrónico y contraseña,</p><p>Entonces se crea una nueva cuenta para el usuario</p><p>Y se le redirige a la página principal de la aplicación.<br><br>**Escenario 2: Edición de Perfil:**</p><p></p><p>Dado que un usuario desea actualizar la información de su perfil,</p><p>Cuando accede a la configuración de perfil y realiza cambios en los detalles personales,</p><p>Entonces los cambios se guardan correctamente <br>Y se reflejan en su perfil.</p><p></p><p>**Escenario 3: Eliminación de Cuenta**</p><p></p><p>Dado que un usuario desea eliminar permanentemente su cuenta,</p><p>Cuando solicita la eliminación de la cuenta desde la configuración de la cuenta <br>Y confirma la acción,</p><p>Entonces el sistema borra todos los datos asociados a la cuenta<br>Y se proporciona una confirmación de la eliminación exitosa.</p>||
|**EP02**|**Funcionalidades de Intercambio**|Como usuario de la aplicación, quiero acceder a una variedad de funcionalidades relacionadas con el intercambio de objetos, para facilitar la búsqueda, creación y gestión de publicaciones de intercambio.|<p>**Escenario 1: Búsqueda de Objetos para Intercambiar**</p><p></p><p>Dado que el usuario quiere encontrar objetos para intercambiar,</p><p>Cuando utiliza la función de búsqueda en la aplicación,</p><p>Entonces el sistema muestra resultados relevantes de objetos disponibles para intercambiar.</p><p></p><p>**Escenario 2: Creación de Publicaciones de Intercambio**</p><p></p><p>Dado que el usuario tiene un objeto para intercambiar,</p><p>Cuando el usuario crea una nueva publicación de intercambio en la aplicación,</p><p>Entonces debe proporcionar los detalles sobre el objeto, como título, descripción, categoría, condición y fotos.</p><p></p><p>**Escenario 3: Gestión de Publicaciones de Intercambio**</p><p></p><p>Dado que el usuario ha creado publicaciones de intercambio,</p><p>Cuando accede a su perfil o al panel de control,</p><p>Entonces debe poder ver todas sus publicaciones de intercambio y realizar acciones como editar, eliminar o destacarlas.</p><p></p><p>**Escenario 4: Interacción con Otras Publicaciones**</p><p></p><p>Dado que el usuario quiere intercambiar con un propietario de un objeto,</p><p>Cuando utiliza la función de contacto en la publicación de intercambio,</p><p>Entonces debe poder comunicarse directamente con el propietario para discutir los detalles del intercambio.</p>||
|**EP03**|**Funcionalidades de Donación**|Como usuario de la aplicación, quiero acceder a funcionalidades específicas relacionadas con la donación de objetos, para facilitar la búsqueda, selección y contacto con organizaciones no gubernamentales (ONGs) para donar objetos.|<p>**Escenario 1:Selección de ONGs para Donar**</p><p></p><p>Dado que el usuario quiere donar objetos a organizaciones no gubernamentales (ONGs),</p><p>Cuando accede a la sección de ONGs disponibles para donación,</p><p>ENTONCES se deben mostrar opciones de ONGs junto con información relevante como su misión, proyectos y formas de colaboración.</p><p></p><p>**Escenario 2: Contacto con ONGs para Donación**</p><p></p><p>Dado que el usuario desea donar objetos a una ONG específica,</p><p>Cuando utiliza la función de contacto proporcionada en la aplicación,</p><p>Entonces debe poder comunicarse directamente con la ONG para coordinar la donación.</p><p></p><p>**Escenario 3: Visualización de Información Relevante**</p><p></p><p>Dado que el usuario está interesado en donar objetos,</p><p>Cuando selecciona una ONG para ver más detalles,</p><p>Entonces debe poder acceder a información detallada sobre la ONG, incluyendo su misión, proyectos actuales y formas de colaboración.</p><p></p>||
|**EP04**|**Gestión de Suscripciones**|Como usuario de la aplicación, quiero acceder a funcionalidades relacionadas con la gestión de suscripciones premium, para poder adquirir una suscripción premium, cancelarla en cualquier momento y disfrutar de los beneficios adicionales que ofrece.|<p>**Escenario 1: Adquisición de Suscripción Premium**</p><p></p><p>Dado el usuario desea acceder a funcionalidades premium,</p><p>Cuando utiliza la función de adquisición de suscripción en la aplicación,</p><p>Entonces el sistema muestra la opción de elegir entre diferentes planes de suscripción premium <br>Y realizar el pago correspondiente.</p><p></p><p>**Escenario 2: Cancelación de Suscripción Premium**</p><p></p><p>Dado el usuario ya no desea mantener su suscripción premium,</p><p>Cuando utiliza la función de cancelación de suscripción en la aplicación,</p><p>Entonces se debe permitir la cancelación de la suscripción en cualquier momento, con una confirmación adicional para evitar cancelaciones accidentales.</p><p></p><p>**Escenario 3: Disfrute de Beneficios Adicionales:**</p><p></p><p>Dado el usuario ha adquirido una suscripción premium,</p><p>Cuando utiliza la aplicación,</p><p>Entonces debe poder acceder y disfrutar de los beneficios adicionales ofrecidos por la suscripción premium, como funciones exclusivas, contenido especial, o descuentos.</p><p><br></p>||
|**EP05**|**Soporte y Ayuda**|Como usuario de la aplicación, quiero acceder a funcionalidades relacionadas con el soporte y la ayuda, para resolver cualquier problema técnico que pueda surgir durante mi experiencia de uso.|<p>**Escenario 1: Acceso al Centro de Soporte:**</p><p></p><p>Dado que el usuario encuentra un problema técnico mientras utiliza la aplicación,</p><p>Cuando busca ayuda para resolver el problema,</p><p>Entonces debe poder acceder al centro de soporte en la aplicación para reportar el problema <br>Y recibir asistencia técnica.</p><p></p><p>**Escenario 2: Acceso a Preguntas Frecuentes y Comentarios**</p><p></p><p>Dado que el usuario tiene una pregunta común o desea conocer la opinión de otros usuarios sobre la aplicación,</p><p>Cuando busca información adicional o comentarios,</p><p>Entonces debe poder acceder a una sección de preguntas frecuentes y comentarios dentro de la aplicación para encontrar respuestas y opiniones relevantes.</p><p></p>||
|**EP06**|**Información y Navegación de la Landing Page**|Como usuario visitante de la página web de la aplicación, deseo acceder a información relevante y navegar fácilmente por la landing page para obtener una comprensión clara de las características y funcionalidades ofrecidas por la aplicación.|<p>**Escenario 1: Visualización de Información Relevante**</p><p></p><p>Dado que el usuario visitante quiere conocer más sobre la aplicación,</p><p>Cuando navega por la landing page,</p><p>Entonces debe poder acceder a información relevante sobre las características, funcionalidades</p><p>Y beneficios ofrecidos por la aplicación.</p><p>**Escenario 2: Navegación Intuitiva:**</p><p></p><p>Dado que el usuario visitante desea navegar fácilmente por la landing page,</p><p>Cuando explora la página,</p><p>Entonces debe encontrar un diseño intuitivo <br>Y un menú de navegación claro que le permita desplazarse sin problemas por las diferentes secciones de la página.</p><p></p><p>**Escenario 3: Visualización de Planes y Precios:**</p><p></p><p>Dado que un usuario visitante está interesado en conocer los planes <br>Y precios de la aplicación,</p><p>Cuando busca información sobre los planes de suscripción,</p><p>Entonces debe poder ver claramente los diferentes planes disponibles junto con sus precios <br>Y beneficios asociados.</p><p></p>||
|**EP07**|**Desarrollo de Funcionalidades de la API de CambiaZo**|Como equipo de desarrollo, queremos implementar una serie de funcionalidades en la API de la aplicación para gestionar usuarios, reseñas, ONGs y suscripciones, con el fin de mejorar la experiencia del usuario y garantizar un funcionamiento eficiente de la plataforma.|<p>**Criterios de Aceptación:**</p><p></p><p>**Escenario 1: Diseño y Configuración de la API**</p><p></p><p>Dado que el equipo de desarrollo está configurando la plataforma,</p><p>Cuando diseñan y configuran la API para gestionar usuarios, reseñas, ONGs y suscripciones,</p><p>Entonces se definen los endpoints, rutas y requisitos de autenticación necesarios para cada funcionalidad.</p><p></p><p>**Escenario 2: Selección de Tecnología**</p><p></p><p>Dado que el equipo de desarrollo está seleccionando la tecnología para implementar la API,</p><p>Cuando consideran los requisitos de la aplicación y las preferencias del equipo,</p><p>Entonces eligen la tecnología adecuada que garantice la escalabilidad, rendimiento y facilidad de mantenimiento.</p><p>**Escenario 3: Implementación de Funcionalidades**</p><p></p><p>Dado que el equipo de desarrollo está implementando las funcionalidades de la API,</p><p>Cuando desarrollan las operaciones POST, GET y otras necesarias para cada tipo de recurso (usuarios, reseñas, ONGs, suscripciones),</p><p>Entonces aseguran que las operaciones funcionen correctamente según los criterios definidos en los technical stories correspondientes.</p><p></p><p>**Escenario 4: Creación de Documentación de la API**</p><p></p><p>Dado que el equipo de desarrollo ha finalizado la implementación de la API,</p><p>Cuando generan la documentación de la API,</p><p>Entonces incluyen información detallada sobre los endpoints disponibles, los parámetros de entrada y salida, los métodos admitidos y los códigos de estado HTTP.</p><p></p>||


<br><br>

**USER STORIES**

|**Epic/User Story ID**|**Título**|**Descripción**|**Criterio de aceptación**|**Relación (EPIC ID)**|
| - | - | - | - | - |
|**US-01**|Registro de usuario|<p>Como nuevo usuario quiero completar el proceso de registro en la aplicación para establecer mi propia cuenta.</p><p></p>|<p>**Escenario 1:** Acceso del usuario a la página de registro</p><p>Dado que el  usuario ha descargado la aplicación y la inicia,</p><p>Cuando se encuentra en la sección de "Inicio de sesión"</p><p>Y opta por hacer clic en el botón de "Registrarse",</p><p>Entonces, la aplicación desplegará la página de registro.</p><p></p><p>**Escenario 2:** Registro exitoso del usuario</p><p>Dado que el usuario esté en la página de registro,</p><p>Cuando introduce su información requerida</p><p>Y procede a hacer clic en el botón de "Registrarse”,</p><p>Entonces la aplicación llevará a cabo el registro del usuario y guardará su cuenta.</p><p></p><p>**Escenario 3**: Registro del usuario con datos inválidos</p><p>Considerando que el usuario está en la página de registro,</p><p>Cuando proporciona información incompleta o no válida</p><p>Y luego activa el botón de "Registrarse",</p><p>Entonces la aplicación mostrará un mensaje de error</p><p>Y eliminará los datos introducidos.</p><p></p>|**EP01**|
|**US-02**|<p>Editar perfil del usuario</p><p></p>|Como usuario ya registrado realizar modificaciones en mi perfil para asegurarme de que mi información esté siempre actualizada.|<p>**Escenario 1:** Acceso del usuario a "Mi perfil"</p><p>Dado que el usuario está registrado en la aplicación,</p><p>Cuando acceda a su perfil,</p><p>Entonces el sistema presentará la página "Mi perfil".</p><p></p><p>**Escenario 2:** El usuario elige editar su perfil</p><p>Dado que el usuario se encuentra en la página "Mi perfil" con los datos personales visibles,</p><p>Cuando seleccione el botón "Editar perfil",</p><p>Entonces, el sistema mostrará la página de edición de perfil.</p><p></p><p>**Escenario 3:** Actualización exitosa de los datos del perfil del usuario</p><p>Dado que el usuario se encuentra en la página de edición de perfil con los datos personales visibles,</p><p>Cuando introduzca sus nuevos datos</p><p>Y seleccione el botón "Guardar cambios",</p><p>Entonces el sistema actualizará la información del perfil del usuario con los nuevos datos ingresados.</p><p></p><p>**Escenario 4:** Actualización de los datos del perfil del usuario con información inválida o incompleta</p><p>Dado que el usuario se encuentra en la página de edición de perfil con los datos personales visibles,</p><p>Cuando ingrese datos incompletos o inválidos</p><p>Y seleccione el botón "Actualizar",</p><p>Entonces la aplicación mostrará un mensaje de "Error"</p><p>Y borrará los datos ingresados.</p><p></p>|**EP01**|
|**US-03**|Iniciar sesión en la aplicación|Como usuario registrado quiero iniciar sesión en la aplicación para poder acceder a todas sus funcionalidades.|<p>**Escenario 1:** Acceso del usuario a la página de inicio de sesión</p><p>Dado que el usuario abre la aplicación</p><p>Y no ha iniciado sesión previamente o se ha desconectado</p><p>Cuando el usuario seleccione el botón "Iniciar Sesión"</p><p>Entonces, la aplicación mostrará la página de inicio de sesión.</p><p></p><p>**Escenario 2:** Inicio de sesión exitoso del usuario</p><p>Dado que el usuario se encuentra en la página de inicio de sesión</p><p>Cuando ingrese sus credenciales válidas</p><p>Y haga clic en el botón "Iniciar Sesión"</p><p>Entonces, el usuario será autenticado</p><p>Y dirigido a la página principal de la aplicación.</p><p></p><p>**Escenario 3:** Intento de inicio de sesión fallido</p><p>Dado que el usuario está en la página de inicio de sesión</p><p>Cuando ingrese credenciales inválidas</p><p>Y haga clic en el botón "Iniciar Sesión"</p><p>Entonces, la aplicación mostrará un mensaje de error indicando que las credenciales son incorrectas.</p><p></p>|**EP01**|
|**US-04**|Cambiar Contraseña|<p>Como usuario registrado, quiero realizar cambios en la contraseña de mi cuenta para reforzar la seguridad de mi cuenta.</p><p></p>|<p>**Escenario 1:** Acceso del usuario a la configuración de la cuenta</p><p>Dado que el usuario ha iniciado sesión en la aplicación</p><p>Cuando acceda a la sección de configuración de la cuenta</p><p>Entonces la aplicación mostrará la opción para modificar la contraseña.</p><p></p><p>**Escenario 2:** Cambio exitoso de la contraseña</p><p>Dado que el usuario está en la página de cambio de contraseña</p><p>Cuando ingrese su contraseña actual y la nueva contraseña dos veces</p><p>Y haga clic en el botón "Cambiar Contraseña"</p><p>Entonces la aplicación ejecutará el cambio de contraseña</p><p>Y mostrará un mensaje de confirmación.</p><p></p><p>**Escenario 3:** Intento de cambio de contraseña fallido</p><p>Dado que el usuario se encuentre en la página de cambio de contraseña</p><p>Cuando ingrese una contraseña actual incorrecta o incompleta, seguida de la nueva contraseña dos veces</p><p>Y seleccione el botón "Cambiar Contraseña"</p><p>Entonces la aplicación mostrará un mensaje de error indicando que la contraseña actual es incorrecta.</p><p></p>|**EP01**|
|**US-05**|<p>Cerrar Sesión</p><p></p>|<p>Como usuario registrado quiero cerrar sesión en la aplicación para asegurarme de que mi cuenta no quede almacenada en mi dispositivo móvil.</p><p></p>|<p>**Escenario 1:** Acceso del usuario a la configuración de la cuenta</p><p>Dado que el usuario ha iniciado sesión en la aplicación</p><p>Cuando acceda a la sección de configuración de la cuenta</p><p>Entonces la aplicación mostrará la opción para cerrar sesión.</p><p></p><p>**Escenario 2:** Cierre de sesión exitoso por parte del usuario</p><p>Dado que el usuario se encuentra en la página de cierre de sesión</p><p>Cuando seleccione el botón "Cerrar Sesión"</p><p>Entonces, la aplicación concluirá la sesión del usuario y lo redirigirá a la página de inicio de sesión.</p><p></p>|**EP01**|
|**US-06**|Filtrado de Objetos|Como usuario Intercambiador, quiero la capacidad de filtrar los objetos disponibles de intercambio para encontrar la opción que mejor se adapte a mis preferencias de intercambio.|<p>**Escenario 1:** Aplicación de Filtros</p><p></p><p>Dado que el usuario intercambiador está en la sección de objetos disponibles para intercambio</p><p></p><p>Cuando el usuario selecciona filtros específicos, como categoría, estado del objeto y ubicación<br><br>Y presiona el botón de "Aplicar Filtros"</p><p></p><p>Entonces la lista de objetos se ajustará automáticamente según los criterios seleccionados.</p><p></p><p>**Escenario 2:**  Visualización de Resultados Filtrados</p><p><br>Dado que el usuario ha aplicado filtros por estado a la lista de objetos disponibles</p><p></p><p>Cuando la aplicación muestra únicamente los objetos que cumplen con el estado seleccionado</p><p></p><p>Entonces el usuario puede ver y explorar los resultados filtrados según sus preferencias.</p><p></p><p>**Escenario 3:** Filtrar por cantidad de Vistas<br><br>Dado que el usuario está buscando objetos con la mayot cantidad de vistas para intercambiar</p><p></p><p>Cuando el usuario selecciona la opción de "Filtrar por Vistas"</p><p></p><p>Y presiona el botón de "Aplicar Filtros"</p><p></p><p>Entonces la aplicación presenta los objetos más populares en la parte superior de la lista de resultados.</p>|**EP02**|
|**US-07**|Filtrado de ONGs|Como usuario Donante, quiero la capacidad de filtrar las ONGs disponibles de donación para encontrar la opción que mejor se adapte a los objetos que tengo para donar|<p>**Escenario 1:** Aplicación de Filtros</p><p></p><p>Dado que el usuario donante está en la sección de ONGs disponibles para donación</p><p></p><p>Cuando el usuario selecciona filtros específicos, como categoría de objetos, estado del objeto y ubicación geográfica</p><p></p><p>Y presiona el botón de "Aplicar Filtros"</p><p></p><p>Entonces la lista de ONGs se ajustará automáticamente según los criterios seleccionados.</p><p></p><p>**Escenario 2:** Visualización de Resultados Filtrados</p><p></p><p>Dado que el usuario donante ha aplicado filtros por categoría y ubicación a la lista de ONGs disponibles</p><p></p><p>Cuando la aplicación muestra únicamente las ONGs que aceptan objetos de la categoría y se encuentran en la ubicación seleccionada</p><p></p><p>Entonces el usuario puede ver y explorar los resultados filtrados según sus preferencias.</p><p><br><br><br><br><br></p><p>**Escenario 3:** Filtrar por Áreas de Actuación</p><p></p><p>Dado que el usuario donante está interesado en encontrar ONGs que trabajen en áreas específicas de acción</p><p></p><p>Cuando el usuario selecciona la opción de "Filtrar por Áreas de Actuación"</p><p></p><p>Y elige una o varias áreas de interés, como educación, salud o medio ambiente</p><p></p><p>Entonces la aplicación presenta las ONGs que se especializan en esas áreas prioritarias de actuación.</p>|**EP03**|
|**US-08**|Brindar reseña sobre el Intercambiador|Como usuario intercambiador, deseo dejar una reseña sobre mi experiencia con el intercambiador para que otros usuarios puedan leer y considerar mi opinión antes de intercambiar|<p>**Escenario 1:** Dejar una Reseña</p><p></p><p>Dado que el usuario intercambiador ha completado un intercambio con otro usuario,</p><p></p><p>Cuando visita la página de la experiencia de intercambio realizada,</p><p></p><p>Entonces el usuario encuentra una opción para dejar una reseña sobre su experiencia con el intercambiador.</p><p></p><p>**Escenario 2:** Visualización de Reseñas</p><p></p><p>Dado que otros usuarios visitan la página de la experiencia de intercambio,</p><p></p><p>Cuando exploran las reseñas dejadas por otros intercambiadores,</p><p></p><p>Entonces pueden leer y considerar las opiniones de otros usuarios antes de realizar un intercambio con ese intercambiador.</p><p></p><p>**Escenario 3:** Respuesta a Reseñas</p><p></p><p>Dado que el usuario intercambiador ha dejado una reseña sobre su experiencia con otro intercambiador,</p><p></p><p>Cuando el intercambiador revisado desea responder a la reseña,</p><p></p><p>Entonces tiene la opción de dejar una respuesta o comentario en la reseña para interactuar con el usuario que dejó la reseña.</p>|**EP02**|
|**US-09**|Eliminación de cuenta|Como usuario, quiero tener la opción de eliminar permanentemente mi cuenta para evitar que mi información persista en caso de que ya no desee utilizar la aplicación|<p>**Escenario 1:** Acceso a la Opción de Eliminación</p><p></p><p>Dado que el usuario está registrado en la aplicación</p><p></p><p>Cuando desea eliminar permanentemente su cuenta</p><p></p><p>Entonces la aplicación proporciona una opción claramente visible en la configuración de la cuenta para eliminar la cuenta.</p><p></p><p>**Escenario 2:** Confirmación de Eliminación</p><p></p><p>Dado que el usuario selecciona la opción de eliminar su cuenta</p><p></p><p>Cuando confirma su elección</p><p></p><p>Entonces la aplicación muestra un mensaje de confirmación solicitando al usuario que confirme su decisión antes de proceder con la eliminación.</p><p></p><p>**Escenario 3:** Eliminación Exitosa de la Cuenta</p><p></p><p>Dado que el usuario ha confirmado su deseo de eliminar su cuenta</p><p></p><p>Cuando la confirmación es recibida por la aplicación</p><p></p><p>Entonces todos los datos asociados con la cuenta del usuario son eliminados permanentemente de la base de datos y la cuenta se cierra de forma definitiva.</p>|**EP01**|
|**US-10**|Actualización de Correo Electrónico|Como usuario, quiero actualizar mi dirección de correo electrónico en mi perfil para asegurarme de que recibo notificaciones e información relevante|<p>**Escenario 1:** Acceso a la Configuración de Perfil</p><p></p><p>Dado que el usuario está autenticado en la aplicación,</p><p></p><p>Cuando desea actualizar su dirección de correo electrónico,</p><p></p><p>Entonces accede a la sección de configuración de perfil.</p><p></p><p>**Escenario 2:** Edición de la Dirección de Correo Electrónico</p><p></p><p>Dado que el usuario está en la sección de configuración de perfil,</p><p></p><p>Cuando selecciona la opción para editar su dirección de correo electrónico,</p><p></p><p>Entonces la aplicación le permite ingresar la nueva dirección de correo electrónico.</p><p></p><p>**Escenario 3:** Verificación del Nuevo Correo Electrónico</p><p></p><p>Dado que el usuario ha ingresado la nueva dirección de correo electrónico,</p><p></p><p>Cuando confirma la actualización de su dirección de correo electrónico,</p><p></p><p>Entonces la aplicación envía un correo electrónico de verificación a la nueva dirección proporcionada.</p><p></p><p>**Escenario 4:** Confirmación de Verificación</p><p></p><p>Dado que el usuario ha recibido el correo electrónico de verificación,</p><p></p><p>Cuando hace clic en el enlace de verificación dentro del correo electrónico,</p><p></p><p>Entonces la aplicación verifica la nueva dirección de correo electrónico</p><p>Y confirma la actualización en el perfil del usuario.</p>|**EP01**|
|**US-11**|Configuración de notificaciones|Como usuario , quiero tener control sobre las notificaciones que recibo para personalizar mi experiencia en la web.|<p>**Escenario 1:** Configuración de Notificaciones</p><p></p><p>Dado que el usuario ha iniciado sesión en la aplicación,</p><p></p><p>Cuando desea personalizar sus notificaciones desde su perfil,</p><p></p><p>Entonces la aplicación le ofrece una página de configuración de notificaciones donde puede elegir las categorías de notificaciones que desea recibir.</p><p></p><p>**Escenario 2:** Personalización de Notificaciones</p><p></p><p>Dado que el usuario se encuentra en la sección de configuración de notificaciones,</p><p></p><p>Cuando selecciona las categorías específicas de notificaciones que le interesan,</p><p></p><p>Entonces la aplicación ajusta sus notificaciones según las preferencias del usuario, enviando únicamente las alertas seleccionadas.</p><p></p><p>**Escenario 3:** Desactivación de Notificaciones</p><p></p><p>Dado que el usuario desea dejar de recibir ciertas notificaciones,</p><p></p><p>Cuando accede a la configuración de notificaciones,desmarcar las categorías de notificaciones no deseadas,</p><p></p><p>Entonces la aplicación adapta sus alertas según las preferencias del usuario.</p>|**EP01**|
|**US-12**|Crear publicación de intercambio|Como usuario de la aplicación, quiero poder crear una nueva publicación de intercambio para ofrecer un artículo que deseo intercambiar|<p>**Escenario 1: Creación de una nueva publicación de intercambio**</p><p>Dado que el usuario accede a la opción de crear una nueva publicación de intercambio desde la interfaz de la aplicación,</p><p>Cuando completa el formulario con los detalles del artículo que desea intercambiar, incluyendo título, descripción, categoría, condición del artículo e información relevante,</p><p>Entonces se le permite adjuntar imágenes del artículo.</p><p></p><p>**Escenario 2: Publicación de intercambio creada**</p><p>Dado que el usuario está completando el formulario de creación de la publicación de intercambio,</p><p>Cuando intenta enviar la publicación,</p><p>Entonces el sistema valida los campos del formulario</p><p>Y crea la publicación de intercambio.</p><p></p><p>**Escenario 3: Visualización de publicación de intercambio**</p><p>Dado que la publicación de intercambio ha sido creada,</p><p>Cuando el usuario acceda a su perfil</p><p>Y vaya a la sección de mis publicaciones</p><p>Entonces el sistema le mostrará la publicación del artículo que desea intercambiar.</p>|**EP02**|
|**US-13**|Editar publicación de intercambio|Como usuario, necesito la capacidad de editar una publicación de intercambio existente para realizar cambios en los detalles del artículo o actualizar la información relevante.|<p>**Escenario 1: Acceso a la edición de una publicación de intercambio**</p><p>Dado que el usuario ha iniciado sesión en la aplicación</p><p>Y tiene una publicación de intercambio existente,</p><p>Cuando el usuario hace click a la opción de editar la publicación desde la interfaz de la aplicación,</p><p>Entonces el sistema redirige a un formulario prellenado con los detalles actuales de la publicación para realizar cambios<br>Y dos botones “Cancelar” y “Publicar”</p><p></p><p>**Escenario 2: Edición de la publicación de intercambio confirmada**</p><p></p><p>Dado que el usuario está en el formulario de edición de la publicación de intercambio,</p><p>Cuando el usuario realiza cambios en los detalles del artículo que desea intercambiar, como título, descripción, categoría, condición del artículo u otra información relevante,</p><p>Y le da al botón de “Publicar</p><p>Entonces el sistema guardará los cambios realizados en la publicación.</p><p>Y la hará visible para todos los usuarios.</p><p></p><p>**Escenario 3: Edición de la publicación de intercambio cancelada**</p><p></p><p>Dado que el usuario está en el formulario de edición de la publicación de intercambio,</p><p>Cuando el usuario realiza cambios en los detalles del artículo que desea intercambiar, como título, descripción, categoría, condición del artículo u otra información relevante,</p><p>Y le da al botón de “Cancelar”</p><p>Entonces el sistema redirige al usuario al inicio de la aplicación.</p><p><br></p>|**EP02**|
|**US-14**|Eliminar publicación de intercambio|Como usuario, quiero tener la opción de eliminar una publicación de intercambio que ya no deseo ofrecer para intercambiar.|<p>**Escenario 1: Acceso a la eliminación de una publicación de intercambio**</p><p>Dado que el usuario ha iniciado sesión en la aplicación</p><p>Y tiene una publicación de intercambio existente,</p><p>Cuando accede a la opción de eliminar la publicación desde la interfaz de la aplicación,</p><p>Entonces el sistema le muestra una confirmación para confirmar si realmente desea eliminar la publicación.</p><p></p><p>**Escenario 2: Confirmación de eliminación**</p><p>Dado que el usuario ha seleccionado eliminar una publicación de intercambio,</p><p>Cuando confirma la acción de eliminación,</p><p>Entonces el sistema elimina la publicación de manera permanente de la plataforma y se muestra un mensaje de confirmación al usuario.</p><p></p><p>**Escenario 3: Cancelación de la eliminación**</p><p>Dado que el usuario ha seleccionado eliminar una publicación de intercambio,</p><p>Cuando decide cancelar la eliminación,</p><p>Entonces la publicación no se elimina</p><p>Y el sistema redirige al usuario al inicio de la aplicación.</p><p></p>|**EP02**|
|**US-15**|Destacar publicación de intercambio|Como usuario, me gustaría poder resaltar una publicación de intercambio para aumentar su visibilidad entre otros usuarios.|<p>**Escenario 1: Acceso a la opción de destacar una publicación de intercambio**</p><p>Dado que el usuario ha iniciado sesión en la aplicación</p><p>Y tiene una publicación de intercambio existente,</p><p>Cuando accede a la opción de destacar la publicación desde la interfaz de la aplicación,</p><p>Entonces el sistema le presenta la opción de resaltar la publicación mediante una función identificada como "Destacar" o "Boost",</p><p>Y indica que esta función está disponible para usuarios premium o mediante la compra de un servicio adicional.</p><p></p><p>**Escenario 2: Confirmación de destacar la publicación con membresía premium**</p><p>Dado que el usuario ha seleccionado destacar una publicación de intercambio</p><p>Y tiene una membresía premium activa,</p><p>Cuando confirma la acción de destacar,</p><p>Entonces el sistema resalta la publicación</p><p>Y le da mayor visibilidad dentro de la plataforma.</p><p></p><p>**Escenario 3: Confirmación de destacar la publicación con compra de boost**</p><p>Dado que el usuario ha seleccionado destacar una publicación de intercambio</p><p>Y no tiene membresía premium,</p><p>Cuando decide comprar un boost para destacar la publicación,</p><p>Entonces el sistema resalta la publicación temporalmente</p><p>Y le da mayor visibilidad dentro de la plataforma durante el período de tiempo especificado por el boost adquirido.</p>|**EP02**|
|**US-16**|Ampliar slots de publicación de intercambio|Como usuario, necesito la capacidad de aumentar el número de publicaciones de intercambio que puedo tener activas simultáneamente.|<p>**Escenario 1: Acceso a la opción de ampliar slots de publicación**</p><p>Dado que el usuario ha iniciado sesión en la aplicación</p><p>Y desea aumentar el número de publicaciones de intercambio activas,</p><p>Cuando accede a la sección de configuración de la cuenta para ampliar los slots de publicación desde la interfaz de la aplicación,</p><p>Entonces el sistema le presenta la opción de aumentar el número de slots disponibles.</p><p></p><p>**Escenario 2: Confirmación de ampliar slots de publicación**</p><p>Dado que el usuario ha seleccionado la opción de ampliar los slots de publicación,</p><p>Cuando confirma la acción</p><p>Y realiza el pago correspondiente</p><p>Entonces el sistema incrementa el número de slots disponibles del usuario</p><p>Y el usuario puede tener más publicaciones de intercambio activas simultáneamente.</p><p></p><p>**Escenario 3: Visualización de slots de publicación disponibles**</p><p>Dado que el usuario ha ampliado los slots de publicación,</p><p>Cuando accede a la sección de creación de publicaciones de intercambio,</p><p>Entonces puede ver el nuevo número de slots disponibles para realizar más publicaciones simultáneas.</p><p></p><p>**Escenario 4: Cancelación de ampliar slots de publicación**</p><p>Dado que el usuario ha accedido a la opción de ampliar slots de publicación <br>Y decide no continuar con la acción,</p><p>Cuando cancela la operación,</p><p>Entonces el número de slots de publicación permanece sin cambios <br>Y se mantiene igual al estado anterior.</p>|**EP02**|
|**US-17**|Visualizar el perfil del usuario que publique un intercambio|Como usuario, me gustaría tener la capacidad de visualizar el perfil de la persona que haya publicado un intercambio, para poder obtener información detallada de su confiabilidad.|<p>**Escenario 1:** **Acceso al perfil del creador de la publicación.**</p><p>Dado que el usuario se encuentra en la publicación de su interés</p><p>Cuando le de click al recuadro que muestran el perfil del autor de la publicación</p><p>Entonces, el usuario podrá visualizar su nombre completo, tiempo que lleva en la aplicación, la cantidad de intercambios exitosos realizado</p><p>Y valoraciones de otros usuarios</p><p></p><p>**Escenario 2: Visualizar reseñas de otros usuarios hacia un perfil en específico.**</p><p>Dado que el usuario se encuentra en el perfil del autor del intercambio</p><p>Cuando Se dirija a la sección llamada “Reseñas” es cuando</p><p>Entonces el usuario podrá visualizar todas las reseñas que dicho autor ha recibido por todas sus publicaciones exitosas</p><p>Y datos relevantes sobre el creador de la publicación.</p><p></p><p>**Escenario 3: Visualizar el tipo de productos que suele intercambiar el usuario.**</p><p>Dado que el usuario está en el perfil del intercambiador</p><p>Cuando se dirija a la sección “Preferencias” es</p><p>Entonces, donde podrá visualizar la variedad de productos que suele intercambiar el usuario, así cómo también si hace match con las preferencias del usuario interesado.</p>|**EP02**|
|**US-18**|Ponerse en contacto para pactar el intercambio|Como usuario, quiero tener la posibilidad de contactar directamente con el creador de una publicación de intercambio, para poder tener una comunicación más directa.|<p>**Escenario 1: Contactar con el vendedor por un chat de WhatsApp o Telegram.**</p><p>Dado que el usuario se encuentra en la publicación de su interés</p><p>Cuando le de click al botón de WhatsApp o Telegram que aparecerá en la parte lateral de la publicación</p><p>Entonces, se le redireccionará a una pestaña de WhatsApp y/o Telegram con un mensaje predeterminado para enviar</p><p>Y ponerse en contacto de manera directa con el intercambiador.</p><p></p><p>**Escenario 2: Verificar la información del vendedor en caso de no contar con un número de contacto registrado.**</p><p>Dado que el usuario se encuentra en la publicación de su interés</p><p>Y no logré encontrar algún botón para ser redireccionado a un chat privado con el intercambiador</p><p>Entonces, podrá verificar su información personal en los detalles de la publicación</p><p>Y así poder saber su correo electrónico y/o redes sociales.</p><p></p><p>**Escenario 3: Escribir un comentario en la publicación para poder obtener información adicional pertinente.**</p><p>Dado que el usuario se encuentra en la publicación de su interés</p><p>Y no logre poder contactar por ningún medio al autor de la publicación</p><p>Entonces, podrá dirigirse a la sección de comentarios, para poder escribir directamente de la página al usuario sobre ciertos detalles o métodos de contacto.</p>|**EP02**|
|**US-19**|Ponerse en contacto para poder realizar una donación|Como usuario, quiero tener la posibilidad de contactar directamente con la organización benéfica correspondiente y/o visualizar información de contacto o número de cuenta bancaria para algún apoyo económico.|<p>**Escenario 1: Contactar con el vendedor por un chat de WhatsApp o Telegram.**</p><p>Dado que el usuario se encuentra en el perfil de la ONG correspondiente</p><p>Cuando le de click al botón de WhatsApp o Telegram que aparecerá en la parte superior del perfil</p><p>Entonces, se le redireccionará a una pestaña de WhatsApp y/o Telegram con un mensaje predeterminado para enviar</p><p>Y ponerse en contacto de manera directa con la organización benéfica.</p><p></p><p>**Escenario 2: Contactar o pedir información sobre alguna campaña en específico.**</p><p>Dado que el usuario se encuentra en el perfil de la ONG u organización benéfica correspondiente</p><p>Cuando le dé click a ver sus publicaciones</p><p>Entonces, podrá visualizar las últimas actualizaciones de campañas publicadas</p><p>Y en cada una de estas habrá un link correspondiente con información más detallada del cómo apoyar en esa campaña específica.</p><p></p><p>**Escenario 3: Solicitar información detallada.**</p><p>Dado que el usuario se encuentra en la publicación de interés</p><p>Cuando le de click a la sección de comentarios</p><p>Entonces, es que podrá redactar alguna pregunta específica que necesite hacer respecto a la campaña correspondiente.</p>|**EP03**|
|**US-20**|Adquirir la suscripción premium|Como usuario, quiero poder adquirir una suscripción premium para poder obtener beneficios adicionales que mejoren mi experiencia.|<p>**Escenario 1: Localizar la sección para adquirir una suscripción.**</p><p>Dado que el usuario desea adquirir una suscripción para CambiaZo</p><p>Cuando le de click a la sección de configuración</p><p>Entonces, le aparecerán varias opciones, entre las que figura “Ser premium”</p><p>Cuando el usuario le de click al botón,</p><p>será redirigido a una nueva ventana que le mostrará las suscripciones disponibles.</p><p></p><p>**Escenario 2: Visualizar los beneficios de la suscripción.**</p><p>Dado que el usuario se encuentra en la ventana correspondiente sobre las suscripciones,</p><p>Entonces cuando le de click a una en específico podrá ver el precio por mes de cada una de ellas</p><p>Y los beneficios que incluyen cada una de estas.</p><p></p><p>**Escenario 3: Compra de la suscripción.**</p><p>Dado que el usuario ha decidido una suscripción de su interés,</p><p>Entonces, cuando le de click a “Suscribirse”, se le redireccionará a una pasarela de pago para que pueda introducir su método de pago</p><p>Y procesar el pago respectivo y adquirir los nuevos beneficios.</p>|**EP04**|
|**US-21**|Cancelar una suscripción|<p>Como usuario quiero poder cancelar mi suscripción en cualquier momento para poder enfocarme más en las clases de la universidad</p><p></p>|<p>**Escenario 1: Acceso a la ventana de suscripciones.**</p><p>Dado que el usuario desea verificar la información del estado de su suscripción,</p><p>Cuando se dirija a la sección de configuración</p><p>Entonces, observará un botón que diga “Mi suscripción”</p><p>Y al darle click podrá ver los detalles de su suscripción.</p><p></p><p>**Escenario 2: Verificación de los detalles de la suscripción.**</p><p>Dado que el usuario se encuentra en la ventana que muestra el estado de su suscripción</p><p>Entonces, podrá visualizar la fecha en la que se renueva su suscripción, los beneficios que obtiene</p><p>Y si es que se encuentra en un plan mensual o semianual.</p><p></p><p>**Escenario 3: Proceder a la cancelación.**</p><p>Dado que el usuario se encuentra en la ventana que muestra el estado de la suscripción</p><p>Entonces, al tener ya la decisión de no continuar con el premium de CambiaZo</p><p>Y podrá darle click a un botón rojo que dice “Anular suscripción”</p><p>Y así terminaría la suscripción que no se renovará hasta su próxima fecha.</p>|**EP04**|
|**US-22**|Visualizar el perfil de las ONG’S registradas|**Como** usuario de la aplicación, **quiero** tener la opción de ver todas las ONG's disponibles **para** realizar donaciones.|<p>**Escenario 1:**Acceso a la pestaña de ONG's</p><p>**Dado que** el usuario se encuentra en la pestaña principal</p><p>**Cuando** le de click a la etiqueta "ONG's"</p><p>**Entonces** se mostrarán todas las ONG's registradas dentro de la aplicación</p><p></p><p>**Escenario 2:** Ver perfil de una ONG</p><p>**Dado que** el usuario se encuentra dentro de la pestaña "ONG'S"</p><p>**Cuando** le de click al recuadro que muestra el perfil de la ONG que desea visualizar</p><p>**Entonces** aparecerán los datos y características de la ONG seleccionada.</p><p></p><p>**Escenario 3:** Donar a una ONG</p><p>**Dado que** el usuario se encuentra en el perfil de la ONG seleccionada</p><p>**Cuando** le de click a la opción “Donar”</p><p>**Entonces** aparecerán las opciones de donación (objetos o dinero)</p><p>**Y** el usuario podrá seleccionar la opción que desea donar</p><p>**Y** realizar la donación.</p>|**EP03**|
|**US-23**|Acceder al centro de soporte para resolver cualquier problema técnico que se presente.|**Como** usuario de CambiaZo, **quiero** tener la opción de acceder a un centro de soporte **para** reportar y resolver mis problemas técnicos.|<p>**Escenario 1:** Acceso a configuración</p><p>**Dado que** soy un usuario en el aplicativo móvil</p><p>**Cuando** le de click a la sección de configuración</p><p>**Entonces** se mostrará el apartado con los botones de configuración.</p><p></p><p>**Escenario 2:** Ingresar al **“**Centro de ayuda”</p><p>**Dado que** me encuentro en la sección de configuración</p><p>**Cuando** esté en la nueva ventana, podré escoger la opción que desee: “Problemas técnicos” o “Chatear con soporte”</p><p>**Entonces** podré** escoger la opción que desee</p><p></p><p>**Escenario 3:** Problemas técnicos</p><p>**Dado que** me encuentro en la sección de “Centro de Ayuda”</p><p>**Cuando** de click en “Problemas técnicos”</p><p>**Entonces** se mostrará una lista con los problemas técnicos más frecuentes con sus soluciones**.**</p><p></p><p>**Escenario 4:** Chatear con soporte</p><p>**Dado que** me encuentro en la sección de Centro de Ayuda</p><p>**Cuando** de click en “Chatear con soporte”</p><p>**Entonces** se mostrará un formulario en el cual podemos enviar nuestro problema para chatear con soporte</p>|**EP05**|
|**US-24**|Acceder dentro de la aplicación a la sección de preguntas frecuentes y comentarios|**Como** usuario de Cambiazo, **quiero** ver las preguntas frecuentes que tienen los demás usuarios y su opinión al usar la aplicación **para** poder ver si tienen mis mismas dudas y ver qué opinan de la aplicación.|<p>**Escenario 1:** Acceso a configuración</p><p>**Dado que** me encuentro en la pantalla principal de la aplicación</p><p>**Cuando** le de click a la sección de configuración</p><p>**Entonces** se mostrará el apartado con los botones de configuración.</p><p></p><p>**Escenario 2:** Preguntas frecuentes</p><p>**Dado que** me encuentro en la sección de configuración de la aplicación</p><p>**Cuando** de click en la sección de “Preguntas frecuentes”</p><p>**Entonces** se mostrará un apartado con las preguntas más frecuentes realizadas por los usuarios de la aplicación y sus respectivas respuestas.</p><p></p><p>**Escenario 2:** Comentarios de CambiaZo</p><p>**Dado que** me encuentro en la sección de configuración de la aplicación</p><p>**Cuando** de click en la sección de “Comentarios de CambiaZo”</p><p>**Entonces** se mostrará un apartado con los comentarios realizados por los usuarios de la aplicación, enseñando los comentarios más recientes.</p>|**EP05**|
|**US-25**|Visualización de la Historia de la Startup|<p>**Como** usuario visitante, **quiero** poder acceder a la historia de la startup, su misión y visión desde la landing page **para** estar más informado acerca de TechZo.</p><p></p>|<p>**Criterios de Aceptación:**</p><p>**Escenario 1: Acceso a la historia de TechZo**</p><p>**Dado que** soy un visitante de la landing page</p><p>**Cuando** navegue por la página de inicio</p><p>**Y** encuentre la sección titulada “Quiénes Somos”</p><p>**Entonces** podré obtener información detallada sobre la historia de la startup.</p><p></p><p>**Escenario 2:** **Acceso a las redes sociales de TechZo**</p><p>**Dado que** el visitante se encuentra en el landing page</p><p>**Cuando** el visitante de click en la etiqueta “Contáctanos”</p><p>**Y** encuentre los botones con los logos de las redes sociales en las que puede encontrar la página de TechZo</p><p>**Y** de click encima del botón con el logo de la red social que desee ver</p><p>**Entonces** el usuario será redireccionado a la red social que seleccionó previamente.</p><p>**Escenario 3: Acceso a información de contacto**</p><p>**Dado que** el visitante se encuentra en la parte inferior de la landing page</p><p>**Cuando** el visitante se acerque a la sección “Comunícate con nosotros”</p><p>**Entonces** el visitante podrá observar los métodos de contacto de la startup “(01) 5718202, 992113864, 933960189, cambiazo@techzo.pe”.</p>|**EP06**|
|**US-26**|Visualizar las características clave de la aplicación|**Como** usuario visitante, **quiero** poder conocer sus características clave **para** saber qué es lo que incluye.|<p>**Criterios de Aceptación:**</p><p>**Escenario 1:** Conocer las secciones principales</p><p>**Dado que** el visitante se encuentra en la landing page</p><p>**Cuando** se dirige a la sección “Puedes elegir entre…”</p><p>**Entonces** la landing page le muestra lo que puede realizar dentro de CambiaZo.</p><p></p><p>**Escenario 2:** Conocer lo que puede intercambiar</p><p>**Dado que** el visitante se encuentra en la landing page</p><p>**Cuando** se dirige a la sección “Si decides intercambiar, podrás encontrar una gran variedad de objetos”</p><p>**Entonces** la landing page muestra los diferentes tipos de artículos que puede intercambiar con CambiaZo.</p><p></p><p>**Escenario 3:** Conocer las características principales</p><p>**Dado que** el visitante se encuentra en la landing page</p><p>**Cuando** se dirige a la sección “En CambiaZo te ofrecemos…”</p><p>**Entonces** la landing page le muestra las características principales de CambiaZo.</p>|**EP06**|
|**US-27**|Acceder a un formulario para llenar mis datos de contacto y recibir noticias relacionadas con CambiaZo.|**Como** usuario visitante, **quiero** tener la opción de llenar un formulario con mi información de contacto, a través de la landing page, **para** recibir noticias y actualizaciones relevantes de CambiaZo.|<p>**Criterios de Aceptación:**</p><p>**Escenario 1: Información en el formulario**</p><p>**Dado** que soy un usuario interesado en CambiaZo que desea llenar el formulario de contacto</p><p>**Cuando** navegue por la Landing page</p><p>**Entonces** encontraré una sección que contendrá un formulario</p><p>**Y** en esa sección, debo colocar mi nombre, apellido y correo electrónico de contacto.</p><p></p><p>**Escenario 2: Envío de formulario con datos completos**</p><p>**Dado que** me encuentro en la sección del formulario de la Landing page</p><p>**Cuando**  termine de completar mi información de contacto</p><p>**Entonces** debo darle click al botón de “ENVIAR”</p><p>**Y** si he llenado todos los campos correspondientes, me saldrá un mensaje de registro exitoso.</p><p></p><p>**Escenario 3: Envío de formulario con datos incompletos**</p><p>**Dado que** me encuentro en la sección del formulario de la Landing page</p><p>**Cuando**  desee enviar el formulario con casillas en blanco</p><p>**Entonces** me saldrá un mensaje indicando que hay casillas que faltan completar.</p>|**EP06**|
|**US-28**|Acceder a la página principal de CambiaZo|<p>Como usuario visitante, quiero encontrar botones o enlaces claramente visibles que me dirijan a la página web principal de Cambiazo, para poder realizar acciones como registrarme, intercambiar o donar artículos una vez que haya obtenido la información necesaria en la landing page.</p><p></p>|<p>**Escenario 1: Identificación de botones o enlaces**</p><p>Dado que el usuario está en la landing page de Cambiazo,<br><br>Cuando busque acceder a la página principal de la plataforma,<br><br>Entonces encontrará botones o enlaces fácilmente identificables que lo dirijan a la página principal.</p><p>**Escenario 2: Redirección rápida y sin problemas**</p><p>Dado que el usuario se dirige a un botón o enlace de acceso a la página principal,<br><br>Cuando el usuario le de clic al botón,<br><br>Entonces el usuario será redirigido de manera rápida <br><br>Y sin problemas a la página principal de Cambiazo.</p><p></p>|**EP06**|
|**US-29**|Ver los planes y precios|Como usuario visitante, quiero tener acceso a una sección que detalle los planes ofrecidos por la plataforma, para poder evaluar las opciones disponibles antes de acceder a la página web principal.|<p>**Escenario 1: Acceso a la sección de planes y servicios:**</p><p>Dado que el usuario visita la landing page de Cambiazo,</p><p>Cuando busque información sobre los planes y servicios ofrecidos por la plataforma,</p><p>Entonces encontrará una sección dedicada que detalle estos aspectos.</p><p>**Escenario 2: Comparación de planes:**</p><p>Dado que el usuario revisa la información sobre los planes ofrecidos,</p><p>Cuando busque tomar una decisión informada,</p><p>Entonces encontrará que puede comparar fácilmente los diferentes planes para evaluar cuál se ajusta mejor a sus necesidades.</p>|**EP06**|
|**US-30**|Navegación en la Landing Page|**Como** usuario visitante, **quiero** contar con un menú de navegación visible y funcional **para** que me permita desplazarme fácilmente por las diferentes secciones del sitio web.|<p>**Escenario 1: Acceder a la información acerca de la startup**</p><p>Dado que el usuario se encuentra en la Landing Page</p><p>Cuando quiera acceder a la información acerca del equipo</p><p>Entonces podré darle click a la etiqueta “¿Quiénes somos?” de la barra navegadora</p><p>Y me redireccionará rápidamente a la parte de la Landing Page en la que se encuentra la información correspondiente.</p><p></p><p>**Escenario 2: Ver las ONG’s afiliadas a CambiaZo**</p><p>Dado que el usuario se encuentra en la Landing Page</p><p>Cuando quiera ver qué ONG’s están afiliadas con CambiaZo</p><p>Entonces podré darle click a la etiqueta “ONG’s” de la barra navegadora</p><p>Y me redireccionará rápidamente a la parte de la Landing Page en la que se encuentra la información correspondiente.</p><p></p><p>**Escenario 3: Buscar la sección de Contacto**</p><p>Dado que el usuario se encuentra en la Landing Page</p><p>Cuando quiera acceder a la sección para contactarme con la startup</p><p>Entonces le daré click a la etiqueta “Contáctanos” de la barra navegadora</p><p>Y me redireccionará rápidamente a la parte de la Landing Page en la que se encuentra el formulario para recibir notificaciones de CambiaZo y el pié de página en el cuál se encuentran los datos de contacto.</p><p></p><p>**Escenario 4: Llegar al inicio de la Landing Page rápidamente**</p><p>Dado que el usuario se encuentra en la Landing Page</p><p>Cuando quiera acceder rápidamente al inicio de esta</p><p>Entonces podré darle click a la etiqueta “Inicio” de la barra navegadora</p><p>Y me redireccionará inmediatamente a la parte superior de la Landing Page.</p>|**EP06**|


<br><br>

**Technical User Stories**

|**Technical story ID**|**Título**|**Descripción**|**Criterios de Aceptación**|**Epica**|
| - | - | - | - | - |
|TS01|Create API User|<p>**Como** usuario desarrollador que configura la plataforma</p><p>**Quiero** diseñar una API que facilite la gestión de usuarios en nuestra aplicación</p><p>**Para** administrar eficazmente la información de los usuarios.</p><p></p>|<p>**Escenario 1: Diseño de la API User**</p><p>Dado que el usuario developer configura la plataforma</p><p>Cuando diseñe la API para gestionar usuarios en nuestra aplicación web,</p><p>Entonces definirá los endpoints y rutas necesarias para manejar operaciones como registro de usuarios, inicio de sesión, actualización de datos de usuario, y recuperación de contraseñas y establecerá los requisitos de autenticación y seguridad necesarios para proteger la información de los usuarios.</p><p>**Escenario 2: Selección de la tecnología para la API**</p><p>Dado que el usuario developer está diseñando la API para gestionar usuarios en nuestra aplicación web,</p><p>Cuando elija la tecnología para implementar la API REST,</p><p>Entonces considerará los requisitos de la aplicación y las preferencias del equipo de desarrollo para tomar una decisión informada</p><p></p>|**EP07**|
|TS02|Post User|<p>**Como** usuario developer de la aplicación de Cambiazo</p><p>**Quiero** registrar usuario en un API</p><p>**Para** puedan navegar en mi aplicación web y usar sus funcionalidades</p>|<p>**Escenario 1: Registro de un nuevo usuario**</p><p>Dado que el endpoint "/usuarios" está disponible,</p><p>Cuando se envía una solicitud POST con los detalles del usuario,</p><p>Entonces se recibe una respuesta con estado 201,</p><p>Y se incluye un usuario con un nuevo ID y los detalles registrados.</p><p>**Escenario 2: Registro de un usuario ya existente**</p><p>Dado que el endpoint "/usuarios" está disponible,</p><p>Cuando se envía una solicitud POST con los datos del usuario,</p><p>Y ya existe un usuario registrado con esos datos,</p><p>Entonces se recibe una respuesta con estado 400,</p><p>Y se muestra un mensaje que indica "Un usuario con estos datos ya existe".</p>|**EP07**|
|TS03|Get User|<p>**Como** usuario developer de la aplicación de Cambiazo</p><p>**Quiero** obtener la información de un usuario dentro de la API usuario</p><p>**Para** usarlo en la aplicación cuando se necesite</p><p></p>|<p>**Escenario 1: Obtener información del usuario**</p><p>Dado que el endpoint "/usuarios" está disponible,</p><p>Cuando se envía una solicitud GET con el identificador del usuario,</p><p>Entonces se recibe una respuesta con estado 200,</p><p>Y se obtienen los datos del usuario solicitado.</p><p>**Escenario 2: Obtener usuario no disponible**</p><p>Dado que el endpoint "/usuarios" está disponible,</p><p>Cuando se envía una solicitud GET con un identificador de usuario que no existe,</p><p>Entonces se recibe una respuesta con estado 404,</p><p>Y se muestra un mensaje que indica "No existe un usuario con este identificador".</p>|**EP07**|
|TS04|Create API Review|<p>**Como** usuario developer que configura la plataforma</p><p>**Quiero** implementar una API que permita a los usuarios dejar reseñas a otros usuarios</p><p>**Para** mejorar la interacción entre usuarios y la plataforma.</p>|<p>**Escenario 1: Diseño de la API Review**</p><p>Dado que el usuario developer está configurando la plataforma,</p><p>Cuando diseña la API para permitir a los usuarios dejar reseñas en nuestra aplicación,</p><p>Entonces se definen los endpoints y rutas necesarias para que los usuarios puedan crear, leer, actualizar y eliminar reseñas y establecen los requisitos de autenticación y seguridad para proteger la privacidad.</p><p>**Escenario 2: Selección de la tecnología para la API**</p><p>Dado que el usuario developer está diseñando la API de reseñas en nuestra aplicación,</p><p>Cuando elige la tecnología para implementar la API REST,</p><p>Entonces se consideran los requisitos de la aplicación, incluyendo la escalabilidad, el rendimiento y la facilidad de mantenimiento.</p><p></p>|**EP07**|
|TS05|Post Review|<p>**Como** usuario developer de la aplicación de Cambiazo</p><p>**Quiero** registrar reseñas de los intercambios de un usuario en una API</p><p>**Para** mostrarlo en el perfil del usuario cuando se solicite.</p><p></p>|<p>**Escenario 1: Agregar una nueva reseña**</p><p>Dado que el endpoint "/reseñas" está disponible,</p><p>Cuando se envía una solicitud POST con los valores de la reseña,</p><p>Entonces se recibe una respuesta con estado 201,</p><p>Y se incluye una reseña con un nuevo ID y los valores registrados.</p><p>**Escenario 2: Agregar una reseña ya existente**</p><p>Dado que el endpoint "/reseñas" está disponible,</p><p>Cuando se envía una solicitud POST con los datos de la reseña,</p><p>Y ya existe una reseña registrada con esos datos,</p><p>Entonces se recibe una respuesta con estado 400,</p><p>Y se muestra un mensaje que dice "Una reseña con estos datos ya existe".</p>|**EP07**|
|TS06|Get Review|<p>**Como** usuario developer de la aplicación de Cambiazo</p><p>**Quiero** obtener informacion de las reseñas de intercambios de un usuario de la API reseñas</p><p>**Para** mostrarlas en el perfil del usuario</p><p></p>|<p>**Escenario 1: Obtener información de la reseña**</p><p>Dado que el endpoint "/reseñas" está disponible,</p><p>Cuando se envía una solicitud GET con el identificador de la reseña,</p><p>Entonces se recibe una respuesta con estado 200,</p><p>Y se obtienen los datos de la reseña solicitada.</p><p>**Escenario 2: Obtener reseña no disponible**</p><p>Dado que el endpoint "/reseñas" está disponible,</p><p>Cuando se envía una solicitud GET con un identificador de reseña que no existe,</p><p>Entonces se recibe una respuesta con estado 404,</p><p>Y se muestra un mensaje que indica "No existe una reseña con este identificador".</p>|**EP07**|
|TS07|Create API ONGs|<p>**Como** usuario developer que configura la plataforma</p><p>**Quiero** quiero diseñar una API que simplifique la obtención de información sobre las ONGs</p><p>**Para** integrarla de manera efectiva en la aplicación.</p>|<p>**Escenario 1: Diseño de la API ONGs**</p><p>Dado que el usuario developer configura la plataforma</p><p>Cuando diseñe la API para obtener información sobre las ONGs,</p><p>Entonces define los endpoints y rutas necesarias para recibir detalles sobre las ONGs y establece los requisitos de autenticación y seguridad necesarios.</p><p>**Escenario 2: Selección de la tecnología para la API**</p><p>Dado que el usuario developer está diseñando la API para obtener información sobre las ONGs,</p><p>Cuando elija la tecnología para implementar la API REST,</p><p>Entonces considerará los requisitos y preferencias de la organización para tomar una decisión informada.</p>|**EP07**|
|TS08|Post ONGs|<p>**Como** usuario developer de la aplicación de Cambiazo</p><p>**Quiero** registrar las ONGs y sus detalles en una API</p><p>**Para** mostrarlas en la aplicación cuando se le solicite.</p><p></p>|<p>**Escenario 1: Agregar una nueva reseña**</p><p>Dado que el endpoint "/reseñas" está disponible,</p><p>Cuando se envía una solicitud POST con los valores de la reseña,</p><p>Entonces se recibe una respuesta con estado 201,</p><p>Y se incluye una reseña con un nuevo ID y sus valores registrados.</p><p>**Escenario 2: Agregar una reseña ya existente**</p><p>Dado que el endpoint "/reseñas" está disponible,</p><p>Cuando se envía una solicitud POST con los datos de la reseña,</p><p>Y ya existe una reseña registrada con esos datos,</p><p>Entonces se recibe una respuesta con estado 400,</p><p>Y se muestra un mensaje que dice "Una reseña con estos datos ya existe".</p>|**EP07**|
|TS09|Get ONGs|<p>**Como** usuario developer de la aplicación de Cambiazo</p><p>**Quiero** mostrar en la aplicación las ONGs de la API ONGs</p><p>**Para** mostrarlas en la aplicación con su detalles.</p><p></p>|<p>**Escenario 1: Obtener información de la reseña**</p><p>Dado que el endpoint "/reseñas" está disponible,</p><p>Cuando se envía una solicitud GET con el identificador de la reseña,</p><p>Entonces se recibe una respuesta con estado 200,</p><p>Y se obtienen los datos de la reseña solicitada.</p><p>**Escenario 2: Obtener reseña no disponible**</p><p>Dado que el endpoint "/reseñas" está disponible,</p><p>Cuando se envía una solicitud GET con un identificador de reseña que no existe,</p><p>Entonces se recibe una respuesta con estado 404,</p><p>Y se muestra un mensaje que indica "No existe una reseña con este identificador".</p>|**EP07**|
|TS10|Create API Subscription|<p>**Como** usuario developer que configura la plataforma</p><p>**Quiero** diseñar una API que facilite la gestión de suscripciones de usuarios</p><p>**Para** ofrecer beneficios al usuario</p>|<p>**Escenario 1: Diseño de la API de Suscripciones**</p><p>Dado que el usuario developer está configurando la plataforma,</p><p>Cuando diseña la API de Suscripciones para gestionar las suscripciones de usuarios,</p><p>Entonces define los endpoints y rutas necesarios para permitir a los usuarios suscribirse, cancelar suscripciones y obtener información sobre sus suscripciones actuales y establecen los requisitos de autenticación y seguridad.</p><p>**Escenario 2: Implementación de la Operación POST para Suscripciones**</p><p>Dado que el usuario developer está desarrollando la API de Suscripciones en la aplicación,</p><p>Cuando elige la tecnología para implementar la API REST</p><p>Entonces se consideran los requisitos de la aplicación, incluyendo la escalabilidad, el rendimiento y la facilidad de mantenimiento.</p>|**EP07**|
|TS11|<p>Post Subscription</p><p></p>|<p>**Como** usuario developer de la aplicación Cambiazo,</p><p>**Quiero** implementar una API que permita a los usuarios suscribirse para obtener beneficios adicionales,</p><p>**Para** mejorar la experiencia del usuario y fomentar la participación en la plataforma.</p>|<p>**Escenario 1: Creación de una nueva suscripción**</p><p>Dado que el endpoint "/suscripciones" está disponible,</p><p>Cuando se envía una solicitud POST con los detalles de la suscripción y el usuario asociado,</p><p>Entonces se recibe una respuesta con estado 201,</p><p>Y se registra la suscripción con un nuevo ID y los detalles registrados.</p><p>**Escenario 2: Suscripción ya existente**</p><p>Dado que el endpoint "/suscripciones" está disponible,</p><p>Cuando se intenta crear una nueva suscripción para un usuario que ya está suscrito,</p><p>Entonces se recibe una respuesta con estado 400,</p><p>Y se muestra un mensaje que indica "El usuario ya está suscrito".</p>|**EP07**|
|TS12|Get Subscription|<p>**Como** usuario developer de la aplicación Cambiazo,</p><p>**Quiero** poder obtener información sobre las suscripciones existentes en la plataforma a través del API,</p><p>**Para** mostrar esta información a los usuarios y permitirles gestionar sus suscripciones.</p>|<p>**Escenario 1: Obtener información de suscripción**</p><p>Dado que el endpoint "/suscripciones" está disponible,</p><p>Cuando se envía una solicitud GET con el identificador de la suscripción,</p><p>Entonces se recibe una respuesta con estado 200,</p><p>Y se obtienen los detalles de la suscripción solicitada.</p><p>**Escenario 2: Suscripción no encontrada**</p><p>Dado que el endpoint "/suscripciones" está disponible,</p><p>Cuando se envía una solicitud GET con un identificador de suscripción que no existe,</p><p>Entonces se recibe una respuesta con estado 404,</p><p>Y se muestra un mensaje que indica "No se encontró la suscripción".</p><p></p>|**EP07**|



## 3.3. Impact Mapping
En esta sección, nuestro equipo presenta el Impact Mapping, el cual es una herramienta visual y colaborativa que ayuda a los equipos a alinear sus objetivos con los resultados deseados.

<b>Segmento Intercambiadores</b><br>

<div align="center">

[![Impact Mapping.](https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Impact-Map/impact-map-1.PNG?raw=true)](https://uxpressia.com/w/ODLU6/i/7BZnN)
</div>


Enlace: [Impact Mappping en UXPRESSIA](https://uxpressia.com/w/ODLU6/i/7BZnN)

<b>Segmento Donadores</b><br>

<div align="center">

[![Impact Mapping.](https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Impact-Map/impact-map-2.PNG?raw=true)](https://uxpressia.com/w/ODLU6/i/M9ikH)
</div>


Enlace: [Impact Mapping en UXPRESSIA](https://uxpressia.com/w/ODLU6/i/M9ikH)



## 3.4. Product Backlog
En el Product Backlog presentaremos una lista priorizada de nuestras user stories según el nivel de prioridad que acordamos en el equipo, esencial para el *enfoque ágil*.Para analizar el nivel de dificultad de las tareas, utilizamos la secuencia de Fibonacci (1,2,3,5,8).
<br><br>
Tomamos como historia de usuario base la historia de usuario US12: Como usuario de la aplicación, quiero poder crear una nueva publicación de intercambio para ofrecer un artículo que deseo intercambiar

<br>

|# Orden |User Story Id|Título|Descripción|Story Points (1 / 2 / 3 / 5 / 8)|
| - | - | - | - | - |
|1|**US-01**|Registro de usuario|<p>Como nuevo usuario quiero completar el proceso de registro en la aplicación para establecer mi propia cuenta.</p><p></p>|3|
|2|**US-02**|<p>Editar perfil del usuario</p><p></p>|Como usuario ya registrado realizar modificaciones en mi perfil para asegurarme de que mi información esté siempre actualizada.|2|
|3|**US-03**|Iniciar sesión en la aplicación|Como usuario registrado quiero iniciar sesión en la aplicación para poder acceder a todas sus funcionalidades.|1|
|4|**US-04**|Cambiar Contraseña|<p>Como usuario registrado, quiero realizar cambios en la contraseña de mi cuenta para reforzar la seguridad de mi cuenta.</p><p></p>|2|
|5|**US-05**|<p>Cerrar Sesión</p><p></p>|<p>Como usuario registrado quiero cerrar sesión en la aplicación para asegurarme de que mi cuenta no quede almacenada en mi dispositivo móvil.</p><p></p>|1|
|6|**US-06**|Filtrado de Objetos|Como usuario Intercambiador, quiero la capacidad de filtrar los objetos disponibles de intercambio para encontrar la opción que mejor se adapte a mis preferencias de intercambio.|5|
|7|**US-07**|Filtrado de ONGs|Como usuario Donante, quiero la capacidad de filtrar las ONGs disponibles de donación para encontrar la opción que mejor se adapte a los objetos que tengo para donar|5|
|8|**US-08**|Brindar reseña sobre el Intercambiador|Como usuario intercambiador, deseo dejar una reseña sobre mi experiencia con el intercambiador para que otros usuarios puedan leer y considerar mi opinión antes de intercambiar|3|
|9|**US-09**|Eliminación de cuenta|Como usuario, quiero tener la opción de eliminar permanentemente mi cuenta para evitar que mi información persista en caso de que ya no desee utilizar la aplicación|3|
|10|**US-10**|Actualización de Correo Electrónico|Como usuario, quiero actualizar mi dirección de correo electrónico en mi perfil para asegurarme de que recibo notificaciones e información relevante|2|
|11|**US-11**|Configuración de notificaciones|Como usuario , quiero tener control sobre las notificaciones que recibo para personalizar mi experiencia en la web.|3|
|12|**US-12**|Crear publicación de intercambio|Como usuario de la aplicación, quiero poder crear una nueva publicación de intercambio para ofrecer un artículo que deseo intercambiar|5|
|13|**US-13**|Editar publicación de intercambio|Como usuario, necesito la capacidad de editar una publicación de intercambio existente para realizar cambios en los detalles del artículo o actualizar la información relevante.|3|
|14|**US-14**|Eliminar publicación de intercambio|Como usuario, quiero tener la opción de eliminar una publicación de intercambio que ya no deseo ofrecer para intercambiar.|2|
|15|**US-15**|Destacar publicación de intercambio|Como usuario, me gustaría poder resaltar una publicación de intercambio para aumentar su visibilidad entre otros usuarios.|3|
|16|**US-16**|Ampliar slots de publicación de intercambio|Como usuario, necesito la capacidad de aumentar el número de publicaciones de intercambio que puedo tener activas simultáneamente.|5|
|17|**US-17**|Visualizar el perfil del usuario que publique un intercambio|Como usuario, me gustaría tener la capacidad de visualizar el perfil de la persona que haya publicado un intercambio, para poder obtener información detallada de su confiabilidad.|3|
|18|**US-18**|Ponerse en contacto para pactar el intercambio|Como usuario, quiero tener la posibilidad de contactar directamente con el creador de una publicación de intercambio, para poder tener una comunicación más directa.|3|
|19|**US-19**|Ponerse en contacto para poder realizar una donación|Como usuario, quiero tener la posibilidad de contactar directamente con la organización benéfica correspondiente y/o visualizar información de contacto o número de cuenta bancaria para algún apoyo económico.|5|
|20|**US-20**|Adquirir la suscripción premium|Como usuario, quiero poder adquirir una suscripción premium para poder obtener beneficios adicionales que mejoren mi experiencia.|8|
|21|**US-21**|Cancelar una suscripción|<p>Como usuario quiero poder cancelar mi suscripción en cualquier momento para poder enfocarme más en las clases de la universidad</p><p></p>|3|
|22|**US-22**|Visualizar el perfil de las ONG’S registradas|**Como** usuario de la aplicación, **quiero** tener la opción de ver todas las ONG's disponibles **para** realizar donaciones.|3|
|23|**US-23**|Acceder al centro de soporte para resolver cualquier problema técnico que se presente.|**Como** usuario de CambiaZo, **quiero** tener la opción de acceder a un centro de soporte **para** reportar y resolver mis problemas técnicos.|3|
|24|**US-24**|Acceder dentro de la aplicación a la sección de preguntas frecuentes y comentarios|**Como** usuario de Cambiazo, **quiero** ver las preguntas frecuentes que tienen los demás usuarios y su opinión al usar la aplicación **para** poder ver si tienen mis mismas dudas y ver qué opinan de la aplicación.|3|
|25|**US-25**|Visualización de la Historia de la Startup|<p>**Como** usuario visitante, **quiero** poder acceder a la historia de la startup, su misión y visión desde la landing page **para** estar más informado acerca de TechZo.</p><p></p>|1|
|26|**US-26**|Visualizar las características clave de la aplicación|**Como** usuario visitante, **quiero** poder conocer sus características clave **para** saber qué es lo que incluye.|2|
|27|**US-27**|Acceder a un formulario para llenar mis datos de contacto y recibir noticias relacionadas con CambiaZo.|**Como** usuario visitante, **quiero** tener la opción de llenar un formulario con mi información de contacto, a través de la landing page, **para** recibir noticias y actualizaciones relevantes de CambiaZo.|5|
|28|**US-28**|Acceder a la página principal de CambiaZo|<p>Como usuario visitante, quiero encontrar botones o enlaces claramente visibles que me dirijan a la página web principal de Cambiazo, para poder realizar acciones como registrarme, intercambiar o donar artículos una vez que haya obtenido la información necesaria en la landing page.</p><p></p>|2|
|29|**US-29**|Ver los planes y precios|Como usuario visitante, quiero tener acceso a una sección que detalle los planes ofrecidos por la plataforma, para poder evaluar las opciones disponibles antes de acceder a la página web principal.|3|
|30|**US-30**|Navegación en la Landing Page|**Como** usuario visitante, **deseo** contar con un menú de navegación visible y funcional **para** que me permita desplazarme fácilmente por las diferentes secciones del sitio web.|3|
|31|**TS-01**|Create API User|<p>**Como** usuario desarrollador que configura la plataforma</p><p>**Quiero** diseñar una API que facilite la gestión de usuarios en nuestra aplicación</p><p>**Para** administrar eficazmente la información de los usuarios.</p><p></p>|5|
|32|**TS-02**|Post User|<p>**Como** usuario developer de la aplicación de Cambiazo</p><p>**Quiero** registrar usuario en un API</p><p>**Para** puedan navegar en mi aplicación web y usar sus funcionalidades</p>|3|
|33|**TS-03**|Get User|<p>**Como** usuario developer de la aplicación de Cambiazo</p><p>**Quiero** obtener la información de un usuario dentro de la API usuario</p><p>**Para** usarlo en la aplicación cuando se necesite</p><p></p>|2|
|34|**TS-04**|Create API Review|<p>**Como** usuario developer que configura la plataforma</p><p>**Quiero** implementar una API que permita a los usuarios dejar reseñas a otros usuarios</p><p>**Para** mejorar la interacción entre usuarios y la plataforma.</p>|5|
|35|**TS-05**|Post Review|<p>**Como** usuario developer de la aplicación de Cambiazo</p><p>**Quiero** registrar reseñas de los intercambios de un usuario en una API</p><p>**Para** mostrarlo en el perfil del usuario cuando se solicite.</p><p></p>|3|
|36|**TS-06**|Get Review|<p>**Como** usuario developer de la aplicación de Cambiazo</p><p>**Quiero** obtener informacion de las reseñas de intercambios de un usuario de la API reseñas</p><p>**Para** mostrarlas en el perfil del usuario</p><p></p>|2|
|37|**TS-07**|Create API ONGs|<p>**Como** usuario developer que configura la plataforma</p><p>**Quiero** quiero diseñar una API que simplifique la obtención de información sobre las ONGs</p><p>**Para** integrarla de manera efectiva en la aplicación.</p>|5|
|38|**TS-08**|Post ONGs|<p>**Como** usuario developer de la aplicación de Cambiazo</p><p>**Quiero** registrar las ONGs y sus detalles en una API</p><p>**Para** mostrarlas en la aplicación cuando se le solicite.</p><p></p>|3|
|39|**TS-09**|Get ONGs|<p>**Como** usuario developer de la aplicación de Cambiazo</p><p>**Quiero** mostrar en la aplicación las ONGs de la API ONGs</p><p>**Para** mostrarlas en la aplicación con su detalles.</p><p></p>|2|
|40|**TS-10**|Create API Subscription|<p>**Como** usuario developer que configura la plataforma</p><p>**Quiero** diseñar una API que facilite la gestión de suscripciones de usuarios</p><p>**Para** ofrecer beneficios al usuario</p>|5|
|41|**TS-11**|<p>Post Subscription</p><p></p>|<p>**Como** usuario developer de la aplicación Cambiazo,</p><p>**Quiero** implementar una API que permita a los usuarios suscribirse para obtener beneficios adicionales,</p><p>**Para** mejorar la experiencia del usuario y fomentar la participación en la plataforma.</p>|3|
|42|**TS-12**|Get Subscription|<p>**Como** usuario developer de la aplicación Cambiazo,</p><p>**Quiero** poder obtener información sobre las suscripciones existentes en la plataforma a través del API,</p><p>**Para** mostrar esta información a los usuarios y permitirles gestionar sus suscripciones.</p>|2|

<br><br>

A continuación se presenta una representación gráfica del mismo en la plataforma Pivotal Tracker:

<div align="center">

[![Product Backlog.](https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Product%20Backlog/Pivotal.jpg?raw=true)](https://www.pivotaltracker.com/n/projects/2699481)
</div>


Enlace: [Product Backlog en PivotalTracker](https://www.pivotaltracker.com/n/projects/2699481)<br><br>


---
# Capítulo IV: Product Design

## 4.1. Style Guidelines
En esta sección, compartimos nuestra propuesta de diseño para el landing page y la aplicación web, con el objetivo de ofrecer una interfaz intuitiva y fácil de usar para nuestros usuarios. Para lograrlo, hemos optado por utilizar recursos visuales que se adapten a la problemática que queremos abordar, al mismo tiempo que generan un atractivo visual para nuestro público objetivo.

### 4.1.1. General Style Guidelines
A continuación, se presentan las pautas generales para asegurar una presentación coherente de nuestros productos.<br>


**Colors:**

Hemos seleccionado cuidadosamente una paleta de colores para representar nuestro aplicativo CambiaZo. Nuestro enfoque se centra en tonalidades que incluyen el amarillo (#FFD146), el blanco (#FFFFFF), el negro (#000000) y degradados del negro para crear transiciones suaves entre los colores. Optamos por el amarillo para reflejar energía y positividad, el blanco para transmitir sofisticación y claridad, y el negro para agregar un toque de elegancia y prestigio. Además, el degradado del negro se utiliza para suavizar las transiciones entre los elementos visuales y añadir profundidad. Por último, el blanco humo (#F8F7F4) complementa la paleta al proporcionar un aspecto moderno y neutro. Este conjunto de colores busca armonizar con nuestra misión de resolver problemas y promover un ambiente de intercambio amigable y dinámico.<br>

<div align="center">
	<img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Style%20Guidelines/paleta-colores.PNG?raw=true" alt="Paleta de Colores"><br><br>
</div><br>

**Branding**

El branding es un proceso creativo fundamental que orienta el rumbo de una empresa y forja su identidad de marca. Su finalidad es la creación de marcas sólidas y fácilmente identificables en el mercado, logrando establecer una identidad y presencia apropiadas a través del diseño gráfico. En nuestro caso, el logo de la marca que queremos transmitir a nuestros usuarios es:

<div align="center">
	<img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Style%20Guidelines/branding.PNG?raw=true" alt="Logo CambiaZo"><br><br>
</div><br>


**Typography**

Elegir una fuente adecuada es esencial para lograr un diseño cohesivo y equilibrado que se alinee con la imagen e identidad de la marca. Esta elección refleja nuestro compromiso de construir una identidad visual sólida y reconocible. La tipografía, incluida la fuente, el tamaño y el ancho, contribuirá significativamente a la percepción y el reconocimiento de la marca en el mercado objetivo.<BR>
La tipografía utilizada será Montserrat, que incluye las variantes Regular, Medium, Semi-Bold y Bold. El tamaño de la letra varió entre 1 rem (16 px), 1.5 rem (24 px), 2 rem (32 px) y 3 rem (48 px).

+ **Montserrat - Google fonts**

<div align="center">

[![Montserrat - Google fonts](https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Style%20Guidelines/Montserrat.PNG?raw=true)](https://fonts.google.com/specimen/Montserrat) 
</div><br>


Referencia: [Montserrat - Google fonts](https://fonts.google.com/specimen/Montserrat)<br><br>

**Spacing**

El espacio en el diseño debe armonizar con la imagen general para lograr una apariencia uniforme y armoniosa. Aunque existen múltiples estilos de espaciado, como equipo hemos tendido a seguir las pautas de diseño de materiales y personalizarlos según las necesidades específicas de nuestro proyecto.<br>

- **Botones**: Establecemos un margen interior (padding) de 1 rem (16 px) en la dirección vertical y de 2 rem (32 px) en la horizontal.
- **Márgenes entre texto**: Mantenemos un margen de 1 rem (16 px) entre elementos de texto.
- **Márgenes entre elementos**: Garantizamos un margen de 1.5 rem (24 px) entre distintos elementos.
- **Márgenes entre secciones**: Fijamos un margen de 6 rem (72 px) para separar claramente las diferentes secciones de contenido.<br><br>


**Dimensions** 

En esta sección, describiremos los diferentes tonos que utilizamos, desde la emoción por explorar hasta el compromiso con la responsabilidad social, y proporcionaremos ejemplos de cómo aplicarlos en nuestra comunicación escrita. A continuación, se presentarán el lenguaje y tonos que usamos para nuestros segmentos objetivo.

- **Usuario Intercambiadores**:  Empleamos un lenguaje más práctico y dinámico, centrado en la conveniencia y la utilidad de la plataforma para facilitar el intercambio de objetos. El tono es amigable y directo, enfocado en resaltar las ventajas y beneficios de utilizar el servicio de intercambio. Se destaca la variedad de opciones disponibles y se promueve la idea de una comunidad colaborativa donde todos pueden encontrar lo que necesitan y compartir lo que ya no utilizan.

- **Usuario Donadores**: En constraste, utilizamos un lenguaje cálido y empático que resalte la importancia del acto de la donación y el impacto positivo que puede tener en la vida de otras personas. El tono es inspirador y motivador, invitando a los usuarios a sentirse parte de una causa noble y a generar un cambio positivo en la comunidad. Se enfatiza la gratitud y el reconocimiento hacia los donadores por su generosidad.



### 4.1.2. Web Style Guidelines

En nuestras pautas de estilo web, priorizamos la adaptación de nuestros principios de diseño a la experiencia de usuario en entornos de navegación en línea. Esto incluye:

- **Diseño Responsivo**: Nos aseguramos de que nuestro sitio web se adapte fluidamente a diferentes tamaños de pantalla, desde computadoras de escritorio hasta dispositivos móviles como tabletas y teléfonos inteligentes. Esto garantiza que los usuarios puedan acceder y disfrutar de la plataforma sin importar el dispositivo que utilicen.

- **Navegación Intuitiva**: Implementamos una barra de navegación (Navbar) clara y organizada que facilita el acceso a las diferentes secciones del sitio. Para mejorar la experiencia en dispositivos móviles, incorporamos un "Botón hamburguesa" que despliega el menú principal de manera compacta y fácilmente accesible en pantallas más pequeñas. Esto permite a los usuarios navegar por el sitio de manera intuitiva y eficiente.

- **Consistencia Visual**: Mantenemos una estética coherente en todo el sitio, utilizando colores, tipografías y elementos visuales que reflejen la identidad de marca de Cambiazo. Esto ayuda a crear una experiencia de usuario unificada y memorable en todas las páginas y dispositivos.

- **Accesibilidad**: Nos esforzamos por hacer que nuestro sitio sea accesible para todos los usuarios, incluidos aquellos con discapacidades visuales o de movilidad. Esto implica utilizar etiquetas alt en imágenes, asegurar un contraste adecuado entre texto y fondo, y proporcionar opciones de navegación alternativas para usuarios con dificultades para interactuar con el sitio de forma estándar.

Al adherirnos a estos principios de diseño, nos comprometemos a ofrecer una experiencia web que sea fácil de usar, estéticamente atractiva y accesible para todos los usuarios, independientemente de su dispositivo o capacidad.


## 4.2. Information Architecture
En Cambiazo, la arquitectura de la información se centra en organizar el contenido de manera intuitiva y accesible tanto en la página de inicio como en las aplicaciones web y móviles. Implementamos sistemas de organización claros y efectivos, como la jerarquía visual y la categorización por temas, junto con una etiquetación precisa para garantizar una navegación fluida y una búsqueda eficiente de productos. Además, ofrecemos una navegación intuitiva con opciones claras de búsqueda y filtros avanzados, lo que permite a los usuarios encontrar fácilmente lo que necesitan sin esfuerzo. Esto se traduce en una experiencia coherente y satisfactoria para los visitantes y usuarios de Cambiazo.

### 4.2.1. Organization Systems
En Cambiazo, aplicaremos varios sistemas de organización de información para garantizar una experiencia de usuario fluida y efectiva. Aquí está cómo se implementarán:

**Organización visual del contenido:**

- **Jerárquica (Visual Hierarchy):** Utilizaremos la organización jerárquica para destacar la información importante y guiar a los usuarios a través de los diferentes niveles de contenido. Por ejemplo, en la página de inicio, los productos destacados tendrán un tamaño y ubicación prominentes para captar la atención del usuario formando parte de un slide infinito.

- **Organización secuencial (Step-by-step):** Implementaremos la organización secuencial en los procesos de registro de usuario, creación de listados de productos y confirmación de intercambios. Esto ayudará a los usuarios a completar tareas de manera efectiva, paso a paso, sin confusiones.

**Esquemas de categorización de contenido:**

- **Por tópicos:** Categorizamos los productos disponibles para intercambiar en diferentes temas o categorías, como electrónica, ropa, libros, etc. Esto facilitará a los usuarios encontrar rápidamente lo que están buscando.

- **Según audiencia (Grupos de usuarios):** Implementaremos esquemas de categorización de contenido basados en los intereses y necesidades de diferentes grupos de usuarios. Por ejemplo, podríamos tener una sección especial para artículos infantiles, otra para artículos deportivos, etc., para satisfacer las necesidades específicas de cada grupo de usuarios.

- **Cronológico:** Utilizaremos la organización cronológica para mostrar eventos importantes, como promociones especiales, actualizaciones de la aplicación y noticias relevantes para la comunidad de Cambiazo.

- **Alfabético:** Algunas secciones de la aplicación, como los productos de intercambio o la sección de preguntas frecuentes, podrían organizarse alfabéticamente para facilitar la búsqueda y navegación.

Al aplicar estos sistemas de organización de información, nos aseguraremos de que los usuarios puedan encontrar fácilmente lo que necesitan y completar sus tareas de manera eficiente en la plataforma Cambiazo.



### 4.2.2. Labeling Systems
En esta sección, vamos a presentar el sistema de etiquetado que proporcionará una descripción concisa y clara de la información presentada en cada una de nuestras aplicaciones. Comenzaremos detallando los encabezados que estarán disponibles en nuestra landing page.

- **Inicio/Home:** Esta sección preseleccionada por defecto ofrecerá una visión general de Cambiazo y su propósito principal, proporcionando una introducción a la plataforma y sus funciones clave.

- **Conócenos/About Us:** En esta sección, los usuarios pueden conocer al equipo detrás de Cambiazo, su misión y visión, así como obtener una comprensión más profunda de lo que impulsa la plataforma.

- **Características/Features:** La sección de Características se encuentran los beneficios específicos que ofrece Cambiazo para sus Usuarios, destacando cómo la plataforma puede satisfacer sus necesidades de intercambio de productos de manera efectiva.

- **ONGs Afiliadas/Affiliated NGOs:** Aquí se destacan las organizaciones no gubernamentales asociadas con Cambiazo.

- **Planes/Subscriptions:** En esta sección se presentarán los diferentes planes de suscripción disponibles en Cambiazo, junto con sus características y precios, permitiendo a los usuarios elegir la opción que mejor se adapte a sus necesidades y preferencias de intercambio.

- **Contáctanos/Contact Us:** Esta sección proporcionará a los usuarios la información de contacto de Cambiazo, incluidos los correos electrónicos, números de teléfono y posiblemente un formulario de contacto para consultas o comentarios.

- **Registrarse/Sign Up:** En esta sección, los usuarios podrán registrarse para obtener una cuenta en Cambiazo, donde podrán acceder a todas las funciones de la plataforma, incluido el intercambio de productos. Se proporcionarán campos para que los usuarios ingresen su información personal y se configuren sus cuentas de usuario.

### 4.2.3. SEO Tags and Meta Tags
Para mejorar el posicionamiento en motores de búsqueda y brindar una experiencia optimizada a los usuarios, aquí están los SEO Tags y Meta Tags que utilizaríamos en Cambiazo:

Encabezado: Aunque técnicamente no es un meta-tag, se considera vital en el encabezado del HTML ya que proporciona el título de la página web. Los motores de búsqueda utilizan este título para encabezar las entradas en los resultados de búsqueda, dándole así una gran importancia para la visibilidad del sitio.

Descripción: Este campo permite ofrecer una descripción breve y clara del contenido del sitio web. Esta descripción se muestra como un fragmento debajo de la URL en los resultados de búsqueda, lo que resulta crucial para atraer la atención de los usuarios y mejorar el SEO del sitio.

Palabras clave (Keywords): Aunque en el pasado fue crucial para el posicionamiento en motores de búsqueda, su relevancia ha disminuido. Aun así, aún se puede usar para proporcionar palabras clave relevantes para el contenido del sitio, aunque su impacto en el SEO actual es limitado.

Autor y Derechos de Autor: Estas etiquetas meta identifican al diseñador de la página web y al propietario de los derechos de autor del código fuente HTML. Aunque no influyen directamente en el SEO, son importantes para atribuir la autoría y proteger los derechos de propiedad intelectual del sitio web.

**Landing Page:**
- **Título:**
```html
<title>
Cambiazo - Intercambia artículos de forma segura y justa
</title>
```

- Descripción:
```
  
 <meta name="description" content="Intercambia artículos de manera segura y justa con Cambiazo. Explora una amplia variedad de productos, garantizando transacciones transparentes y beneficiosas para todos."/>

```

- Palabras clave:
```

<meta name="keywords" content="Intercambio de artículos, plataforma de intercambio, seguridad en el intercambio, justicia en el intercambio, comunidad de intercambio, donaciones de artículos."/>
```

+ Autor:
```

<meta name="author" content="TechZo Startup" />

```

- Copyright:
```

<meta name="copyright" content="© TechZo, 2024" />

```
**Web Application**
- **Título:**
```html
<title>
Cambiazo - Tu plataforma de intercambio confiable
</title>
```

- Descripción:
```
  
 <meta name="description" content="Descubre una nueva forma de intercambiar artículos con Cambiazo. Regístrate hoy para acceder a una comunidad dedicada a transacciones seguras y transparentes."/>

```

- Palabras clave:
```

<meta name="keywords" content="Intercambio seguro, comunidad de intercambio, plataforma de intercambio de artículos, transacciones justas, donaciones de artículos."/>
```

- Autor:
```

<meta name="author" content="TechZo Startup" />

```

- Copyright:
```

<meta name="copyright" content="© TechZo, 2024" />

```

Estos tags están diseñados para resaltar los aspectos clave de Cambiazo, como la seguridad en los intercambios, la justicia en las transacciones y la posibilidad de realizar donaciones de artículos. Esto ayuda a mejorar la visibilidad en los motores de búsqueda y atraer a usuarios interesados en la plataforma.<br><br>



### 4.2.4. Searching Systems

Para garantizar una experiencia de búsqueda eficiente y satisfactoria para los usuarios en Cambiazo, implementaremos un sistema de búsqueda robusto con varias opciones y filtros. Aquí está cómo será el sistema de búsqueda:

- **Búsqueda básica:** Ofreceremos un campo de búsqueda simple en la parte superior de cada página, donde los usuarios podrán ingresar palabras clave relacionadas con los productos que desean encontrar. Esto proporcionará una forma rápida y directa de buscar artículos específicos.

- **Filtros avanzados:** Permitiremos a los usuarios refinar sus resultados de búsqueda utilizando filtros avanzados como categoría de producto. Estos filtros ayudarán a los usuarios a encontrar exactamente lo que están buscando y a reducir el volumen de información para evitar la sobrecarga de datos.

- **Ordenación de resultados:** Después de realizar una búsqueda, los usuarios podrán ordenar los resultados según diferentes criterios, como relevancia, precio ascendente/descendente, fecha de publicación, etc. Esto les permitirá encontrar los productos más adecuados de manera rápida y eficiente.

- **Vista de resultados clara y detallada:** Mostraremos los resultados de búsqueda de manera clara y ordenada, con información relevante y detallada sobre cada producto, incluyendo imágenes, título, descripción, precio y ubicación del vendedor. Esto facilitará a los usuarios evaluar y comparar los productos encontrados.

- **Sugerencias de búsqueda:** Proporcionaremos sugerencias de búsqueda mientras los usuarios escriben en el campo de búsqueda, ayudándoles a encontrar términos relevantes y populares relacionados con su consulta.

Al ofrecer estas opciones de búsqueda y filtros, junto con una presentación clara y detallada de los resultados, buscamos garantizar que los usuarios puedan encontrar fácilmente los productos que están buscando en Cambiazo, sin sentirse abrumados por el volumen de información disponible.



### 4.2.5. Navigation Systems

Para guiar a los usuarios a través del Landing Page y las aplicaciones de Cambiazo de manera efectiva, implementaremos diversas acciones y técnicas de navegación:

- **Menú de navegación claro y conciso:** En la parte superior de cada página, proporcionaremos un menú de navegación que incluya enlaces directos a las secciones principales de la plataforma, como "Inicio", "Donaciones", "Mi perfil" y "Ayuda". Esto permitirá a los usuarios acceder rápidamente a las funciones y áreas que deseen explorar.

- **Búsqueda prominente:** Colocaremos un campo de búsqueda bien visible en la parte superior de cada página, permitiendo a los usuarios buscar productos específicos, categorías o ong’s dentro de la plataforma de manera rápida y sencilla.

- **Botones de llamada a la acción (CTA):** Utilizaremos botones de CTA estratégicamente ubicados para dirigir a los usuarios hacia acciones importantes, como "Publicar", "Inicia sesión", "Inicio", "Categorías", etc. Estos botones ayudarán a los usuarios a tomar decisiones y avanzar en su experiencia en la plataforma.

- **Navegación intuitiva:** Diseñaremos la estructura de la plataforma de manera intuitiva, siguiendo convenciones de diseño web estándar y asegurándonos de que la navegación sea coherente en todas las páginas. Esto ayudará a los usuarios a sentirse cómodos y seguros mientras exploran y utilizan Cambiazo.

Al implementar estas acciones y técnicas de navegación, buscamos garantizar que los usuarios puedan cumplir sus objetivos de manera satisfactoria y disfrutar de una experiencia fluida y sin problemas en la plataforma Cambiazo.


## 4.3. Landing Page UI Design.
### 4.3.1. Landing Page Wireframe.
Para la creación del esquema inicial de nuestra página de inicio (landing page), se empleó la plataforma Figma en conjunto con una variedad de complementos que simplificaron considerablemente el proceso de diseño y desarrollo. Esta combinación de herramientas permitió una producción eficiente y efectiva del wireframe.

Enlace: [Wireframe del Landing Page en Figma](https://www.figma.com/file/EuSz7z4cWAICYsdKoDvK93/Untitled?type=design&mode=design&t=GUEZeeg6jgtCP6yE-1)<br><br>

**Landing Page**

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Wireframe/Wireframe_desktop.png?raw=true" width="600px" alt="Wireframe">
</div><br><br>

**Landing Page en Mobile Web Browser**

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Wireframe/Wireframe_mobile.png?raw=true" width="300px" alt="Wireframe Mobile">
</div><br><br>




### 4.3.2. Landing Page Mock-up.
Hemos completado con éxito la creación del mock-up de la página de inicio, lo que nos ha permitido destacar y aplicar los principios y elementos de diseño que hemos establecido. Estos principios y pautas heurísticas desempeñan un papel fundamental al hacer que la experiencia para los usuarios finales de nuestra plataforma sea más sencilla e intuitiva.

Enlace: [Mock-up del Landing Page en Figma](https://www.figma.com/file/EuSz7z4cWAICYsdKoDvK93/Untitled?type=design&mode=design&t=GUEZeeg6jgtCP6yE-1)<br><br>

**Landing Page**

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Mock-up/Mock-up_desktop.png?raw=true" width="600px" alt="Mockup">
</div><br><br>

**Landing Page en Mobile Web Browser**

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Mock-up/Mock-up_mobile.png?raw=true" width="300px" alt="Mockup Mobile">
</div><br><br>

## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes
Los wireframes son esenciales en el diseño de nuestras aplicaciones, ya que ayudan a planificar la interfaz y la navegación antes de empezar el desarrollo. En nuestro proyecto, utilizamos 'Figma' para crear los wireframes de manera eficiente y colaborativa.

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Web-Application-Wireframe/wireframe-0.png?raw=true"  alt="wireframes-appweb">
</div><br><br>

Enlace: [Wireframes de la App Web en Figma](https://www.figma.com/file/VpmoDnfHRERQvKTwxnOjLe/CambiaZo?type=design&node-id=0%3A1&mode=design&t=6tWRPswBDZfqgYDM-1)<br><br>

A continuación, mostramos los wireframes de nuestra aplicación web:


<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Web-Application-Wireframe/wireframe-1.png?raw=true"  alt="wireframes-1"><br><br>
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Web-Application-Wireframe/wireframe-2.png?raw=true"  alt="wireframes-2"><br><br>
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Web-Application-Wireframe/wireframe-3.png?raw=true"  alt="wireframes-3"><br><br>
</div><br>

Estos wireframes se centran en la funcionalidad de inicio de sesión, registro y cambio de contraseña en la aplicación web. La disposición de los elementos se ha optimizado para una interacción intuitiva del usuario, sin considerar detalles de diseño.<br><br>

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Web-Application-Wireframe/wireframe-4.png?raw=true"  alt="wireframes-4">
</div><br>

La página de inicio presenta las publicaciones de usuarios de manera organizada y equitativa. Se incluirá una barra de búsqueda y categorías para facilitar la navegación.<br><br>


<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Web-Application-Wireframe/wireframe-5.png?raw=true"  alt="wireframes-5">
</div><br>

Esta página mostrará una lista de organizaciones benéficas registradas, con espacio entre cada una para una mejor legibilidad. Se incluirá una barra de búsqueda dinámica para facilitar la exploración.<br><br>

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Web-Application-Wireframe/wireframe-6.png?raw=true"  alt="wireframes-6">
</div><br>

La página de membresía presentará los distintos planes de membresía de forma clara y ordenada, con información concisa sobre los beneficios de cada plan.<br><br>


<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Web-Application-Wireframe/wireframe-7.png?raw=true"  alt="wireframes-7">
</div><br>

El formulario de publicación de objetos estará diseñado de manera intuitiva, con secciones claras y espacio suficiente entre ellas para una fácil comprensión. Los campos importantes se destacarán para mejorar la experiencia del usuario.<br><br>

### 4.4.2. Web Applications Wireflow Diagrams

A continuación, se presentan los wireflows que competen a nuestros user goals.

**User goal 1:** Como usuario, quiero poder iniciar sesión y poder recuperar mi contraseña en caso de pérdida.

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Wireflow-Diagram/wireflow-diagram-1.png?raw=true" alt="wireflow 1">
</div><br>
El usuario entra a la página web y se encuentra con el inicio de la misma, en la cuál verá todas las publicaciones de intercambios destacadas, incluso aquellas que poseen un boost. Para poder iniciar sesión deberá dar click al botón en la parte superior derecha, para luego ser redirigido a otra ventana en la cual podrá ingresar su correo y contraseña.
En caso el usuario haya olvidado la contraseña, tendrá la posibilidad de recuperar y cambiarla mediante un correo de confirmación para luego introducir un código de verificación.<br><br>

**User goal 2:** Como usuario, quiero poder revisar información detallada de las organizaciones benéficas que puedo apoyar.

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Wireflow-Diagram/wireflow-diagram-2.png?raw=true" alt="wireflow 2">
</div><br>
El usuario entra a la página web y se dirige a una de las opciones de la barra de navegación que se llama “Donaciones”, en ella podrá visualizar todas las organizaciones benéficas afiliadas a CambiaZo, además de poder filtrar por categorías. Al clickear en una de estas, podrá visualizar información más detallada de la misma.<br><br>



**User goal 3:** Como usuario, quiero poder tener la posibilidad de suscribirse a una membresía y de esta forma obtener mejores beneficios.

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Wireflow-Diagram/wireflow-diagram-3.png?raw=true"  alt="wireflow 3">
</div><br>
El usuario entra a la página web, se dirige a la barra navegadora y clickea en la opción de Membresías, en la cuál podrá visualizar todas las suscripciones disponibles con su información detallada. Al momento de seleccionar una, será redirigido a una pasarela de pagos para luego recibir un pop-up de confirmación.<br><br>

**User goal 4:** Como usuario, quiero poder verificar información sobre términos y condiciones de la compañía y política de uso

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Wireflow-Diagram/wireflow-diagram-4.png?raw=true"  alt="wireflow 4">
</div><br>
El usuario entra a la página web, se dirige al footer de la misma y clickea en las opciones de términos y condiciones y/o políticas de uso, en donde podrá visualizar todos los términos legales y de uso de CambiaZo.<br><br>


**User goal 5:** Como usuario, quiero poder visualizar información de ayuda y/o tener la posibilidad de solicitar soporte al equipo de desarrollo.

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Wireflow-Diagram/wireflow-diagram-5.png?raw=true"  alt="wireflow 5">
</div><br>

El usuario entra a la página web, se dirige al footer de la misma y clicke en Ayuda y/o Soporte. En la primera ventana podrá verificar información de ayuda básica sobre la página, si es que tiene algún inconveniente más específico, puede contactarse con nuestro soporte técnico.<br><br>



**User goal 6:** Como usuario quiero poder publicar mis intercambios de una manera rápida y accesible.

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Wireflow-Diagram/wireflow-diagram-6.png?raw=true"  alt="wireflow 6">
</div><br>

El usuario entra a la página web y se redirige al botón de la parte superior derecha que dice “Publicar”. Una vez dentro, saldrá un formulario para que el usuario ya con una sesión iniciada, pueda realizar su publicación de intercambio, incluir datos y fotos. Para finalizar le saldrá un pop-up con un mensaje de confirmación.<br><br>


**User goal 7:** Como usuario quiero poder filtrar mi búsqueda de objetos, recibir información solo de estos mismos y visualizar información pertinente y necesaria.


<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Wireflow-Diagram/wireflow-diagram-7.png?raw=true"  alt="wireflow 7">
</div><br>

El usuario entra a la página web y clickea en algunos de los botones de categorías disponibles. Después de ello se redirigirá a una ventana en la que salgan todos los resultados de publicaciones encontradas con esa misma categoría. Además de filtros específicos e información básica.<br>Una vez el usuario clickee en cualquier card de publicación, podrá ver la información de la publicación con más detalle e información del autor de la publicación.<br><br>




**User goal 8:** Como usuario quiero poder realizar una oferta, teniendo en consideración los intercambios publicados que tengo en mi perfil.

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Wireflow-Diagram/wireflow-diagram-8.png?raw=true"  alt="wireflow 8">
</div><br>

Una vez el usuario haya seleccionado la publicación de interés, puede darle click a “Ofertar”. Después de ello, saldrá una ventana en la cual el usuario puede seleccionar cualquiera de sus publicaciones en su “stock” para ofrecer. Después de ello, recibirá un mensaje de confirmación. <br><br>


**User goal 9:** Como usuario quiero poder visualizar mis publicaciones en mi perfil y administrarlas según mis necesidades.

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Wireflow-Diagram/wireflow-diagram-9.png?raw=true"  alt="wireflow 9">
</div><br>

El usuario se dirige al ícono de perfil, para luego visualizar las publicaciones que ha realizado en el momento. Después de ello, al darle click en “Editar perfil”, podrá ver la configuración de notificaciones que tenga, además de poder editar su información personal.<br><br>


**User goal 10:** Como usuario, quiero poder verificar las ofertas que he recibido por mis publicaciones y aceptarlas o declinar en caso contrario.

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Wireflow-Diagram/wireflow-diagram-10.png?raw=true"  alt="wireflow 10">
</div><br>

  Dirigirse a la sección de perfil, para luego clickear en Ofertas, se tiene que seleccionar “Recibidas”, una vez hecho ello, se podrá visualizar todos las ofertas recibidas por las publicaciones que hemos hecho.<br><br>

Enlace: [Wireflows en LucidChart 1](https://lucid.app/lucidchart/63364102-d93b-47fe-a04f-fce263593fdf/edit?viewport_loc=-5194%2C-809%2C20455%2C7652%2C0_0&invitationId=inv_451c4fe8-c20d-4e3d-8ab3-e8df00c42f3e)<br><br>

Enlace: [Wireflows en LucidChart 2](https://lucid.app/lucidchart/ded0e94e-a2ae-4af8-84a9-30eda1490a8c/edit?viewport_loc=-422%2C4306%2C3790%2C1418%2C0_0&invitationId=inv_12e34c87-1186-4aa4-8ddb-ca02798fcd0c)<br><br>

### 4.4.3. Web Applications Mock-ups
Los mockups son otra parte esencial en el diseño de nuestras aplicaciones, ya que nos permiten visualizar la apariencia y la disposición de los elementos antes de comenzar el desarrollo.

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Web-Application-MockUp/mock-up-0.png?raw=true"  alt="mockups-appweb">
</div><br><br>

Enlace: [Mock-up de la App Web en Figma](https://www.figma.com/file/VpmoDnfHRERQvKTwxnOjLe/CambiaZo?type=design&node-id=0%3A1&mode=design&t=6tWRPswBDZfqgYDM-1)<br><br>


A continuación, mostramos los mock-ups de nuestra aplicación web.
<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Web-Application-MockUp/mock-up-1.png?raw=true"  alt="mockups-1"><br><br>
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Web-Application-MockUp/mock-up-2.png?raw=true"  alt="mockups-2"><br><br>
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Web-Application-MockUp/mock-up-3.png?raw=true"  alt="mockups-3"><br><br>
</div><br>
Páginas para el inicio de sesión, registro y cambio de contraseña en la aplicación web, con botones minimalistas con bordes redondeados y diseño agradable en nuestro color amarillo distintivo. Presentamos texto amigable y el nombre de la aplicación de manera prominente para generar percepción y reconocimiento de marca entre los usuarios. Utilizamos iconos destacados con sombreado para una fácil identificación visual por parte del usuario. Al finalizar exitosamente las operaciones, mostramos mensajes con el título resaltado en un tamaño mayor, identificados por su importancia, acompañados de un texto agradable y sencillo para mejorar la experiencia del usuario.<br><br>

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Web-Application-MockUp/mock-up-4.png?raw=true"  alt="mockups-4">
</div><br>
La página de inicio muestra el logo de la aplicación para identificación rápida. Destaca las publicaciones de usuarios en cuadros equitativamente espaciados y sombreados para una apariencia ordenada y atractiva. Las publicaciones se dividen en dos tipos: las últimas y las más destacadas, estas últimas presentadas en un scroll para mayor atención del usuario y facilidad al buscarlas. La información relevante de las publicaciones se resalta mediante el tamaño de letra y otros elementos visuales para una mejor comprensión. Además, se muestra una barra de búsqueda dinámica y debajo, categorías resaltadas en amarillo que se destacan para llamar la atención del usuario de manera efectiva; estas categorías funcionan para una búsqueda rápida y dinámica por parte de los usuarios, garantizando una experiencia cómoda, agradable y visualmente atractiva.<br><br>

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Web-Application-MockUp/mock-up-5.png?raw=true"  alt="mockups-5">
</div><br>
Página que muestra una lista de organizaciones benéficas registradas, con un diseño minimalista y espacio entre ellas para una mejor organización. Utilizamos botones con un color amarillo que resalta y es más visible para el usuario. Además, implementamos una barra de búsqueda dinámica para buscar organizaciones por nombre y por localidades, así como también por categorías mediante botones. Mantenemos una estética visual coherente con un diseño minimalista en toda la aplicación, lo que facilita su navegación y la hace más intuitiva para los usuarios.<br><br>


<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Web-Application-MockUp/mock-up-6.png?raw=true"  alt="mockups-6">
</div><br>
Al acceder a la página de membresía, los usuarios son recibidos por un texto destacado en color amarillo que les invita de manera llamativa a formar parte de nuestra plataforma. Seguidamente, se presentan los distintos planes de membresía en cuadros rectangulares con bordes suavemente redondeados, distribuidos de manera equitativa en la página. En cuanto a la estética, los bordes de estos rectángulos están resaltados en amarillo, mientras que los paneles laterales exhiben un fondo blanco con un borde amarillo sutil, y el panel central se muestra con un fondo amarillo, atrayendo así la atención del usuario hacia los detalles de cada plan.Además se detallan los beneficios de cada plan en cuadros con texto breve para mantener la presentación ordenada. Cada cuadro está equipado con un botón negro de bordes redondeados que permite a los usuarios seleccionar su membresía y realizar el pago. Los beneficios de cada plan están listados con un icono de marca de verificación en color negro para resaltarlos junto con el texto en el mismo tono. Esta estructura visual y organización de la información hace que sea fácil para los usuarios comprender y elegir la membresía que mejor se adapte a sus necesidades.<br><br>


<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Web-Application-MockUp/mock-up-7.png?raw=true"  alt="mockups-7">
</div><br>
En la página de publicación de objetos, hemos diseñado un formulario intuitivo con instrucciones claras para guiar al usuario en todo el proceso. El formulario está dividido en secciones con subtítulos claramente definidos y un espacio equitativo entre ellos para una mejor organización visual. Cada sección cuenta con un sutil sombreado con un diseño minimalista, que proporciona una experiencia agradable y cómoda para el usuario. Además, los campos importantes se destacan mediante un tamaño de letra más grande y negrita, lo que facilita su identificación y comprensión durante la creación de la publicación. También hemos incluido un botón de "Publicar" en color amarillo, destacando visualmente sobre las demás secciones para que el usuario identifique intuitivamente que ese botón es para finalizar y publicar la información.<br><br>

### 4.4.4. Web Applications User Flow Diagrams

A continuación, se presentan los diagramas de flujo de usuarios relacionados con nuestros objetivos de usuario.

**User Goal 1:** Como usuario, quiero ingresar a la aplicación web utilizando una cuenta.

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/User-Flow-Diagram/goal%201.png?raw=true" alt="userflow 1">
</div><br>

El usuario accede a la aplicación. Se le presenta una ventana para iniciar sesión si ya tiene una cuenta; de lo contrario, debe registrarse. Si inicia sesión correctamente, puede usar todas las funciones de la aplicación. Si se registra con los datos correctos, se le muestra una ventana de confirmación y es llevado a la página de inicio de sesión.<br><br>


**User Goal 2:** Como usuario, quiero buscar objetos para intercambiar fácilmente y obtener información detallada sobre ellos.

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/User-Flow-Diagram/goal%202.png?raw=true" alt="userflow 2">
</div><br>

El usuario está en la página de inicio. Visualiza objetos publicados por otros usuarios, incluyendo los destacados y los últimos publicados. Al seleccionar un objeto, es dirigido a otra página con más detalles sobre la publicación. También puede explorar las publicaciones al seleccionar las categorías desde la página de inicio.<br><br>



**User Goal 3:** Como usuario, quiero que otros usuarios vean los objetos que publiqué para intercambiar.

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/User-Flow-Diagram/goal%203.png?raw=true" alt="userflow 3">
</div><br><br>

Desde la página de inicio, el usuario selecciona la opción de publicar. Es llevado a una página para crear una nueva publicación. Después de completar los datos necesarios y confirmar la publicación, recibe un mensaje de confirmación y su publicación es mostrada a todos los usuarios.<br><br>

**User Goal 4:** Como usuario, quiero solicitar un intercambio a cambio de uno de los objetos de mi publicación.

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/User-Flow-Diagram/goal%204.png?raw=true" alt="userflow 4">
</div><br><br>

Al visualizar una publicación, el usuario presiona el botón "Ofertar". Se le muestra una ventana con sus propios objetos publicados, y puede seleccionar uno para proponer un intercambio. Recibe un mensaje de agradecimiento por parte de la aplicación.<br><br>

**User Goal 5:** Como usuario, quiero ser notificado cuando reciba una solicitud de intercambio y tener la opción de aceptar o rechazarla.

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/User-Flow-Diagram/goal%205.png?raw=true" alt="userflow 5">
</div><br><br>

El usuario accede a las ofertas enviadas desde su perfil, donde encuentra las solicitudes de intercambio de otros usuarios. Puede aceptar una oferta, lo que le muestra un mensaje de confirmación y la opción de contactar al usuario por Telegram o WhatsApp para coordinar el intercambio. También puede rechazar la oferta.<br><br>


**User Goal 6:** Como usuario, quiero explorar y buscar ONGs y acceder a la información detallada sobre ellas.

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/User-Flow-Diagram/goal%206.png?raw=true" alt="userflow 6">
</div><br><br>

Desde la página de inicio, el usuario accede a la sección de donaciones. Encuentra una lista de todas las ONGs disponibles y al seleccionar una, se le muestra información detallada sobre la misma.<br><br>


**User Goal 7:** Como usuario, quiero explorar y obtener información sobre los perfiles de otros usuarios.

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/User-Flow-Diagram/goal%207.png?raw=true" alt="userflow 7">
</div><br><br>

Mientras visualiza una publicación, el usuario accede al perfil del usuario que la publicó para ver más información sobre él.<br><br>


**User Goal 8:** Como usuario, quiero tener la opción de  pagar una membresía y disfrutar de los beneficios que ofrece.

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/User-Flow-Diagram/goal%208.png?raw=true" alt="userflow 8">
</div><br><br>

Desde la página de inicio, el usuario accede a la sección de membresías y elige el plan de su preferencia. Realiza la suscripción a través de una pasarela de pago. Una vez completado el pago con éxito, recibe un mensaje de confirmación.<br><br>

**User Goal 9:** Como usuario, quiero tener acceso claro y fácil a toda la información relevante de la aplicación.

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/User-Flow-Diagram/goal%209.png?raw=true" alt="userflow 9">
</div><br><br>

Desde la página de inicio, el usuario accede a información pertinente de la aplicación, como condiciones de uso, políticas de privacidad y sección de ayuda, además de la sección de contacto para comunicarse con la empresa al completar un formulario.<br><br>

**User Goal 10:** Como usuario, quiero poder realizar modificaciones en mis publicaciones si considero que necesitan ajustes.

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/User-Flow-Diagram/goal%2010.png?raw=true" alt="userflow 10">
</div><br><br>

Desde su perfil, el usuario accede a la sección de publicaciones al presionar el botón de tres puntos puede eliminar una publicación, lo que le solicita confirmación antes de eliminarla. También puede editar una publicación, lo que le permite modificar la información mediante un formulario.<br><br>



**User Goal 11:** Como usuario, quiero realizar cambios en mi perfil y mantenerlo actualizado con la información más reciente.

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/User-Flow-Diagram/goal%2011.png?raw=true" alt="userflow 11">
</div><br><br>

Desde la página de inicio, el usuario accede a su perfil y realiza modificaciones, como cambiar su foto de perfil, sus datos personales o contraseña. Al cambiar la contraseña, se le muestra un formulario para realizar los cambios y al presionar “Cambiar” se le muestra un mensaje de confirmación.<br><br>

Enlace: [User Flow 1 en LucidChart](https://lucid.app/lucidchart/43f6d75d-44c8-4170-bd1c-99fd21312c75/edit?viewport_loc=-3569%2C-5403%2C2791%2C1048%2C0_0&invitationId=inv_f07bff56-c57f-4cbb-8b02-8c692958e133)<br><br>

Enlace: [User Flow 2 en LucidChart](https://lucid.app/lucidchart/4966c7f2-f561-43f5-97c3-4dae978dbcfb/edit?viewport_loc=-2622%2C-8651%2C6038%2C2267%2C0_0&invitationId=inv_6403b820-2acd-4db0-9a63-16de1d01e7c6)<br><br>

Enlace: [User Flow 3 en LucidChart](https://lucid.app/lucidchart/d12cb0f3-976b-46bf-ab0e-a545c1575e19/edit?view_items=R8dsqoYWsTCr&invitationId=inv_3ca4de93-b0e9-4de4-819a-3037cf6b4e95)<br><br>

## 4.5. Web Applications Prototyping.

A continuación, se presenta el prototipo que se realizó en base a los mockups que se desarrollaron y documentaron en puntos anteriores. El prototype nos permite evidenciar algunos flujos que se llevarán al desarrollo en código.

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Prototype/prototype-app-0.PNG?raw=true"  alt="prototype">
</div><br><br>

Enlace: [Prototype de la App Web en Figma](https://www.figma.com/proto/VpmoDnfHRERQvKTwxnOjLe/CambiaZo?type=design&node-id=662-6234&t=6tWRPswBDZfqgYDM-0&scaling=scale-down&page-id=0%3A1&starting-point-node-id=662%3A4809&show-proto-sidebar=1)<br><br>


Para complementar, se ha realizado un video donde se muestran los user flows del prototipo, detallando cada flujo de interacción y definiendo el tiempo en el cual se muestran para una comprensión efectiva. Este enfoque proporciona una visión dinámica de la experiencia del usuario, facilitando la identificación de mejoras y la validación de la funcionalidad del prototipo.<br><br>

Enlace: [Video Prototype de la App Web](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202214059_upc_edu_pe/EUUL7qHyT4ZEphT55Efo2EkBd8UOBk_GQsqR3o8HY9yMNg?e=3x2Yce&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)<br><br>


**User Goal 1:**  Como usuario, quiero ingresar a la aplicación web utilizando una cuenta.<br><br>

Tiempo: 0:15

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Prototype/prototype-app-1.PNG?raw=true" alt="prototype 1">
</div><br>


**User Goal 2:** Como usuario, quiero buscar objetos para intercambiar fácilmente y obtener información detallada sobre ellos.<br><br>

Tiempo: 2:48

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Prototype/prototype-app-2.PNG?raw=true" alt="prototype 2">
</div><br>


**User Goal 3:** Como usuario, quiero que otros usuarios vean los objetos que publiqué para intercambiar.<br><br>

Tiempo: 3:04

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Prototype/prototype-app-3.PNG?raw=true" alt="prototype 3">
</div><br><br>


**User Goal 4:** Como usuario, quiero solicitar un intercambio a cambio de uno de los objetos de mi publicación.<br><br>

Tiempo: 1:35

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Prototype/prototype-app-4.PNG?raw=true" alt="prototype 4">
</div><br><br>

**User Goal 5:** Como usuario, quiero ser notificado cuando reciba una solicitud de intercambio y tener la opción de aceptar o rechazarla.<br><br>

Tiempo: 0:50

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Prototype/prototype-app-5.PNG?raw=true" alt="prototype 5">
</div><br><br>


**User Goal 6:** Como usuario, quiero explorar y buscar ONGs y acceder a la información detallada sobre ellas.<br><br>

Tiempo: 1:39

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Prototype/prototype-app-6.PNG?raw=true" alt="prototype 6">
</div><br><br>



**User Goal 7:** Como usuario, quiero explorar y obtener información sobre los perfiles de otros usuarios.<br><br>

Tiempo: 2:53

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Prototype/prototype-app-7.PNG?raw=true" alt="prototype 7">
</div><br><br>



**User Goal 8:** Como usuario, quiero tener la opción de  pagar una membresía y disfrutar de los beneficios que ofrece.<br><br>

Tiempo: 3:08

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Prototype/prototype-app-8.PNG?raw=true" alt="prototype 8">
</div><br><br>


**User Goal 9:** Como usuario, quiero tener acceso claro y fácil a toda la información relevante de la aplicación.<br><br>

Tiempo: 3:48

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Prototype/prototype-app-9.PNG?raw=true" alt="prototype 9">
</div><br><br>


**User Goal 10:** Como usuario, quiero poder realizar modificaciones en mis publicaciones si considero que necesitan ajustes.<br><br>

Tiempo: 4:30

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Prototype/prototype-app-10.PNG?raw=true" alt="prototype 10">
</div><br><br>



**User Goal 11:** Como usuario, quiero realizar cambios en mi perfil y mantenerlo actualizado con la información más reciente.<br><br>

Tiempo: 4:20

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Prototype/prototype-app-11.PNG?raw=true" alt="prototype 11">
</div><br><br>



## 4.6. Domain-Driven Software Architecture

En esta sección emplearemos el modelo C4 para crear la estructura de software, considerando aspectos como el contexto, los recipientes, los elementos y la implementación. Este enfoque permite una comprensión sencilla de la arquitectura, tanto para los miembros del equipo como para las partes interesadas externas.

### 4.6.1. Software Architecture Context Diagram

Para lograr identificar y representar correctamente los usuarios y sistemas externos que se relacionan con nuestro sistema, hemos creado un diagrama de contexto, en el cual podemos ver que tenemos usuarios y administradores de la aplicación, y los sistemas externos son Gmail, la Reniec, un Servicio de Pagos, y las ONG’s.

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Software-Architecture/software-architecture-context-diagram.png?raw=true" width="600px" alt="diagram context">
</div><br><br>

Enlace: [Diagrama de Contexto en Structurizr](https://structurizr.com/share/82722/aaf6290c-e396-4761-8cd4-eb584715ccc8/diagrams#Contexto)<br><br>


### 4.6.2. Software Architecture Container Diagrams

En este diagrama de contenedores mostramos la arquitectura de CambiaZo, en la cual hemos identificado diferentes contenedores. Además se logra ver la interacción que tienen y cómo se conectan con los sistemas externos.

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Software-Architecture/software-architecture-container-diagram.png?raw=true" width="600px" alt="diagram container">
</div><br><br>

Enlace: [Diagrama de Contenedores en Structurizr](https://structurizr.com/share/82722/aaf6290c-e396-4761-8cd4-eb584715ccc8/diagrams#Contenedores)<br><br>


### 4.6.3. Software Architecture Components Diagrams

En estos diagramas de componentes mostramos la arquitectura de las principales funcionalidades de CambiaZo. Además se logra ver cómo funcionan por dentro y cómo se conectan con los sistemas externos.


**Componente Gestión de Usuarios**

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Software-Architecture/software-architecture-components-diagram-gestion.png?raw=true" width="600px" alt="diagram component 1">
</div><br><br>

Enlace: [Diagrama de Componentes 1 en Structurizr](https://structurizr.com/share/82722/aaf6290c-e396-4761-8cd4-eb584715ccc8/diagrams#Component-001)<br><br>

**Componente Intercambios/Trueques**

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Software-Architecture/software-architecture-components-diagram-trueque.png?raw=true" width="600px" alt="diagram component 2">
</div><br><br>

Enlace: [Diagrama de Componentes 2 en Structurizr](https://structurizr.com/share/82722/aaf6290c-e396-4761-8cd4-eb584715ccc8/diagrams#Component-002)<br><br>

**Componente Configuración y Ajustes**

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Software-Architecture/software-architecture-components-diagram-configuracion.png?raw=true" width="600px" alt="diagram component 3">
</div><br><br>

Enlace: [Diagrama de Componentes 3 en Structurizr](https://structurizr.com/share/82722/aaf6290c-e396-4761-8cd4-eb584715ccc8/diagrams#Component-003)<br><br>


**Componente Donaciones**
<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Software-Architecture/software-architecture-components-diagram-donaciones.png?raw=true" width="600px" alt="diagram component 4">
</div><br><br>

Enlace: [Diagrama de Componentes 4 en Structurizr](https://structurizr.com/share/82722/aaf6290c-e396-4761-8cd4-eb584715ccc8/diagrams#Component-004)<br><br>



## 4.7. Software Object-Oriented Design

En la sección de Software Object-Oriented Design se presentarán dos aspectos fundamentales: los diagramas de clase y el diccionario de clases.

### 4.7.1. Class Diagrams

Los diagramas de clase representan las entidades del sistema y sus relaciones de manera visual, facilitando la comprensión de la estructura y la interacción entre los componentes del software.

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Class%20Diagram/class-diagram.PNG?raw=true" width="800px" alt="class diagram">
</div><br><br>

Enlace: [Class Diagram en LucidChart](https://lucid.app/lucidchart/d12cb0f3-976b-46bf-ab0e-a545c1575e19/edit?viewport_loc=-2546%2C119%2C2587%2C1126%2C0_0&invitationId=inv_3ca4de93-b0e9-4de4-819a-3037cf6b4e95)<br><br>



### 4.7.2. Class Dictionary

El diccionario de clases detalla las características y funciones de cada entidad del sistema, proporcionando una referencia completa para entender la funcionalidad del software.

- **Usuario:** Representa a los usuarios de la aplicación, quienes pueden tener objetos, hacer donaciones, crear anuncios, etc.
- **Objeto:** Representa los objetos que los usuarios pueden subir, junto con su información asociada.
- **Donación:** Representa las donaciones realizadas por los usuarios a organizaciones.
- **Anuncio:** Representa los anuncios creados por los usuarios.
- **Suscripción:** Representa las subscripciones que los usuarios pueden tener en la aplicación.
- **Contacto:** Representa los mensajes de contacto enviados por los usuarios.
- **Adapter:** Representa al patrón de diseño estructural “adapter” para transformar la interfaz del usuario al utilizar CambiaZo.
- **InicioSesion:** Representa a un patrón de diseño “singleton” para que todos los usuarios tengan una sola instancia al querer iniciar sesión en CambiaZo.

## 4.8. Database Design

En la sección Database Design, se incluirá el diagrama de la base de datos para visualizar la estructura y las relaciones entre las entidades, facilitando la eficiente almacenamiento y recuperación de datos.

### 4.8.1. Database Diagram

Los diagramas de base de datos representan la estructura de la base de datos y las relaciones entre las entidades, lo que permite visualizar cómo se almacenan y se relacionan los datos dentro del sistema de manera eficiente.

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Database%20Diagram/database-diagram.PNG?raw=true" width="800px" alt="database diagram">
</div><br>

Enlace: [Database Diagram en Vertabelo](https://my.vertabelo.com/public-model-view/s7THFGyJJnZzsBc37Ubx6ig8WmX5rVJ6ZL16CxHnv7GEzTEZZFbid1yg52TaV2yg?x=3174&y=3601&zoom=0.5095)<br><br>

---

# Capítulo V: Product Implementation, Validation & Deployment


## 5.1 Software Configuration Management

A continuación, se presentará un repositorio central y organizado que servirá como guía para el desarrollo enfocado y consistente de nuestra solución.

### 5.1.1 Software Development Environment Configuration

En esta sección se incluye los links de las aplicaciónes, productos de software realizadas durante el ciclo del proyecto en los programas que se utilizaron. <br>

+ **Project Management**<br>
Esta área se centra en la planificación, organización, coordinación y control de los recursos y actividades necesarias para completar un proyecto de software con éxito. Incluye la gestión del alcance, el tiempo, el costo, la calidad, los riesgos, los recursos humanos y la comunicación para garantizar que el proyecto se entregue dentro del tiempo y el presupuesto establecidos, cumpliendo con los requisitos y objetivos definidos.

  +	<b>Pivotal Tracker:</b> Herramienta ágil de gestión de proyectos que permite a los equipos planificar, priorizar y realizar un seguimiento del trabajo de manera colaborativa. <br>https://www.pivotaltracker.com<br><br>

+ **Requirements Management**<br>
Se refiere al proceso de identificar, documentar, verificar y gestionar los requisitos del sistema y del software. Implica entender las necesidades de los usuarios y las partes interesadas, traduciéndolas en requisitos funcionales y no funcionales claros y específicos. El objetivo es garantizar que el software desarrollado satisfaga las necesidades y expectativas de los usuarios finales.

  + **Pivotal Tracker:**
Pivotal Tracker es una plataforma de gestión de proyectos centrada en User Stories, que se organizan en Epics y se clasifican por puntaje. Es utilizada para mantener a todos los miembros del equipo al tanto del progreso del proyecto, ofreciendo una vista en tiempo real compartida. Esto facilita la colaboración y permite a los miembros contribuir en diferentes aspectos del proyecto, manteniendo así un flujo de trabajo eficiente y bien coordinado.<br> https://www.pivotaltracker.com/n/projects/2699481<br><br>

+ **Product UX/UI Design**<br>
Este aspecto se enfoca en el diseño de la experiencia del usuario (UX) y la interfaz de usuario (UI) del producto de software. UX se centra en comprender y mejorar la experiencia general del usuario al interactuar con el software, mientras que UI se refiere al diseño visual y la usabilidad de la interfaz de usuario. El diseño UX/UI busca crear una experiencia intuitiva, atractiva y eficiente para los usuarios. En este caso realizar un modelo de sitio web para computadoras y celulares.

  + **Figma:**<br>Es una herramienta de prototipo web y editor de gráficos vectorial, que, a diferencia de las otras herramientas, se aloja en la web, permitiendo establecer los modelos para versión en Web Browser y Mobile Browser.
https://www.figma.com/design/ 

  + **UXPressia:**<br> Es una herramienta en línea para el mapeo de la trayectoria del cliente que crea mapas de impacto y personas. Sus herramientas nos permitieron establecer las bases del modelado de User Persona, Empathy Map y Journey Map.<br>https://uxpressia.com/ 

  + **MIRO:**<br>Es una pizarra digital colaborativa en línea, que puede ser usada para la investigación, la ideación, mapas mentales, as-is, to-be y una variedad de otras actividades colaborativas.<br>https://miro.com/app/dashboard/ 

  + **Lucid Chart:**<br> Es una herramienta de diagramación basada en la web, que permite a los usuarios colaborar y trabajar juntos en tiempo real, creando diseños UML, mapas mentales, prototipos de software y muchos otros tipos de diagrama.
https://lucid.app/documents#/dashboard 

  + **Vertabelo:**<br> Es una herramienta que permite a los usuarios crear diagramas de bases de datos de manera intuitiva y colaborativa, facilitando la visualización y comprensión de la estructura de la base de datos. 
https://my.vertabelo.com/drive

  + **Structurizr:**<br> Es una herramienta de diseño que soporta el modelo C4, para visualizar la arquitectura de software de nuestra solución. 
https://structurizr.com/ 

+ **Software Development**<br>
Es el proceso de crear, diseñar, programar, probar y mantener el software. Incluye la implementación de los requisitos definidos en el proceso de desarrollo de software, utilizando diferentes lenguajes de programación, herramientas y tecnologías. El objetivo es construir un producto de software funcional y de alta calidad que cumpla con los requisitos y expectativas del cliente.

  + **GitHub:**<br> Es un repositorio comunitario cuya función es almacenar los avances de un proyecto elaborado por un grupo de personas. <br>
https://github.com/TechZo-Organization  para open otro link


  + **Visual Studio Code:**<br> Es un editor potente que brinda extensiones que nos permiten personalizar y agregar funcionalidades para que la función del desarrollador sea más eficiente.<br>
https://code.visualstudio.com/ 

  + **HTML:**<br>  Es el lenguaje estándar para crear y diseñar sitios web. Utiliza etiquetas para estructurar el contenido, como texto, imágenes y enlaces. Junto con CSS y JavaScript, HTML forma la base de la web moderna. Este lenguaje será utilizado en el presente proyecto para implementar la documentación de la página web.<br>
https://www.jetbrains.com/help/webstorm/editing-html-files.html 

  + **CSS:**<br> Es un lenguaje de estilo utilizado para controlar el diseño y la presentación de páginas web. Permite establecer colores, fuentes, márgenes y otros aspectos visuales para mejorar la apariencia de un sitio web. Este lenguaje se utilizará para la implementación del diseño de nuestra plataforma web.<br>
https://www.jetbrains.com/help/webstorm/style-sheets.html#ws_css_completion 

  + **JavaScript:**<br> Es un lenguaje de programación de alto nivel que se utiliza principalmente para agregar interactividad y dinamismo a los sitios web. Permite realizar acciones como validar formularios, animar elementos y actualizar contenido sin recargar la página. Se utilizará para la elaboración de las dinámicas de la plataforma web.<br>
https://www.jetbrains.com/help/webstorm/javascript-specific-guidelines.html 


  + **TypeScript:**<br> Es un superset de JavaScript que agrega tipado estático y otras características avanzadas al lenguaje. Permite escribir código más seguro y mantenible, especialmente en proyectos grandes y complejos.<br>
https://www.typescriptlang.org/docs/handbook/typescript-from-scratch.html

  + **Java:**<br>  Es un lenguaje de programación popular y versátil que se utiliza en una variedad de aplicaciones, desde desarrollo web hasta aplicaciones empresariales y móviles. Java se destaca por su portabilidad y su robusto sistema de tipos. Se utilizará para la elaboración de las dinámicas de la plataforma web.<br>
https://www.java.com/es/download/help/whatis_java.html

  + **Angular Material:**<br>Es una biblioteca de componentes de interfaz de usuario desarrollada para Angular que sigue las directrices de diseño de Material Design de Google. Proporciona una amplia gama de componentes listos para usar para crear aplicaciones web con una apariencia y sensación consistentes y atractivas. Integrado con Angular, facilita el desarrollo de aplicaciones web para los desarrolladores.<br>https://material.angular.io/


+ **Software Testing**<br>
Se refiere a la actividad de verificar y validar el software para garantizar su calidad y funcionamiento correcto. Involucra la ejecución de pruebas funcionales y no funcionales para identificar errores, defectos o problemas en el software antes de su lanzamiento. El objetivo es asegurar que el software sea confiable, robusto y cumpla con los requisitos y expectativas del usuario final.

  + **Lenguaje Gherkin:**<br>Es un lenguaje de dominio específico (DSL) utilizado en el desarrollo de software para escribir pruebas de aceptación en un formato legible por humanos. Utiliza palabras clave como Given, When y Then para describir el estado inicial, la acción y el resultado esperado de un escenario de prueba, lo que facilita la colaboración entre equipos al definir requisitos y pruebas.<br>https://cucumber.io/

+ **Software Deployment**<br>
Es el proceso de implementar y poner en funcionamiento el software en un entorno de producción o en los dispositivos de los usuarios finales. Incluye actividades como la instalación, configuración, migración de datos y puesta en marcha del software. El objetivo es garantizar una implementación exitosa y sin problemas del software en el entorno de producción.

  + **Github Pages:**<br> Servicio de Github que nos permitió alojar nuestra Landing page y nos permitirá alojar nuestro web applications.<br>
https://pages.github.com/ <br>


+	**Software Documentation**<br>Se refiere a la creación y mantenimiento de documentos que describen el software, incluyendo su arquitectura, diseño, funcionamiento, instalación, configuración, uso y mantenimiento. La documentación proporciona información útil y detallada sobre el software para desarrolladores, usuarios finales, administradores de sistemas y otras partes interesadas. 

    + **Markdown:**<br>Es un lenguaje de marcado ligero que permite escribir texto con un formato fácil de leer y escribir, que luego puede ser convertido a HTML u otros formatos de presentación. Es ampliamente utilizado para documentar proyectos de software debido a su simplicidad y versatilidad. Markdown permite agregar formato básico como encabezados, listas, enlaces e imágenes utilizando una sintaxis sencilla y fácil de recordar.<br>https://www.markdownguide.org/getting-started/<br><br>

### 5.1.2 Source Code Management

Para administrar el progreso del código de manera efectiva, hemos decidido adoptar la metodología Git Flow. Esta estrategia se enfoca en el uso de ramas para facilitar la gestión de archivos durante el proceso de programación. En resumen, Git Flow nos permite mantener una rama principal ('main') que contiene una versión estable del proyecto en un punto determinado. Al mismo tiempo, utilizamos otra rama de desarrollo para incorporar nuevas características al código base sin afectar la versión estable actual. Esto nos permite avanzar en el desarrollo de nuestra página de destino mientras realizamos pruebas relacionadas con las nuevas modificaciones introducidas en la rama de desarrollo.

Además, hemos optado por utilizar GitHub debido a su función específica llamada GitHub Pages. Esta función permite la visualización eficiente del proyecto mediante la ejecución de archivos '.html' y la generación de un enlace web.

En cuanto a nuestros archivos feature, creamos una nueva rama “feature/sprint-1” para cada nueva funcionalidad que deseamos agregar. Este enfoque modular y organizado asegura un desarrollo progresivo, ya que cada rama “feature/sprint-1” actúa como un espacio aislado para desarrollar y probar una característica específica antes de fusionarla con la rama de desarrollo.<br><br>

Enlace de la Landing Page en GitHub Pages: https://techzoorganization-opensource.github.io/landing-page-OpenSource/ <br><br> 

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Code-Management/landing-desplegada.jpeg?raw=true" alt="Landing Page">
</div><br>

Repositorio GitHub de la Landing Page: https://github.com/TechZoOrganization-OpenSource/landing-page-OpenSource <br><br> 

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Code-Management/landing-repositorio.jpeg?raw=true"  alt="Repositorio landing page">
</div><br>

Repositorio GitHub de los archivos feature: https://github.com/TechZoOrganization-OpenSource/Acceptance-Test-OpenSource <br><br> 

<div align="center">
    <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Code-Management/acceptance-repositorio.jpeg?raw=true"  alt="repositorio feature">
</div><br><br>


### 5.1.3 Source Code Style Guide & Conventions

En esta sección del proyecto, nos enfocaremos en establecer un conjunto coherente de referencias y convenciones para el estilo de código y las convenciones de programación que usaremos para la creación de nuestra aplicación web CambiaZo. Estas prácticas son cruciales para el desarrollo de la aplicación puesto a que garantizan la coherencia, la legibilidad y la calidad estructural del código. En consecuencia, nos facilitarán su mantenimiento y escalabilidad a lo largo del ciclo de vida del proyecto. 

En este proyecto, se emplearán HTML, CSS, TypeScript y Java para desarrollar la plataforma web, mientras que Gherkin se utilizará en el proceso de prueba del programa. A continuación, se presentarán y explicarán las reglas y recomendaciones generales que se considerarán al utilizar estos lenguajes.



**Nomenclatura en Inglés y uso de Minúsculas**

Los términos utilizados para nombrar variables, objetos, elementos y funciones estarán en inglés y relacionados con la función o descripción de lo que representan. Se evitará el uso de mayúsculas, ya que la combinación de mayúsculas y minúsculas puede afectar la legibilidad del código, según lo señalado por Google. Se dará preferencia al uso exclusivo de minúsculas para mejorar la legibilidad del código.

Ejemplo: 
```
.rg {}  (Mala práctica, el nombre de esta clase no nos dice nada)

.register {} (Buena práctica, el nombre de esta clase nos dice que representa al registro)
```

**Identación o Sangría**

La indentación o sangría en el código es esencial para mejorar la legibilidad y comprensión del mismo. Proporciona una estructura visual clara que refleja la lógica del código, facilitando su mantenimiento y reduciendo la probabilidad de errores.

Según Google para facilitar la lectura, se debe agregar dos espacios de sangría y no utilizar la tecla de tabulación, por lo que seguiremos esta práctica para nuestro proyecto.


Ejemplos:

**En HTML:**
```
<ul>
  <li>London</li>
  <li>Paris</li>
  <li>Tokyo</li>
</ul>
```

**En CSS:**
```
body {
  background: #fff;
  color: #404;
}
```

**En TypeScript:**

```
function square(num:number):number {
  return num*num;
}
```

A continuación se mostrarán las reglas específicas para cada lenguaje que utilizaremos:

**HTML**

Para nuestro proyecto utilizaremos HTML5, el estándar más reciente de HTML que ofrece una amplia gama de nuevas características y mejoras. A continuación se mostrarán las características y pautas que seguiremos para el desarrollo:

+ **Document Type**

En nuestro proyecto, nos adherimos a las mejores prácticas recomendadas por Google al utilizar HTML. Por lo tanto, emplearemos la declaración de tipo de documento (DOCTYPE) específica de HTML5, que se define como "```<!DOCTYPE html>```". 

+ **Semantics**

Utilizaremos los elementos HTML para lo que han sido diseñados. Por ejemplo, emplearemos elementos de encabezado para encabezados, elementos de párrafo (“p”) para párrafos, elementos de anchor (“a”) para enlaces, y así sucesivamente, tal y como nos indica Google.

Ejemplo:
```
<!-- Not recommended -->
<div onclick="goToComments();">All comments</div>

<!-- Recommended -->
<a href="comments/">All comments</a>
```
+ **Blank Lines**

Para mejorar la legibilidad del código, W3Schools recomienda agregar líneas en blanco para separar bloques de código grandes o lógicos. Esta práctica ayuda a dividir visualmente el código en secciones más manejables y facilita la identificación de la estructura y la lógica del programa.
```
<body>

<h1>Famous Cities</h1>

<h2>Tokyo</h2>
<p>Tokyo is the capital of Japan, the center of the Greater Tokyo Area, and the most populous metropolitan area in the world.</p>

<h2>London</h2>
<p>London is the capital city of England. It is the most populous city in the United Kingdom.</p>

<h2>Paris</h2>
<p>Paris is the capital of France. The Paris area is one of the largest population centers in Europe.</p>

</body>
```
+ **Multimedia Fallback**

Es fundamental proporcionar contenido alternativo para elementos multimedia, como imágenes, videos y objetos animados a través de canvas. Esto implica utilizar texto alternativo (“alt”) significativo para las imágenes, videos y audios. Según Google, la inclusión de contenido alternativo es crucial por razones de accesibilidad y además es importante en caso de que estos objetos multimedia fallen al cargar. 

Ejemplo:
```
<!-- Not recommended -->
<img src="userpersona.png">

<!-- Recommended -->
<img src="userpersona.png" alt="User persona screenshot.">
```
+ **HTML Quotation Marks**

Según las recomendaciones de Google, al citar los valores de los atributos en HTML, se deben utilizar comillas dobles ("") en lugar de comillas simples (''). Esta práctica es preferible ya que las comillas dobles son el estándar recomendado en la especificación de HTML.

Ejemplo:
``` 
<!-- Not recommended →
<a class='facebook-button'>Sign in</a>

<!-- Recommended →
<a class="facebook-button">Sign in</a> 
```

<br><br>

**CSS**

Para nuestro proyecto, optaremos por CSS3, la versión más reciente de CSS que ofrece una amplia variedad de nuevas características y mejoras en comparación con las versiones anteriores. A continuación, se presentarán las características y directrices que seguiremos para el desarrollo:

+ **Property Name Stops**

Para mantener la consistencia en el código CSS, se recomienda utilizar un espacio después de los dos puntos que siguen al nombre de la propiedad. Además, es importante utilizar un solo espacio entre la propiedad y el valor asignado a esa propiedad, tal y como nos indica  Google.

Ejemplo:


```
/* Not recommended */
h2 {
  font-weight:bold;
}

/* Recommended */
h2 {
  font-weight: bold;
}
```

+ **Declaration Stops**

Según las recomendaciones de Google, se debe utilizar un punto y coma (;) al final de cada declaración en CSS. Esto ayuda a mantener la consistencia y la extensibilidad del código.

```
/* Not recommended */
.box {
  display: block;
  width: 100px
}


/* Recommended */
.box {
  display: block;
  width: 100px;
}
```

+ **Shorthand Properties**

Se debe utilizar propiedades abreviadas (shorthand properties) siempre que sea posible en CSS. Google afirma que estas propiedades abreviadas, como font, ofrecen una forma más concisa de definir múltiples valores en una sola declaración, incluso en casos donde solo se establece un valor de manera explícita.

Ejemplo: 

```
/* Not recommended */
border-top-style: none;
padding-bottom: 2em;
padding-left: 1em;
padding-right: 1em;
padding-top: 0;



/* Recommended */
border-top: 0;
padding: 0 1em 2em;
```


+ **CSS Quotation Marks**

Google nos dice la recomendación de que se deben utilizar comillas simples ('') en lugar de comillas dobles ("") para selectores de atributos y valores de propiedades en CSS. No se deben utilizar comillas en valores de URI (url()).

Ejemplo: 

```
/* Not recommended */
@import url("https://www.google.com/css/page.css");

html {
  font-family: "open sans", sans-serif;
}


/* Recommended */
@import url(https://www.google.com/css/page.css);

html {
  font-family: 'open sans', sans-serif;
}
```

+ **Declaration Block Separation**

Se debe utilizar un espacio entre el último selector y el bloque de declaración en CSS. Google indica que siempre se debe utilizar un solo espacio entre el último selector y la llave de apertura que inicia el bloque de declaración. La llave de apertura debe estar en la misma línea que el último selector en una regla dada.

Ejemplo:

```
/* Not recommended: missing space */
.nav{
  margin-bottom: 1em;
}

/* Not recommended: unnecessary line break */
.nav
{
  margin-bottom: 1em;
}


/* Recommended */
.nav {
  margin-bottom: 1em;
}
```

<br><br>

**TYPESCRIPT**

Para nuestro proyecto, hemos elegido Typescript, un superset de JavaScript que añade tipado estático opcional al lenguaje. Typescript proporciona una amplia gama de nuevas características y mejoras con respecto a JavaScript, lo que lo convierte en una opción popular para el desarrollo de aplicaciones web y de Node.js. A continuación, se presentarán las características y directrices que seguiremos para el desarrollo utilizando este lenguaje.

+ **Naming Conventionns**

Esha Garg (2020) señala la importancia de mantener un orden adecuado al nombrar variables, constantes, métodos y clases:

Ejemplo: 

```
Nombres de variables: camelCase
firstNumber = 12

Constantes: UPPER_CASE con ‘_’ entre las palabras

const FIRST_NUMBER = 18

Nombres de métodos: camelCase

sumOfTwoNumbers()

Nombres de clases: PascalCase

export class EmployeeDetails {}

Nombres de archivos: lower-case (Separados por ‘-’ si el nombre es de 2 a más palabras)

employee-details
```
+ **Data type of variables and methods**

Esha Garg (2020) sugiere incluir los tipos de datos tanto para los parámetros de los métodos como para los valores de retorno. Al definir un método, es importante especificar el tipo de datos esperado para cada parámetro que recibe y el tipo de datos que el método devuelve, lo que proporciona claridad sobre el tipo de información que se puede esperar como resultado de su ejecución.

Ejemplo:

```
En variables:
firstNumer: number

En métodos:
function sum(firstNumber: number, secondNumber:number):number{
  return firstNumber + secondNumber;
}
```

+ **Spaces Around Operators**

Según W3Schools, se recomienda siempre colocar espacios alrededor de los operadores (=, +, -, *, /) y después de las comas al escribir código TypeScript. Esto ayuda a mejorar la legibilidad y la claridad del código, facilitando su comprensión y mantenimiento.

Ejemplo: 

```
let z:number = x + y;
const myArray:string[] = ["Toyota", "Kia", "Hyundai"];
```

  <br><br>
  
**GHERKIN**<br>
Gherkin es un Lenguaje Específico de Dominio (DSL) diseñado para abordar problemas específicos al generar casos de validación de características en diversos escenarios. Este lenguaje se utiliza para describir el comportamiento deseado de un software de manera comprensible para personas no técnicas. Gherkin presenta varios elementos, entre los que se destacan Feature, Scenario, Example, Given, When y Then, los cuales son ampliamente utilizados para definir las características y los pasos de las pruebas de comportamiento.

Las pautas a tener en cuenta al utilizar Gherkin en nuestro código incluyen:

  

* **Discernible Given-When-Then Blocks**
  
Según la sugerencia de Keiblinger, para facilitar la comprensión y la organización de los escenarios en Gherkin, se recomienda indentar los pasos que comienzan con "And" después de cada Given, When o Then. Esto permite distinguir claramente dónde termina un bloque y comienza otro, incluso en escenarios con múltiples pasos.

Ejemplo de Sophie Keiblinger :

```
Scenario: Discernible Given-When-Then Blocks

In order to quickly spot where one block ends and another one begins, you can indent the steps starting with “And”

Given I need to prepare some data for my  scenario

And this is more complex so I need a second step

And this is more complex so I need a third step

When I trigger some action

Then I can see the expected outcome

And this outcome also has a second step

And this outcome also has a third step
```

* **Steps with Tables**
  
Keiblinger nos sugiere utilizar un colon (:) al final de los pasos que requieren más entrada de una tabla. Esto ayuda a hacer inmediatamente reconocible que se espera una tabla como parte de la entrada del paso.

Ejemplo de Sophie Keiblinger:

```
Given I need to prepare the following data for my scenario:

|  column 1  | column 2 |
| necessary |     data     |
```

* **Reducing Noise**

Keiblinger sugiere utilizar valores por defecto para campos que el sistema requiere pero que no son pertinentes para el escenario en cuestión. Por ejemplo, al probar la validación de una fecha de nacimiento, no es necesario especificar el nombre de la persona, título académico o número de seguro social. Esta  inclusión no afecta al resultado del escenario. Esta práctica ayuda a simplificar los escenarios y a enfocarse en las características específicas que se están probando.

Ejemplo:

```
When el visitante se acerque a la sección ‘Comunícate con nosotros’
```

* **Newlines between scenarios and separator comments**

Keiblinger nos dice que para mantener la claridad en los archivos de escenarios de Gherkin, especialmente cuando estos son extensos o contienen múltiples escenarios, se recomienda agregar dos líneas en blanco entre cada escenario. Esto ayuda a distinguir claramente dónde termina un escenario y comienza otro. Además, es común añadir un comentario separador para brindar una guía visual adicional y facilitar la navegación en el archivo.

Ejemplo:

```
#-----------------------------------------------------------------------------------
Scenario: Acceso a la historia de TechZo
        Given que soy un visitante de la landing page
        When navegue por la página de inicio
        And encuentre la sección titulada "¿Quiénes Somos?"
        Then podré obtener información detallada sobre la historia de la startup.

#-----------------------------------------------------------------------------------

    Scenario: Acceso a las redes sociales de TechZo
        Given que el visitante se encuentra en el landing page
        When el visitante de click en la etiqueta “Contáctanos”
        And encuentre los botones con los logos de las redes sociales en las que puede encontrar la página de TechZo
        And de click encima del botón con el logo de la red social que desee ver
        Then el usuario será redireccionado a la red social que seleccionó previamente.

```
 
<br><br>

**Java**

Java es un lenguaje de programación versátil y potente, ampliamente utilizado en una variedad de aplicaciones, desde desarrollo de aplicaciones empresariales hasta aplicaciones móviles y de escritorio. Ofrece una amplia gama de características y funcionalidades, como la portabilidad, la orientación a objetos y la robustez, lo que lo convierte en una opción popular para desarrolladores de todo el mundo. Con Java, los desarrolladores pueden crear aplicaciones escalables y confiables que se ejecutan en una variedad de plataformas y dispositivos. A continuación, se presentarán las características y directrices que seguiremos para el desarrollo utilizando este lenguaje

* **Name Conventions**

Para identificar una variable, método, función o clase, es importante utilizar nombres significativos que mejoren la legibilidad del código. A continuación, se detallan las convenciones para diferentes tipos de identificadores según GVSU(2024):

Nombre de una clase: Debe comenzar con una letra mayúscula.

Ejemplo:

```
public class Persona
{
}
```

Nombre de función: Debe comenzar con una letra minúscula.

Ejemplo:

```
private int sum(int num1, int num2)
{
}
```

Nombre de variable: Debe comenzar con una letra minúscula.

Ejemplo:

```
int area = 100;
```

Nombre de final o constante: Debe estar en letras mayúsculas.

Ejemplo:

```
public final int MAX_HEIGHT = 100;
```

* **Uso de paréntesis y llaves en las expresiones**
  
CodeAcademy sugiere utilizar paréntesis y llaves para hacer las cláusulas en una expresión más evidentes. Esta práctica mejora la claridad y la legibilidad del código, especialmente en expresiones complejas como la que se mostrará a continuacion:

Ejemplo:

```
if ((num1 > num2) && (num1 > num3))
{
   // Contenido
}
```

* **Identación y espaciado**

Codecademy recomienda seguir ciertos estándares para mejorar la legibilidad del código en Java. Esto incluye utilizar sangrías de dos espacios y asegurarse de que haya una sangría cada vez que se abre un nuevo bloque. Además, sugiere agregar espacios antes y después de las palabras clave y operadores para mejorar la claridad del código

Ejemplo:

```
x = 3;
y = 4;
```

* **Comment Style**

Google nos recomienda utilizar comentarios con (//) y (/* */). Es preferible evitar comentarios en varias líneas  para explicaciones más largas, ya que los comentarios no están localizados y pueden dificultar la lectura del código. En su lugar, se sugiere incluir explicaciones más extensas en un artículo complementario o en documentación externa.

```
//Funcion que realiza una suma de dos números
private int sum(int num1, int num2)
{
}
```

### 5.1.4 Software Deployment Configuration

En esta sección mostraremos los pasos que hemos realizado para poder desplegar cada uno de nuestros proyectos.

**Landing Page**

Para desplegar nuestro landing page hemos optado por usar Github Pages, el cual brinda la posibilidad de alojar sitios web estáticos sin costo alguno.

**1.  Ingresamos al repositorio de nuestra landing page**

<div align="center">
  <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Deployment-Landing/paso1.jpeg?raw=true" alt="landing repo">
</div>

<br>

**2.  Nos dirigimos al apartado de settings**

<div align="center">
  <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Deployment-Landing/paso2.jpeg?raw=true" alt="landing repo">
</div>

<br>

**3.  Vamos a la sección de Github Pages**

<div align="center">
  <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Deployment-Landing/paso3.jpeg?raw=true" alt="landing repo">
</div>

<br>

**4.  Debemos seleccionar la rama de github-pages en el apartado de source.**

<div align="center">
  <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Deployment-Landing/paso4.jpeg?raw=true" alt="landing repo">
</div>

<br>

**5.  Finalmente estaría todo listo.**

<div align="center">
  <img src="https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/Deployment-Landing/paso5.jpeg?raw=true" alt="landing repo">
</div><br>

Esta sería la forma de cómo desplegamos automáticamente la landing page en GitHub Pages. Con cada commit a la rama develop, se configuró GitHub Pages para que se despliegue desde la rama “main”. Luego, se creó un flujo de trabajo de GitHub Actions que se active con cada commit a develop, compile los archivos estáticos de la landing page y los suba a la misma rama develop, lo que provocará que GitHub Pages detecte los cambios y actualice la landing page desplegada con los nuevos archivos subidos cuando todo el equipo apruebe los cambios.<br><br>




</div>
