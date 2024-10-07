# Chacka360 - Plataforma de Agricultura Inteligente

Chacka360 es una solución avanzada diseñada para optimizar la producción agrícola mediante el uso de UAVs (drones) y tecnologías de sensores ambientales. La plataforma permite a los agricultores analizar grandes extensiones de terreno y tomar decisiones informadas sobre los cultivos más adecuados para sus campos, basándose en datos en tiempo real y datos satelitales de la NASA.

## Características principales:
- **Análisis en tiempo real**: Recopilación de datos como temperatura, humedad, altitud, presión atmosférica y calidad del aire.
- **Integración de datos satelitales**: Información adicional como la humedad del suelo y patrones de precipitación proporcionada por la NASA.
- **Mapas interactivos**: Identificación de zonas óptimas para diferentes cultivos basadas en las condiciones del suelo.
- **Plataforma fácil de usar**: Panel de control intuitivo para visualizar datos y recomendaciones.

## Componentes del Proyecto

### 1. Aplicación Flutter

La aplicación móvil/dashbord fue desarrollada en Flutter y permite a los agricultores visualizar los datos recopilados por el dron en tiempo real. La app ha sido probada tanto en **Android** como en la **web**.

**Repositorio Flutter**: [Link al Repositorio Flutter](https://github.com/tu-repositorio-flutter)

#### Instrucciones para correr la aplicación:
1. Clona el repositorio:  
   ```bash
   git clone https://github.com/tu-repositorio-flutter.git

2. Accede al directorio del proyecto 
   ```bash
   git clone https://github.com/tu-repositorio-flutter.git

3. Instala las dependencias:  
   ```bash
   git clone https://github.com/tu-repositorio-flutter.git

4. Corre la aplicación
   ```bash
   git clone https://github.com/tu-repositorio-flutter.git


## 2. Estación Meteorológica con ESP32

El sistema de sensores está construido sobre un **ESP32** y recopila datos en tiempo real desde diferentes sensores ambientales. El ESP32 está conectado a internet para transmitir los datos a la plataforma **Chacka360**.

### Sensores integrados:
- **GPS**: Ubicación precisa del dron y sus lecturas.
- **Presión atmosférica**: Medida en milibares (mb).
- **Altitud**: Medida en metros sobre el nivel del mar (msnm).
- **Humedad**: Expresada en porcentaje (%).
- **Temperatura**: Expresada en grados Celsius (°C).
- **Calidad del aire**: Medida en partes por millón (PPM).

**Repositorio del Sistema de Sensores**: [Link al Repositorio de ESP32](https://github.com/tu-repositorio-esp32)

## 3. Carcasa Impresa en 3D

La estación meteorológica está alojada en una carcasa impresa en 3D que protege los sensores de las condiciones climáticas y permite su uso eficiente en el dron **Bebop 2**.

## 4. Dron Bebop 2

El sistema está actualmente integrado con el dron **Bebop 2**, que se utiliza para la recopilación de datos sobre grandes extensiones de terreno agrícola.

## 5. Predicción de Datos usando IA y Datos Satelitales de la NASA

La plataforma **Chacka360** no solo recopila datos en tiempo real de sensores locales, sino que también utiliza datos satelitales de la **NASA** para realizar predicciones sobre las condiciones climáticas y del terreno. Estas predicciones son realizadas mediante el uso de algoritmos de **Inteligencia Artificial (IA)**, que procesan grandes cantidades de datos históricos y en tiempo real para ayudar a los agricultores a tomar decisiones más informadas.

### Fuentes de Datos Satelitales:
- **Humedad del suelo**: Datos que permiten predecir la disponibilidad de agua en diferentes zonas del terreno.
- **Patrones de precipitación**: Información sobre lluvias pasadas y futuras que impactan las decisiones de riego y siembra.
- **Imágenes infrarrojas**: Monitoreo de la vegetación para identificar el crecimiento y la salud de los cultivos.

### Algoritmo de IA:
El sistema de IA analiza y correlaciona los datos recolectados por los **sensores locales** (dron y estación meteorológica) y los **datos satelitales** para predecir:
- Riesgos de **sequía** o **exceso de agua** en áreas específicas.
- Condiciones óptimas de **siembra** basadas en las tendencias de humedad y temperatura.
- Zonas con mayor **potencial de producción** para cultivos específicos, basándose en análisis históricos y actuales.

**Repositorio del Sistema de Predicción**: [Link al Repositorio de Predicción IA](https://github.com/tu-repositorio-prediccion-ia)





