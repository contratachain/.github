# ContrataChain: Sistema de Calificación de Contratos Públicos

## Descripción del Proyecto

**ContrataChain** es una plataforma descentralizada diseñada para transformar la manera en que se gestionan los contratos públicos y la calificación de proveedores en Colombia. En un contexto donde la opacidad y la corrupción afectan la contratación pública, esta plataforma busca garantizar mayor transparencia y eficiencia en los procesos de contratación de bienes y servicios. El uso de tecnologías como **blockchain**, **smart contracts** y soluciones modernas de desarrollo permite crear un sistema que no solo es seguro, sino también accesible e inmutable, lo que permite una gestión de contratos más justa y transparente.

### Problema

La falta de acceso a información confiable sobre proveedores y contratos públicos, sumado a la corrupción y la manipulación de datos, genera riesgos significativos en la contratación pública. Esto no solo afecta la calidad de los servicios y productos, sino que también desperdicia recursos públicos y perjudica la confianza en las instituciones gubernamentales.

### Solución

La plataforma **ContrataChain** proporciona una herramienta innovadora que utiliza **blockchain** para almacenar y procesar la información de los proveedores, contratos y calificaciones. Los **smart contracts** se encargan de automatizar el proceso de evaluación y calificación de los proveedores, asegurando que toda la información sea transparente, verificable y accesible públicamente.

Los usuarios de la plataforma, que incluyen tanto empresas privadas como organismos gubernamentales, pueden consultar el historial de cumplimiento, las calificaciones y la información relevante sobre proveedores, lo que facilita la toma de decisiones informadas.

## Arquitectura del Sistema

La solución de **ContrataChain** está construida sobre una arquitectura de **blockchain** que garantiza la seguridad, transparencia e inmutabilidad de todos los datos relacionados con los proveedores y los contratos. Los componentes clave de la arquitectura incluyen:

- **Blockchain Pública y Descentralizada**: Utiliza **Ethereum** como base para almacenar y procesar la información crítica. La blockchain asegura que los datos no puedan ser manipulados y que todas las transacciones sean verificables.
  
- **Smart Contracts**: Desarrollados para automatizar la calificación de los proveedores. Estos contratos procesan los datos de los proveedores y calculan las calificaciones de manera automática, actualizando directamente la blockchain con los resultados. Esto garantiza que el proceso sea transparente y sin intervención humana, reduciendo el riesgo de errores o manipulaciones.
  
- **Interfaz de Usuario (UI)**: La plataforma incluye una interfaz web sencilla e intuitiva que permite a los usuarios consultar información sobre proveedores y contratos. Está diseñada para ser fácil de usar, incluso para aquellos sin experiencia en tecnología blockchain.

## Modelo de Negocio

El modelo de negocio de **ContrataChain** se basa en una estructura que combina suscripciones y servicios de consultoría, con un enfoque en ofrecer valor tanto a empresas como a organismos gubernamentales:

1. **Suscripciones**: Las empresas y organismos gubernamentales pueden suscribirse a la plataforma para acceder a información detallada y actualizada sobre los proveedores registrados. Esto les permite tomar decisiones más informadas al seleccionar proveedores, reduciendo el riesgo de corrupción o baja calidad en los contratos.
   
2. **Servicios de Consultoría**: La plataforma ofrecerá servicios de análisis de datos y consultoría, ayudando a las entidades a mejorar sus procesos de contratación y a integrar de manera efectiva la tecnología blockchain en sus sistemas.

3. **Publicidad**: A medida que la plataforma crezca, se abrirá la posibilidad de generar ingresos a través de publicidad dirigida a empresas y organismos relacionados con el sector público y privado.

### Visión Futura

En el futuro, **ContrataChain** tiene la intención de expandir sus capacidades mediante la integración de **Arweave**, una plataforma de almacenamiento permanente, descentralizado y de bajo costo. Arweave permitirá guardar los contratos y documentos de manera **permanente** y **segura** sin depender de servidores centrales, lo que garantiza que los datos nunca puedan ser manipulados ni "olvidados".

