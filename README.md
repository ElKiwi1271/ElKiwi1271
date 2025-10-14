## Hi there 👋

<!--
**ElKiwi1271/ElKiwi1271** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->Restricciones técnicas:
Nombre su proyecto como eanrcucode donde nrc es su código de NRC y code es su código de estudiante
en minúsculas (por ejemplo ea4395u201621873).
Debe generar el proyecto con Vite y utilizar Vue 3, con Composition API. El equipo requiere que la
interfaz de usuario esté basada en Material Design utilizando la biblioteca de componentes de UI
PrimeVue, junto con la biblioteca de utilidades de CSS PrimeFlex y la biblioteca de icons PrimeIcons,
Página 4 de 6
mientras que para la comunicación con el backend debe apoyarse en axios
(https://github.com/axios/axios). La aplicación debe soportar in-app navigation y utilizar VueRouter
(https://router.vuejs.org/) para el manejo de routing en la aplicación, incluyendo child routes para cada
bounded context. Debe incluir ARIA atributes en las vistas. La interfaz de usuario debe mostrar los textos
en inglés. Para el soporte de i18n utilice Vue-i18n (https://vue-i18n.intlify.dev/). Utilice Pinia
(https://pinia.vuejs.org/) para el state management store de cada bounded context. La organización del
proyecto debe ser domain-driven aplicando layered y component-based architecture, object-oriented
programming y design patterns, considerando los sub-dominios shared (para elementos base o de uso
común en otros sub-dominios y insurance (para componentes o elementos relacionados con brokers,
incluyendo lo relacionado a payments). La programación en JavaScript debe ser object-oriented.
Distribuya adecuadamente los elementos dentro de cada carpeta de sub-dominio, considerando
carpetas presentation, infrastructure, aplication, domain, así como subcarpetas según el tipo de layer
que corresponda. Considere dentro de los layers sub-carpetas como views, components, model. En
views solo se ubican componentes que tienen relación directa con rutas de navegación. En components
se ubican componentes que son incluidos en otros y no están asociados de forma directa a rutas de
navegación. Aplique buenas prácticas para nomenclatura lógica y física de clases y componentes.
Aplique patrones de diseño, incluyendo Request/Response, Resource, Assembler, Api, Endpoint, State
Management (Store). Aplique buenas prácticas y convenciones aplicadas en clase para nomenclatura
lógica y física de clases y componentes. El proyecto de aplicación debe poder aperturarse sin problemas
en JetBrains WebStorm. Para la nomenclatura física de componentes, clases e interfaces utilice kebab-
case. Aplique en los nombres físicos sufijos que indiquen el tipo de elemento: .entity.js, .store.js,
.assembler.js. En el caso de entities, el sufijo entity no debe ser parte del nombre de la entidad cuando
se declare la clase (Por ejemplo person.entity debería utilizarse en código de clase como Person). No se
aplica sufijos .component para archivos de componentes. Utilice environment variables para evitar hard
coding de URLs o PATHs. Para la nomenclatura de componentes de PrimeVue dentro de los templates
utilice kebab-case. Asigne el prefijo pv- al momento de incorporar su uso en el proyecto (Por ejemplo,
pv-card). Para los identificadores de textos de traducción de idiomas, utilice kebab-case. Para
referenciar a los componentes dentro de templates utilice kebab-case.
Para los cálculos analíticos como promedios u otros, construya funciones personalizadas, pudiendo
utilizar en su implementación iteraciones, o las funciones reduce(), map() o forEach() de JavaScript
según convenga (ver referencias).
Para aplicar filtros a colecciones de elementos puede utilizar la función filter() de JavaScript (ver
referencias). Para dar formato a números puede utilizar la función de JavaScript NumberFormat (ver
referencias). Comente los archivos de código fuente en JavaScript elaborados por usted utilizando las
convenciones de JSDoc (ver referencias), con block comments incluyendo descripción resumida, un
texto de @summary con el propósito y @author con su nombre y apellido. Incluya en el archivo
README.md, la información en inglés de la aplicación, descripción, features y su información como
author.
Antes de la generación del archivo .zip (único formato válido) para el envío, elimine la carpeta
node_modules. El nombre del archivo .zip debe seguir la estructura eanrcucode.zip (por ejemplo,
ea7420u201821873.zip).
