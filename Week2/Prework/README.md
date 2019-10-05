# Week 2: Prework

### Preguntas de Prework

1. Entra a https://www.hackingwithswift.com/sixty y en la página [online.swiftplayground.run](http://online.swiftplayground.run) haz las siguientes secciones:

2. 1. Complex Types
   2. Operators and conditions
   3. Looping
   4. Functions
   5. Structs

3. Entra a https://developer.apple.com/design/human-interface-guidelines/ios/overview/themes/ y contesta lo siguiente:

4. 1. Enlista y describe los temas principales de diseño

- **Claridad**: Texto Legible, iconos precisos y lúcidos, los elementos transmiten interactividad.

- **Deferencia** (respeto): Contenido llena la pantalla y la interfaz no compite con el.

- **Profundidad**: Distintas capas visuales transmiten jerarquía y facilitan la comprensión.

2.  Enlista y describe los principios de diseño

- **Integridad Estética:** Apariencia & Comportamiento integrados a la funcionalidad.

- **Consistencia:** Implementa estándares y paradigmas de iconos, textos y terminología uniforme.

- **Manipulación directa:** Facilita la comprensión. Los usuarios experimentan una manipulación directa cuando giran el dispositivo o usan gestos para afectar el contenido en pantalla. A través de la manipulación directa, pueden ver los resultados inmediatos y visibles de sus acciones.

- **Retroalimentación/Feedback:** Se muestra una respuesta perceptible a las acciones de los usuarios. Los elementos interactivos se resaltan, los indicadores de progreso muestran el estado, la animación y el sonido ayudan a aclarar los resultados de las acciones.

- **Metáforas:** Las personas aprenden más rápidamente cuando los objetos y acciones virtuales de una aplicación son metáforas de experiencias familiares, funcionan bien (Por ejemplo Mover las vista, Arrastrar o deslizan el contenido, interruptores, Incluso hojear páginas de libros y revistas.)

- **Control de usuario:** En iOS, el usuario mantiene el control de las aplicaciones, mediante elementos interactivos, familiares y predecibles, confirmando acciones destructivas y facilitando la cancelación de operaciones, incluso si ya estan en marcha.

3.  Dentro de la sección de **User Interaction**, describe lo siguiente:

4.  **1. Authentication**
    Solicite a los usuarios que se autentiquen solo a cambio de valor, como personalizar la experiencia, acceder a funciones adicionales, comprar contenido o sincronizar datos.

    En caso de que sí sea necesario, se debe optar por alguna de las siguientes opciones:

    - [Iniciar sesión con Apple](https://developer.apple.com/design/human-interface-guidelines/sign-in-with-apple/overview/).
    - Autollenado de contraseña.
    - Retrasar el inicio de sesión el mayor tiempo posible.
    - Explicar los beneficios de la autenticación y cómo suscribirse al servicio.
    - Minimizar la entrada de datos mostrando los teclados apropiados.
    - Siempre que sea posible (usuario ha habilitado la autenticación biométrica) hacer uso de **Face ID y Touch ID**, teniendo en cuenta que se debe tener otro metodo de autenticación alterno (usuario ha deshabilitado la autenticación biométrica)

    **IMPORTANTE:** Nunca usar el término **passcode / código de acceso**, Ya que él código de acceso se usa para desbloquear el dispositivo iOS del usuario y autenticar con Apple Pay cuando la autenticación biométrica está desactivada.

    **2. Data Entry**
    Para la recoleción de datos debemos cuidar que el proceso no sea tedioso.
    Podemos lograrlo si contemplamos lo siguiente:

    - Presentar opciones cuando sea posible - Obtener la información del sistema siempre que sea posible - Proporcionar valores razonables por defecto - Habilitar el avance solo después de recopilar los valores requeridos - Validar dinámicamente los valores de campo - Requerir valores de campo solo cuando sea necesario. - Facilitar la navegación a través de listas de valores - Muestrar una pista en un campo de texto para ayudar a comunicar el propósito.

    **3. Gestures**

    Como regla general, debemos usar gestos estándar, a menos que nuestra aplicación sea un juego no tendríamos que reinventar el uso de los gestos que ya son un "estandar"

    | GESTO          | DESCRIPCION                                                                                                                                                                                                                                                                                |
    | -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
    | Tap            | Activa un control o selecciona un elemento                                                                                                                                                                                                                                                 |
    | Drag           | Mueve un elemento de lado a lado o arrastra un elemento por la pantalla                                                                                                                                                                                                                    |
    | Flick          | Se desplaza o se desplaza rápidamente                                                                                                                                                                                                                                                      |
    | Swipe          | Cuando se realiza con un dedo, vuelve a la pantalla anterior, revela la vista oculta en un controlador de vista dividida, revela el botón Eliminar en una fila de vista de tabla o revela acciones en un vistazo. Cuando se realiza con cuatro dedos en un iPad, cambia entre aplicaciones |
    | Double tap     | Acerca y centra el contenido o una imagen, o aleja el zoom si ya lo hizo                                                                                                                                                                                                                   |
    | Pinch          | Se acerca cuando se pellizca hacia afuera, se aleja cuando se pellizca hacia adentro                                                                                                                                                                                                       |
    | Touch and hold | Cuando se realiza en texto editable o seleccionable, muestra una vista ampliada para el posicionamiento del cursor. Cuando se realiza en ciertas vistas, como una vista de colección, ingresa a un modo que permite reorganizar los elementos                                              |
    | Shake          | Inicia deshacer o rehacer                                                                                                                                                                                                                                                                  |
    | Rotate         | Rota una imagen o vista                                                                                                                                                                                                                                                                    |

    ​
    _No interferir con los gestos del borde de la pantalla en todo el sistema._
    ​

5.  Dentro de la sección de **Visual Design**, describe lo siguiente:

6.  **1. Adaptability and Layout**

    - En iOS, los elementos y diseños de la interfaz se pueden configurar para cambiar automáticamente la forma y el tamaño en diferentes dispositivos, durante la multitarea en iPad, en vista dividida, cuando se gira la pantalla y más. Es esencial que diseñe una interfaz adaptable que brinde una gran experiencia en cualquier entorno

    **2. Branding**

    - Las excelentes aplicaciones expresan una identidad de marca única a través de fuentes inteligentes, color y decisiones de imagen.

    **3. Color**

    -El color es una excelente manera de impartir vitalidad, proporcionar continuidad visual, comunicar información de estado, dar retroalimentación en respuesta a las acciones del usuario y ayudar a las personas a visualizar datos.

7.  Dentro de la sección de **Controls**, describe lo siguiente:

8.  1. Buttons
    2. Labels
    3. Color

9.  Enlista tus 10 apps favoritas

10. Enlista y describe los cuatro pilares de la programación orientada a objetos

11. Dentro del paradigma de programación orientada a objetos:

12. 1.  ¿Qué es un objeto?
    2.  ¿Qué es una clase?
    3.  ¿Qué es un método?
    4.  ¿Qué es una propiedad?

13. Investiga y describe la arquitectura de diseño MVC

14. ¿Qué es un ViewController?

15. ¿Qué es un Storyboard?

16. ¿Qué es un IBAction?

17. ¿Qué es un IBOutlet?

18. ¿Qué es la notación CamelCase y cuáles son sus tipos? ¿Conoces otro tipo de notación?

19. ¿Qué es un IDE y cuáles son sus elementos principales?
