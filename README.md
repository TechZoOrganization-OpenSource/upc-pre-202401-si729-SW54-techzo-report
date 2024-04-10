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










</div>
