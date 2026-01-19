# SISTEMAS CLOUD

![Nube](nube.jpg)

## MIGRACIÓN A LA NUBE

La transformación digital ya no es una opción. Migrar la nube se ha convertido en un paso esencial para las empresas que buscan mejorar su agilidad, eficiencia y competitividad. Con el objetivo de utilizar la tecnología para entender de mejor manera al cliente y optimizar operaciones de mercado.

- Visión 360 del cliente -> Unificar datos.
- Optimización de Operaciones -> Reducir el exceso de stock y mejorar logística.
- Agilidad del mercado -> Adaptarse rápidamente a las nuevas tendencias.

## REVOLUCIÓN DEL CLOUD COMPUTING

El cloud computing ofrece una alternativa rentable y escalable a la infraestructura locan. Externaliza el hardware y el software.

- Menos Costes -> Elimina la inversión inicial en hardware.
- Innovación Constante -> Acceso a las ultimas versiones sin costes adicionales.
- Mayor Escalabilidad -> Permite ampliar o reducir recursos según la demanda.
- Fiabilidad y Productividad -> Garantiza la disponibilidad del serviciio y facilita la colaboración y el teletrabajo.
- Seguridad Mejorada -> Los proveedores de la nube cuentan con equipos especializados en ciberseguridad.

## MODELOS DE SERVICIO

Los servicios en la nube se distribuyen en distintos modelos, cada modelo ofrece un nivel diferentede control y gestión.

- IaaS -> ofrecé la máxima dlexibilidad, el cliente controla la infraestructura virtual sin gestionar hardware.
- PaaS -> Es el entorno para desarrolladores, el cliente gestiona sus aplicaciones, mientras que el proveedor se encarga del SO.
- SaaS -> La solución lista para usar. El proveedor gestiona todo, el cliente solamente usa el software.
- CaaS -> Agilidad para aplicaciones modernas. Un modelo intermedio donde se gestionan aplicaciones a través de contenedores.

## ESPECTO DE RESPONSABILIDAD EN LA NUBE

| Capa / Modelo | IaaS | CaaS | PaaS | SaaS |
| :--- | :---: | :---: | :---: | :---: |
| **Datos y configuración** | C | C | C | S |
| **Aplicación** | C | C | C | S |
| **Escalabilidad** | C | C | S | S |
| **Runtime** | C | C | S | S |
| **Sistema operativo** | C | S | S | S |
| **Virtualización** | S | S | S | S |
| **Hardware** | S | S | S | S |

Cliente -> C
Servidor -> S

## LA EXPLOSIÓN DE DATOS DEL IoT

El éxito de la nube ha impulsado un mundo hiperconectado, donde miles de millones de dispositivos generan datos de forma exponencial.

- Volumen Masivo de Datos -> La gran cantidad de datos generada puede saturar las redes.
- Necesidad de respuesta Inmediata -> Muchas aplicaciones requieren decisiones en milisegundos.
- Autonomía y Conectividad -> Los dispositivos deben poder operar incluso con una conexión a internet inestable o inexistente.

## El límite de la Nube

### Latencia -> Es el tiempo que tardan los datos en viajer desde el dispositivo hasta el servidor y volver.

Para aplicaciones críticas como los vehículos autónomos o la videovigilancia inteligente, esperar a que los datos viajen a un servidor es inviable. Una decisión que llega tarde es inútil.

## Solución en la periferia

Edge computing es una tecnología que procesa los datos cerca del lugar en el que se generan.

- Reduce la latencia -> Las decisiones son casi instantáneas.
- Mejora la velocidad de respuesta -> Crucial para aplicaciones en tiempo real.
- Ahorra ancho de banda -> Solo envía a la nube la información relevante o ya procesada.
- Aumenta la privacidad y seguridad -> Los datos sensibles pueden procesarse localmente sin salir del perímetro.

### Edge en Acción

- Vehiculos autonomos

Toman decisiones de conducción en milisegundos (frenar, esquivar) sin depender de la nube.

- Edge AI

La combinación con inteligencia artificial. Tu teléfono reconoce tu cara para desbloquearse, sin enviar ninguna foto a un servidor.

- Ciudades Inteligentes

Semáforos que responden en tiempo real al flujo de tráfico para optimizar la circulación.


## NUBE VS EDGE

Cloud y edge no son competidores, son complementarios. Cada uno resuelve un tipo de problema diferente.

| NUBE | EDGE COMPUTING |
| :---: | :---: |
| ✓ Colaboración y Productividad | ✖️ Colaboración y Productividad | 
| ✓ Seguridad y privacidad (Centralizada) | ✖️ Seguridad y privacidad (Distribuida) | 
| ✓ Escalabilidad | ✖️ Escalabilidad |
| ✖️ Procesamiento en tiempo real | ✓ Procesamiento en tiempo real |

  
## FOG Y MIST COMPUTING

El concepto de proximidad es un espectro. Entre la nube distante y el dispositivo inmediato existen capas intermedias.

-Cloud (Nube): El procesamiento más lejano. Se realiza en servidores remotos, centralizados.
-Fog (Niegla): Procesamiento cercano, de ámbito local o regional. Un nodo 'fog' puede dar servicio a múltiples dispositivos 'edge'.
-Mist (Rocío): Procesamiento inmediato. Se realiza directamente en los microcontroladores o sensores del propio dispositivo.

## EL CONTNUO COMPUTACIONAL

los sistemas modernos operan a lo largo de un continuo. Los datos se generan en la capa 'mist', se pueden agregar en la capa 'fog', y los análisis a gran escala se realizan en la 'cloud'. Minimiza la latencia y maximiza la eficiencia.

## Eligiendo la Heraramienta Adecuada para cada tarea

La eficiencia de un sistema digital depende de procesar los datos en la capa correcta. No hay una solución unica

Se debe utilizar ***Mist/Edge*** cuando necesitemos una respuesta instantanea, tengamos una conexión a internet inestable o inexistente, datos sensibles y necesitemos autonomía.

Se debe utilizar ***FOG*** cuando necesitemos coordinar múltiples dispositivos edge en un área local, requerimos un procesamiento de datos, antes de enviarlos a la nube, y necesitamos una respuesta rápidan pero no instantánea.

Se debe utilizar ***CLOUD*** cuando queremos almacenar grandes volúmenes de datos históricos, procesamientos complejos y insensibles al tiempo o requiramos herramientas de colaboración y acceso desde múltiples ubicaciones.


## CONSTRUYENDO SISTEMAS DIGITALES INTELIGENTES Y RESILIENTES

La arquitectura del futuro no es ni centralizada ni descentralizada, es híbrida y distribuida.
Combina el poder de la nube, con la agilidad del edge, fog y mist, podemos crear sistemas que son simultáneamente potentes, rápidos, seguros y eficientes.

1- Captura y respuesta en tiempo real (Edge/Mist)
2- Agregación y análisis local (Fog)
3- Análisis profundo y re-entrenamiento de modelos de IA (Cloud)
4- Los nuevos modelos y la lógica de negocio se despliegan de vuelta al Edge.

## EL FUTURO ES UN PAISAJE COMPUTACIONAL HÍBRIDO

El paradigma ha cambiado. Ya no se trata de elegir 'donde' computar, sino de entender todo, desde el núcleo centralizado de la nube, hasta la periferia inmediata del dispositivo. La cosa es dominar este paisaje para diseñar la próxima generación de tecnología, desde la IA hasta las experciencias inmersivas del mañana.

