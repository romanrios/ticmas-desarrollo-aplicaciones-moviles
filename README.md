# Proyecto final - Desarrollo de aplicaciones móviles

Argentina Programa 4.0 - Ticmas Academy - Curso de Desarrollo de aplicaciones móviles - Presentación de actividad y proyecto final integrador - Román Ríos

![WhatsApp Image 2023-07-25 at 14 14 55](https://github.com/romanrios/ticmas-desarrollo-aplicaciones-moviles/assets/122373737/d6069add-d24e-4a2d-808f-7799561b0717)


## Actividad 1

Requerimientos

Generá un archivo .doc con lo planteado en la consigna. Adjuntá los resultados de este ejercicio en el proyecto final que entregarás al final de este recorrido.


Ejercicio práctico

Introducción a Android

Crear una aplicación utilizando Android Studio con las siguientes especificaciones:

•	Nombre: AppPractica1

•	Nombre del paquete: com.curso.android.app.practica.uno

•	Versión mínima a soportar: Android 5

•	Basa en un template del tipo: Vista Primaria con Detalle

 
**Actividad 1**

Crear un emulador del tipo Tablet, con un tamaño de pantalla de al menos 8”.
1.	Correr la aplicación en el emulador en orientación Portrait (vertical).
2.	Correr la aplicación en el emulador en orientación Landscape (horizontal).


![image005](https://github.com/romanrios/ticmas-desarrollo-aplicaciones-moviles/assets/122373737/39ab6ada-42d0-45a2-bbc4-0c43072a6266)

![image007](https://github.com/romanrios/ticmas-desarrollo-aplicaciones-moviles/assets/122373737/41b963ab-470d-4209-942d-2ea2f97a6915)

**Actividad 2**

Crear un emulador del tipo Teléfono.

Correr la aplicación en el emulador en orientación Portrait (vertical).

Correr la aplicación en el emulador en orientación Landscape (horizontal).

![image009](https://github.com/romanrios/ticmas-desarrollo-aplicaciones-moviles/assets/122373737/6ceeb5ae-aa60-4a32-bde7-9016b76e1e24)

![image011](https://github.com/romanrios/ticmas-desarrollo-aplicaciones-moviles/assets/122373737/cd14b494-84ba-4698-818e-9a3bf3e37860)

**Actividad 3**

En ambos los casos:

Indicar que configuración tiene cada emulador creado (versión de Android, tamaño de pantalla, memoria RAM).
Realizar capturas de pantalla de cómo se ven todas las pantallas de la aplicación en cada configuración.
 

**Respuesta:**

**Tablet: Nexus 9**

Versión de Android: API 30 / Android 11.0

Tamaño de pantalla: 8,86” / 2048 x 1536 px

Memoria RAM: 1536 MB

<div style="display: flex; justify-content: space-between;">
  <img src="https://github.com/romanrios/ticmas-desarrollo-aplicaciones-moviles/assets/122373737/5678f78c-b4fe-4bdb-a6dc-224b92d3d5bb" alt="Imagen 1" width="400"/>
  <img src="https://github.com/romanrios/ticmas-desarrollo-aplicaciones-moviles/assets/122373737/04490ffd-944e-426a-b3ce-b3b84034749d" alt="Imagen 2" width="400"/>
</div>

**Teléfono: Pixel 2**

Versión de Android: API 30 / Android 11.0

Tamaño de pantalla: 5,0” / 1080 x 1920 px

Memoria RAM: 1536 MB

<div style="display: flex; justify-content: space-between;">
  <img src="https://github.com/romanrios/ticmas-desarrollo-aplicaciones-moviles/assets/122373737/78130605-9fc9-41e7-beb4-0110fe8aea92" alt="Imagen 1" width="300"/>
  <img src="https://github.com/romanrios/ticmas-desarrollo-aplicaciones-moviles/assets/122373737/6a5bedf6-6c29-4d9f-bbf2-ea0f9d00cd6e" alt="Imagen 2" width="300"/>
  <img src="https://github.com/romanrios/ticmas-desarrollo-aplicaciones-moviles/assets/122373737/0b4744a9-f9c0-484b-b386-c52e55857ae9" alt="Imagen 3" width="300"/>
  <img src="https://github.com/romanrios/ticmas-desarrollo-aplicaciones-moviles/assets/122373737/1fa19a05-68aa-4727-b80f-ec2c84fd241b" alt="Imagen 4" width="600"/>
  <img src="https://github.com/romanrios/ticmas-desarrollo-aplicaciones-moviles/assets/122373737/78fb1d20-c66a-4203-ab65-1e531836ae6f" alt="Imagen 5" width="600"/>
  <img src="https://github.com/romanrios/ticmas-desarrollo-aplicaciones-moviles/assets/122373737/eabf8495-5dd8-4bfa-98ef-e729b52f55c2" alt="Imagen 6" width="600"/>
</div>


Actividad 4

¿Qué diferencia observás en el funcionamiento de la aplicación en una Tablet con orientación Landscape y un teléfono con orientación Portrait?
 

Respuesta:

En una Tablet con orientación Landscape, la aplicación muestra tanto el listado como el detalle en la misma pantalla. Esto es posible porque la pantalla más grande de la Tablet permite que ambos elementos se ajusten y se muestren al mismo tiempo. Por lo tanto, el usuario puede ver la lista de elementos y seleccionar uno para ver los detalles en la misma vista.

En cambio, en un teléfono con orientación Portrait, debido a la pantalla más pequeña, la aplicación muestra una instancia en simultáneo, es decir, solo muestra el listado o el detalle en una sola pantalla a la vez. Para ver los detalles de un elemento en el listado, el usuario debe seleccionarlo y luego la vista cambiará para mostrar los detalles en una nueva pantalla.

 

Actividad extra

1. ¿En qué archivo está el nombre de tu aplicación? Probá cambiarlo y correr la aplicación nuevamente.

2. ¿Y el ícono?

 
**Respuesta:**

El nombre de la aplicación "AppPractica1" se encuentra en el atributo 'android:label' dentro del archivo **./app/manifests/AndroidManifest.xml**. Opcionalmente, este nombre puede estar referenciado desde **./app/res/values/strings.xml**.

Modificar este nombre tiene un impacto directo en la forma en que vemos el nombre de la aplicación en la pantalla de inicio o en el listado de aplicaciones del dispositivo donde la estemos ejecutando.

En cuanto al ícono de la aplicación, los archivos correspondientes se encuentran en **./app/res/mipmap/**, con las carpetas **ic_launcher, ic_launcher_foreground, e ic_launcher_round** para los distintos formatos del ícono.

Para crear o modificar el ícono de la aplicación, podemos utilizar Asset Studio, una herramienta incluida en Android Studio que facilita su creación. Asset Studio nos permite generar los íconos en diferentes tamaños y formatos para que la aplicación se vea correctamente en diferentes dispositivos y situaciones.


# PROYECTO FINAL INTEGRADOR

**CONSIGNA**

Desarrollá una aplicación que tenga un solo activity que cumpla con las siguientes premisas:

 

Contenga una única pantalla (sin importar el layout elegido) con:

- 2 cuadros de textos (EditText)

- 1 botón con el texto “comparar”

- 1 texto (TextView) que en el que se escriba el resultado de la acción al presionar el botón.

 

Asegurarse de que:

1. Utiliza MVVM

2. Tiene al menos un test unitario

3. Tiene al menos un test de UI

 

Función de la aplicación

Cuando el usuario hace clic en el botón “comparar” debe comparar la entrada de ambos cuadros de texto y escribir en el texto (TextView) si ambas cadenas de caracteres son iguales o no.

 

Requerimientos

1. Usá un repositorio de GitHub pages para subir tu proyecto (Repositorio app laboratorio: https://github.com/eaceto/ticmas-lab-android Con lo visto en el último módulo del curso, vas a poder subir sin problema tu proyecto a la web.

2. Generá un archivo .doc con lo planteado en la consigna y el link de tu entregable.

3. Luego, subilo en el bloque "Proyectos" que se encuentra en la página principal del curso, en la plataforma.


**CREANDO EL NUEVO PROYECTO**

Para cumplir con lo solicitado en la consigna, creé un nuevo proyecto con las siguientes especificaciones:

Plantilla: Empty Views Activity

Nombre: Proyecto Final

Package Name: com.ticmas.romanrios.proyectofinal

SDK mínimo: API 21 – Android 5.0 (Lollipop)

Lenguaje: Kotlin

 

**DISEÑANDO LA UI**

Luego diseñé la UI con los elementos visuales solicitados, para esto edité el archivo **activity_main.xml** ubicado en **.app/res/layout/**

Adicionalmente agregué el logo de Ticmas y el nombre del curso.

Solo emplea un LinearLayout, es sencilla y se acomoda bien a distintos formatos de pantalla y orientaciones.

![image005](https://github.com/romanrios/ticmas-desarrollo-aplicaciones-moviles/assets/122373737/4b9ad1e2-1ec7-4da1-a374-a75cbb695416)


**DEPENDENCIAS**

Previamente revisé si tenía las dependencias necesarias en ‘gradle.bundle’ comparando mi proyecto con el ejemplo de Laboratorio que vimos en el cursado, algunas ya se encontraban presente en mi archivo, otras tuve que agregarlas, realicé una pequeña investigación para tener presente para qué sirven y luego poder removerlas en el futuro si no llegara a usarlas.

**Dependencias para Kotlin y Coroutines:**

    implementation "androidx.fragment:fragment-ktx:1.5.4":

Proporciona extensiones de Kotlin para trabajar con fragments.

    implementation "androidx.activity:activity-ktx:1.6.1":

Proporciona extensiones de Kotlin para trabajar con activities.

    implementation "androidx.lifecycle:lifecycle-viewmodel-ktx:2.5.1":

Proporciona extensiones de Kotlin para trabajar con ViewModel del ciclo de vida.

    implementation "androidx.lifecycle:lifecycle-livedata-ktx:2.5.1":

Proporciona extensiones de Kotlin para trabajar con LiveData del ciclo de vida.

    implementation 'org.jetbrains.kotlinx:kotlinx-coroutines-android:1.6.1':

Proporciona soporte para Coroutines en Android.

 

**Dependencias para testing:**

    testImplementation "org.jetbrains.kotlinx:kotlinx-coroutines-test:1.6.1":

Proporciona clases de ayuda para testing de Coroutines.

    testImplementation "androidx.arch.core:core-testing:2.1.0":

Proporciona clases de ayuda para testing de componentes LiveData.

    androidTestImplementation 'com.android.support.test:rules:1.0.2':

Proporciona reglas y funcionalidades para testing de Android.

    androidTestImplementation 'com.android.support.test:runner:1.0.2':

Proporciona el runner necesario para realizar pruebas instrumentadas.

    androidTestImplementation 'androidx.test.ext:junit:1.1.5':

Proporciona clases de ayuda para testing de JUnit 4 en pruebas instrumentadas.

    androidTestImplementation 'androidx.test.espresso:espresso-core:3.5.1':

Proporciona clases y métodos para realizar pruebas de UI utilizando Espresso.

    testImplementation 'junit:junit:4.13.2':

Proporciona la biblioteca de JUnit para realizar pruebas unitarias.

 

**Dependencias para componentes de diseño:**

    implementation 'androidx.core:core-ktx:1.8.0':

Extensiones de Kotlin para trabajar con bibliotecas de compatibilidad de Android.

    implementation 'androidx.appcompat:appcompat:1.4.1':

Compatibilidad con versiones anteriores de Android.

    implementation 'com.google.android.material:material:1.5.0':

Proporciona estilos y componentes de diseño de Material Design para la UI.

    implementation 'androidx.constraintlayout:constraintlayout:2.1.4':

Proporciona una biblioteca para trabajar con el diseño de constraints en las vistas.


**PROGRAMANDO LA FUNCIONALIDAD DE LA APLICACIÓN**

La aplicación debe cumplir la función solicitada respetando la arquitectura MVVM y los principios SOLID. Los archivos deben tener responsabilidades únicas y bien definidas, que faciliten el mantenimiento y la escalabilidad del código.

De esta manera, organicé mi código en los siguientes archivos:

![image007](https://github.com/romanrios/ticmas-desarrollo-aplicaciones-moviles/assets/122373737/7661e44f-db05-423a-9406-a9e234b9ce6f)

**DataModel.kt**

Ubicado en ./app/java/com.ticmas.romanrios.proyectofinal/model/

Define el modelo de datos DataModel que contiene las propiedades text1, text2 y tvResult. Su única responsabilidad es definir la estructura de datos.

 

**MainActivity.kt**

Ubicado en ./app/java/com.ticmas.romanrios.proyectofinal/view/

Representa la actividad principal de la aplicación y se encarga de la interacción con la interfaz de usuario. Interactúa con el ViewModel (MainViewModel) a través del patrón de observación (LiveData) para obtener el resultado de la comparación de textos y actualizar la interfaz de usuario en consecuencia.

 

**MainViewModel.kt**

Ubicado en ./app/java/com.ticmas.romanrios.proyectofinal/view/

Representa el ViewModel de la aplicación, que actúa como intermediario entre la actividad y el modelo de datos. Contiene la lógica de negocio para la comparación de textos y expone el resultado a través de LiveData para que la actividad pueda observarlo.


**CAPTURAS**

Luego de algunos ajustes en el código ya tengo mi aplicación funcionando, aquí algunas capturas de la aplicación corriendo en mi celular Android físico:

<div style="display: flex; justify-content: space-between;">
  <img src="https://github.com/romanrios/ticmas-desarrollo-aplicaciones-moviles/assets/122373737/0b57ba30-6f5c-4580-9cf5-4a1d854a2ee6" alt="Imagen 4" width="300"/>
   <img src="https://github.com/romanrios/ticmas-desarrollo-aplicaciones-moviles/assets/122373737/3199a595-3864-4475-98c9-efbbf43bf9ae" alt="Imagen 0" width="600"/>
  <img src="https://github.com/romanrios/ticmas-desarrollo-aplicaciones-moviles/assets/122373737/d27479b9-9ea1-4d8a-8468-7084ffe08270" alt="Imagen 1" width="300"/>
  <img src="https://github.com/romanrios/ticmas-desarrollo-aplicaciones-moviles/assets/122373737/3269a8a4-fb59-4182-8630-c2f74fc08159" alt="Imagen 2" width="300"/>
  <img src="https://github.com/romanrios/ticmas-desarrollo-aplicaciones-moviles/assets/122373737/7ba3e664-ee35-4e5f-8b29-e224dba10c86" alt="Imagen 3" width="300"/>
</div>


**TEST UNITARIO**

El siguiente paso es programar los test.

![image019](https://github.com/romanrios/ticmas-desarrollo-aplicaciones-moviles/assets/122373737/8de13795-bb5c-49c4-b9e1-11eb9709cfed)

**TestUnitario.kt**

Ubicado en ./app/java/com.ticmas.romanrios.proyectofinal (test)

**mainViewModel_TestCompareTexts_EmptyFields():** Verifica si la función **compareTexts()** del **MainViewModel** maneja correctamente el caso en que ambos campos de texto están vacíos. Comprueba si el resultado mostrado en el LiveData result es "Campos incompletos".
**mainViewModel_TestCompareTexts_EqualTexts():** Verifica si la función **compareTexts()** del **MainViewModel** maneja correctamente el caso en que ambos campos de texto son iguales. Comprueba si el resultado mostrado en el LiveData result es "Los textos son IGUALES".
**mainViewModel_TestCompareTexts_DifferentTexts():** Verifica si la función **compareTexts()** del **MainViewModel** maneja correctamente el caso en que los campos de texto son diferentes. Comprueba si el resultado mostrado en el LiveData **result** es "Los textos son DIFERENTES".

**TEST INSTRUMENTADO**

**TestInstrumentado.kt**

Ubicado en ./app/java/com.ticmas.romanrios.proyectofinal (androidTest)

**mainActivity_compareTextsEqual():** Verifica si la actividad **MainActivity** muestra correctamente el resultado "Los textos son IGUALES" cuando se ingresan textos iguales en los EditText y se hace clic en el botón "comparar". Utiliza Espresso para interactuar con los elementos de la interfaz de usuario y verificar que el resultado se muestre correctamente en el TextView.

**mainActivity_compareTextsDifferent():** Verifica si la actividad **MainActivity** muestra correctamente el resultado "Los textos son DIFERENTES" cuando se ingresan textos diferentes en los EditText y se hace clic en el botón "comparar". Utiliza Espresso para interactuar con los elementos de la interfaz de usuario y verificar que el resultado se muestre correctamente en el TextView.

**mainActivity_compareTextsEmptyFields():** Verifica si la actividad **MainActivity** muestra correctamente el resultado "Campos incompletos" cuando no se ingresa texto en los EditText y se hace clic en el botón "comparar". Utiliza Espresso para interactuar con los elementos de la interfaz de usuario y verificar que el resultado se muestre correctamente en el TextView.

**ÍCONOS**

Para finalizar, se crearon los íconos para la aplicación utilizando Asset Studio. Se ubican automáticamente en sus carpetas correspondientes en **.app/res/mipmap/**

Utilicé el logo de Ticmas como imagen foreground y un color plano blanco como background.

<div style="display: flex; justify-content: space-between;">
  <img src="https://github.com/romanrios/ticmas-desarrollo-aplicaciones-moviles/assets/122373737/98081fcc-3e76-4878-8a17-92cd0cd613b3" alt="Imagen 1" width="300"/>
  <img src="https://github.com/romanrios/ticmas-desarrollo-aplicaciones-moviles/assets/122373737/a3bebce8-683c-4fd5-8ac7-de02ef2a80c7" alt="Imagen 2" width="300"/>
  <img src="https://github.com/romanrios/ticmas-desarrollo-aplicaciones-moviles/assets/122373737/e83dce4d-86c2-41f0-88a4-73750a10a456" alt="Imagen 3" width="300"/>
</div>


La aplicación ya se encuentra lista para poder construir un APK o un Bundle, ser firmada y distribuida.
