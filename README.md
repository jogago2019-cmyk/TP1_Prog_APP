# TRABAJO PRÁCTICO Nº 1

## Fundamentos y Ecosistemas del Desarrollo Móvil

### Realizar el siguiente trabajo práctico en el repositorio de github asignado para la actividad. Se deberán contestar las preguntas y subirlas como README.md

1 - ¿Cuáles son los principales sistemas operativos para dispositivos móviles en la actualidad?

2 - ¿Cuáles son las principales diferencias técnicas entre el desarrollo nativo para iOS y para Android en la actualidad?

3 - ¿A qué nos referimos cuando hablamos de desarrollo nativo en programación de APP móviles? ¿Qué ventajas ofrece sobre el desarrollo multiplataforma?

4 - ¿Qué ventaja principal ofrece un Framework Multiplataforma (como Flutter o React Native) frente al desarrollo nativo?

5 - En el contexto de la arquitectura móvil, ¿cuál es la función de una API REST importa el sistema operativo desde el cuál se consuma la API o es indistinto?

### Tip de Documentación: Tablas en Markdown
Para que las respuestas de los puntos 2 o 4 sean mucho más legibles y profesionales, se
sugiere utilizar una tabla comparativa. En el archivo README.md, puedes crear una
siguiendo este formato:
| Característica | Desarrollo Nativo | Multiplataforma (Flutter/RN) |
| :--- | :--- | :--- |
| Rendimiento | Optimizado al máximo | Muy alto (casi nativo) |
| Costo/Tiempo | Mayor (dos bases de código) | Menor (una base de código) |
| Acceso a Hardware | Total e inmediato | Depende de plugins/puentes |

Nota: No olvidar los guiones --- en la segunda línea para separar el encabezado del contenido. Una buena visualización técnica suma puntos en la calidad de entrega.

Desarrollo

1)- 
#### os principales sistemas operativos para dispositivos móviles en la actualidad

La mayoría de los teléfonos inteligentes funcionan con unos pocos sistemas operativos principales para dispositivos móviles, incluidos Apple iOS, Google Android.
| Sistema Operativo | Caracteristicas | Desarrollo Nativo | Multiplataforma (Flutter) |Multiplataforma (Reac Native) |
| :---: | :--- | :--- | :--- | :--- |
| Andorid | 1. Código Abierto. (Open Source). | 1. Entorno Android studio | 1. Lenguaje Flutter/Dark + (Java y kotlin) | 1. Componentes Nativos Reales |
|         | 2. Multitarea Real. | 2. Lenguajes: Java/kotlin | 2. Renderizado Propio (Skia/Impeller) | 2. Basado en React y JavaScript |
|         | 3. Ecosistema Google Play. | 3. Ventaja clave: Acceso inmediato a las últimas funciones de Android en cuanto salen al mercado | 3. Compilación en Código Nativo | 3.Fast Refresh (Recarga instantánea) |
| IOS | 1. Codigo Cerrado         | 1. Lenguajes: Swift | 1. Rendimiento en iOS: Fluido  | 1. Arquitectura "Fabric" |
|     | 2. Seguridad y Privacidad | 2. (IDE): Xcode | 2. Compilación: a lenguaje binario | 2. Uso de "Hermes" optimizado |
|     | 3. App Store              | 3. Ventaja clave: Apple es muy estricto con la experiencia de usuario (UX). El desarrollo nativo te da acceso total a tecnologías exclusivas como FaceID, Apple Pay, y los últimos avances en realidad aumentada con ARKit. | 3. Renderizado: Motor Impeller | 3. CocoaPods Integrado |

2)- 

| Criterio                    | IOS |               Android |
|--------------|--------------|--------------|
| Lenguajes Principales  |Swift y Objective-C. |   Kotlin y Java.            |
|Entorno de Desarrol(IDE)|     Xcode (exclusivo de macOS)     |    Android Studio (multiplataforma).       
|Arquitectura del SO     |  Basado en XNU (kernel Darwin), cerrado y optimizado para hardware Apple.   | Basado en Linux, modular y abierto con mayor fragmentación de dispositivos.|
|Acceso a Hardware | Acceso completo y optimizado a APIs nativas, pero con restricciones estrictas de seguridad y sandboxing.|Acceso amplio y flexible a funcionalidades del sistema y archivos,permitiendo mayor personalizacion y root.
|Gestion de memoria|Uso de ARC(Automatic Reference Counting)para automatizacion y seguridad.|Gestion de memoria explicita o automatica (Garbage o Collection),dependiendo del lenguaje.|
|Distribucucion y Actualizacion|Control cetralizado en App Store.Actualizaciones simultaneamente para todos los dispositivos compatibles.|Distribucion abierta (tiendas y APK),actualizaciones escalonadas dependiente del fabricante del dispositivo.|
|Diseño de interfaz (UI/UX)|Sigue las Human Interface Guidelines (HIG)con componentes como botones de llamada a la accion y selectores de fechas tipo rodillo.|Sigue Material Design con botones planos/elevados,textos en mayusculas y botones de acciones flotante(FAB)|



