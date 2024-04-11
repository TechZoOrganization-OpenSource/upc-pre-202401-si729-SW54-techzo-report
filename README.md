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

[![User Persona 1](https://github.com/TechZoOrganization-OpenSource/upc-pre-202401-si729-SW54-techzo-report/blob/main/Resources/NeedFinding/user-persona-1.PNG?raw=true)](https://uxpressia.com/w/ODLU6/p/WUMVh)>
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





## 3.2. User Stories.
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
|**US-27**|Acceder a un formulario para llenar mis datos de contacto y recibir noticias relacionadas con CambiaZo.|**Como** usuario visitante, **quiero** tener la opción de llenar un formulario con mi información de contacto, a través de la landing page, **para** recibir noticias y actualizaciones relevantes de CambiaZo.|<p>**Criterios de Aceptación:**</p><p>**Escenario 1: Información en el formulario**</p><p>**Dado** que soy un usuario interesado en CambiaZo que desea llenar el formulario de contacto</p><p>**Cuando** navegue por la Landing page</p><p>**Entonces** encontraré una sección que contendrá un formulario</p><p>**Y** en esa sección, debo colocar mi nombre, apellido y correo electrónico de contacto.</p><p></p><p>**Escenario 2: Envío de formulario con datos completos**</p><p>**Dado que** me encuentro en la sección del formulario de la Landing page</p><p>**Cuando**  termine de completar mi información de contacto</p><p>**Entonces** debo darle click al botón de “ENVIAR”</p><p>**Y** si he llenado todos los campos correspondientes, me saldrá un mensaje de registro exitoso.</p><p></p><p>**Escenario 3: Envío de formulario con datos incompletos**</p><p>**Dado que** me encuentro en la sección del formulario de la Landing page</p><p>**Cuando**  desee enviar el formulario con casillas en blanco</p><p>**Entonces** me saldrá un mensaje indicando que hay casillas que faltan completar.</p>|**EP02**|
|**US-28**|Acceder a la página principal de CambiaZo|<p>Como usuario visitante, quiero encontrar botones o enlaces claramente visibles que me dirijan a la página web principal de Cambiazo, para poder realizar acciones como registrarme, intercambiar o donar artículos una vez que haya obtenido la información necesaria en la landing page.</p><p></p>|<p>**Escenario 1: Identificación de botones o enlaces**</p><p>Dado que el usuario está en la landing page de Cambiazo,<br><br>Cuando busque acceder a la página principal de la plataforma,<br><br>Entonces encontrará botones o enlaces fácilmente identificables que lo dirijan a la página principal.</p><p>**Escenario 2: Redirección rápida y sin problemas**</p><p>Dado que el usuario se dirige a un botón o enlace de acceso a la página principal,<br><br>Cuando el usuario le de clic al botón,<br><br>Entonces el usuario será redirigido de manera rápida <br><br>Y sin problemas a la página principal de Cambiazo.</p><p></p>|**EP06**|
|**US-29**|Ver los planes y precios|Como usuario visitante, quiero tener acceso a una sección que detalle los planes ofrecidos por la plataforma, para poder evaluar las opciones disponibles antes de acceder a la página web principal.|<p>**Escenario 1: Acceso a la sección de planes y servicios:**</p><p>Dado que el usuario visita la landing page de Cambiazo,</p><p>Cuando busque información sobre los planes y servicios ofrecidos por la plataforma,</p><p>Entonces encontrará una sección dedicada que detalle estos aspectos.</p><p>**Escenario 2: Comparación de planes:**</p><p>Dado que el usuario revisa la información sobre los planes ofrecidos,</p><p>Cuando busque tomar una decisión informada,</p><p>Entonces encontrará que puede comparar fácilmente los diferentes planes para evaluar cuál se ajusta mejor a sus necesidades.</p>|**EP06**|
|**US-30**|Navegación en la Landing Page|**Como** usuario visitante, **quiero** contar con un menú de navegación visible y funcional **para** que me permita desplazarme fácilmente por las diferentes secciones del sitio web.|<p>**Escenario 1: Acceder a la información acerca de la startup**</p><p>Dado que el usuario se encuentra en la Landing Page</p><p>Cuando quiera acceder a la información acerca del equipo</p><p>Entonces podré darle click a la etiqueta “¿Quiénes somos?” de la barra navegadora</p><p>Y me redireccionará rápidamente a la parte de la Landing Page en la que se encuentra la información correspondiente.</p><p></p><p>**Escenario 2: Ver las ONG’s afiliadas a CambiaZo**</p><p>Dado que el usuario se encuentra en la Landing Page</p><p>Cuando quiera ver qué ONG’s están afiliadas con CambiaZo</p><p>Entonces podré darle click a la etiqueta “ONG’s” de la barra navegadora</p><p>Y me redireccionará rápidamente a la parte de la Landing Page en la que se encuentra la información correspondiente.</p><p></p><p>**Escenario 3: Buscar la sección de Contacto**</p><p>Dado que el usuario se encuentra en la Landing Page</p><p>Cuando quiera acceder a la sección para contactarme con la startup</p><p>Entonces le daré click a la etiqueta “Contáctanos” de la barra navegadora</p><p>Y me redireccionará rápidamente a la parte de la Landing Page en la que se encuentra el formulario para recibir notificaciones de CambiaZo y el pié de página en el cuál se encuentran los datos de contacto.</p><p></p><p>**Escenario 4: Llegar al inicio de la Landing Page rápidamente**</p><p>Dado que el usuario se encuentra en la Landing Page</p><p>Cuando quiera acceder rápidamente al inicio de esta</p><p>Entonces podré darle click a la etiqueta “Inicio” de la barra navegadora</p><p>Y me redireccionará inmediatamente a la parte superior de la Landing Page.</p>|**EP06**|






















</div>