La plataforma también está explorando la posibilidad de almacenar la **interfaz web** como una **permaweb** (web permanente) sobre **Arweave**, para garantizar que la plataforma siga siendo accesible a largo plazo sin riesgo de pérdida de datos o control centralizado. Esta integración es parte de nuestra visión a largo plazo de crear una infraestructura completamente descentralizada.

Se planea utilizar Arbitrum Stylus para el tema de escalabilidad, por lo que con esto podriamos solucionar el trilema Arweave solucionando la descentralización, y Arbitrum Stylus soluciona la escalabilidad gracias a wasm y seguridad gracias al garbage collector y otras geniales que como lenguaje de programación rust sea seguro hacer smart contracts.

También y por ahora es una calificadora de que tan probable sea corrupto un contrato, haciendo scrapping a secop II (Servicio de Contratación Publica de Colombia). Pero lo ideal es **mejorar** o **remplazar** Secop II, Secop II solo rastrea los contratos, más no el dinero que pasa a través de bancos o cheques algo que es dificil de rastrear tanto para veedores como funcionarios de contralorias.

A nivel legal hay muchas cosas que nos respalda como la ley 1745 de ley transparencia de 2014, pero una cosa es lo que dice la ley y otra cosa es si es aprobada esta herramienta como estandar para disminuir la corrupción de los contratos que hacen las entidades publicas o que manejan dinero publico.

## Beneficios del Sistema

- **Transparencia**: Toda la información es pública y accesible para cualquier usuario, lo que aumenta la confianza en los procesos de contratación pública.
  
- **Inmutabilidad**: Los datos no pueden ser alterados sin el consenso de la red, garantizando que no haya manipulaciones de la información.
  
- **Automatización**: Los **smart contracts** permiten automatizar los procesos de calificación, eliminando la posibilidad de errores humanos y agilizando las decisiones de contratación.
  
- **Seguridad**: La plataforma asegura que todos los datos estén protegidos contra accesos no autorizados, utilizando criptografía avanzada y blockchain.

## Tecnologías Utilizadas

El sistema está compuesto por una combinación de tecnologías modernas que garantizan la eficiencia y seguridad del sistema:

- **Blockchain (Ethereum/Arbitrum)**: Base de la plataforma para almacenar y procesar la información de manera descentralizada y segura.
  
- **Smart Contracts (Solidity)**: Los contratos inteligentes calculan y actualizan las calificaciones de los proveedores en la blockchain.

- **Frontend (Next.js)**: Una interfaz web amigable que facilita la consulta y visualización de los proveedores y contratos.

- **Backend (Arweave)**: En el futuro, se planea utilizar **Arweave** para almacenar de forma permanente los contratos y otros documentos críticos, evitando la dependencia de servidores tradicionales.

- **Frameworks de Desarrollo**: **Scaffold-ETH** y **Hardhat** para el desarrollo de contratos inteligentes.

## Repositorios

Scaffold-Eth es un monorepositorio si queremos a nivel de arquitectura escalarlo se harían estos 3 repositorios:

Cada componente clave del proyecto tiene su propio repositorio para facilitar la gestión y el desarrollo independiente de cada parte. Los repositorios son los siguientes:

1. [**ContrataChain Backend**](https://github.com/contratachain/contratachainBackend): Aquí se encuentra la lógica de almacenamiento con Arweave, no es como una base de datos tradicional es para guardar datos en frio, se evalua si se debería implementar este almacenamiento descentralizado o usar algo más tradicional.
   
2. [**ContrataChain Frontend**](https://github.com/contratachain/contratachainFrontend): Contiene la interfaz de usuario construida en **Next.js**, donde los usuarios pueden consultar la información de los proveedores y visualizar las calificaciones.
   
3. [**ContrataChain Blockchain**](https://github.com/contratachain/contratachainBlockchain): Aquí se encuentran la logica de los contratos inteligentes y las configuraciones necesarias para la interacción con la blockchain (Ethereum/Arbitrum).

## Video de Prueba de Concepto

Puedes ver un video de la **prueba de concepto** del sistema en funcionamiento en el siguiente enlace: [Ver video de prueba de concepto](https://youtu.be/w5qkjixP8lY).