3)-
 #### .¿A qué nos referimos cuando hablamos de desarrollo nativo en programación de APP móviles?

#### El desarrollo móvil nativo:
 describe la creación de una aplicación específicamente para un sistema operativo móvil determinado, como iOS o Android, utilizando lenguajes de programación nativos de ese sistema operativo.

#### Desarrollo de aplicaciones móviles multiplataforma:
En este caso se utilizan herramientas que no son nativas de un sistema operativo determinado, pero que pueden producir aplicaciones nativas para cada plataforma a partir de una única base de código maestro.

Las herramientas de desarrollo multiplataforma pueden ahorrar tiempo y recursos al consolidar el trabajo de crear aplicaciones para múltiples sistemas operativos en un solo esfuerzo, pero existen algunos retos.

| Característica | Nativo | Multiplataforma |
| -------------- | ------ | ---------------- |
| Rendimiento | Alto, optimizado para cada sistema | Muy bueno, pero no siempre igual al nativo |
| Acceso a hardware | Completo | Depende de plugins |
| Tiempo de desarrollo | Mayor | Menor |
| Costo | Más alto | Más bajo |
| Mantenimiento | Más complejo | Más simple |
| Experiencia de usuario | Mejor integrada | Buena pero no perfecta |

4).
#### ¿Qué ventaja principal ofrece un Framework Multiplataforma frente al desarrollo nativo?

La principal ventaja de los frameworks multiplataforma como Flutter o React Native es que permiten desarrollar una sola aplicación con un único código que funciona en varios sistemas operativos como Android e iOS. Esto hace que el desarrollo sea más rápido, más económico y más fácil de mantener en comparación con el desarrollo nativo, donde se necesita una app diferente para cada sistema.

Además, facilita el trabajo en equipo y permite lanzar aplicaciones en menos tiempo, lo cual es muy útil para proyectos pequeños o medianos y para crear versiones iniciales de una app.

| Característica | Desarrollo Nativo | Multiplataforma |
| -------------- | ---------------- | ---------------- |
| Código | Uno por cada sistema | Un solo código para todos |
| Tiempo de desarrollo | Más largo | Más rápido |
| Costo | Más alto | Más bajo |
| Mantenimiento | Más complejo | Más simple |
| Rendimiento | Máximo | Muy alto (casi nativo) |
| Experiencia de usuario | Mejor integración | Buena y uniforme |


5)-
#### En Contexto de la arquitectura movil
la función principal de una API REST en la arquitectura móvil es actuar como un puente estandarizado que permite a las aplicaciones acceder, manipular y sincronizar datos y funcionalidades de un servidor remoto de forma segura y eficiente, independientemente de la complejidad interna del sistema. 
No importa el sistema operativo desde el cual se consuma la API; el protocolo es indistinto entre plataformas, iOS, Android, etc., ya que la arquitectura REST se basa en el estándar HTTP y en el intercambio de datos, generalmente JSON o XML, que cualquier dispositivo capaz de hacer solicitudes web puede interpretar. 

### Las funciónes y Principios Clave son;
### Separación de responsabilidades: 
Permite que el desarrollo del cliente, osea la app móvil, y del servidor osea el backend sea independiente, facilitando la evolución de cada parte sin afectar a la otra. 
### Interoperabilidad: 
Al utilizar métodos HTTP universales como GET, POST, PUT, DELETE, cualquier aplicación móvil, sin importar su lenguaje de programación o sistema operativo, puede comunicarse con el servicio. 
### Gestión de recursos: 
Funciona exponiendo recursos específicos como usuarios, productos o notificaciones a través de URLs únicas, permitiendo operaciones CRUD (Crear, Leer, Actualizar, Eliminar) de manera predecible.