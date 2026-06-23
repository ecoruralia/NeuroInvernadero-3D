
# NeuroInvernadero-3D
Simulación y control climático inteligente para agricultura protegida. ![Simulador 3D] 

<img width="800" height="600" alt="invernadero_3d_simulador" src="https://github.com/user-attachments/assets/aaf071b0-acb8-4ad2-b1d3-5c37e1a55686" />

## Descripción del proyecto
NeuroInvernadero 3D es un simulador de invernadero en 3D con un controlador climático inteligente basado en lógica neuro-difusa, lo diseñé cuando estaba terminando mis estudios de ingeniría eléctrica en Cuba en el 2008. Inspirado para implementarlo en la parcela suburbaba a sur de Chile en una empresa amiga. Modelé y entrené este modelo de red neuronal con retropropagación en MATLAB, complementándolo con un Controlador PID Fuzzy para lograr su sintonización y ajuste fino y evitar el "wind-up" en los motores que e acoplan al sistema y modelar y optimizar 8 variables ambientales que usé como entradas al sistema de control neuro-difuso como: temperatura, humedad, presencia de lluvia, velocidad del viento, ventilación, radiación solar, etc. Además acoplé 6 actuadores del sistema (Salidas y perturbaciones del sistema) como: Ventiladores de aire forzado, Nebulizadores, Ventanas cenitales y laterales, etc acoplados a las 6 salidas de la red neuronal difusa y lograr así el equilibrio o control del clima/tempraturas y humedad y sistema de riego automatizado dentro del invernadero respetando los termoperídoso de los culticos de hortalizas/vegetales/frutas de porte pequeño y de temporada en producción agroeclógica dentro del invernadero. El proyecto busca representar el comportamiento del microclima interno de un invernadero y apoyar la toma de decisiones para automatización agrícola y agricultura protegida en zonas rurales. Ahora estoy actualizando el proyecto para Galicia, España, por eso los datos de entrada climáticos los usamos de esta ubicación o zona.

## Objetivos
- Simular el comportamiento climático de un invernadero en un entorno visual 3D con dtos reales en tiempo real.
- Representar el control de variables como temperatura, humedad, ventilación e iluminación.
- Evaluar un enfoque neuro-difuso para la toma de decisiones del sistema (Control de salidas).
- Servir como base para futuras pruebas, validaciones y extensiones en agricultura inteligente en zonas rurales gallegas.

## Funcionalidades
- Simulación visual del invernadero utilizando el lenguaje de programación C++ y otras tecnologías, en lo posible Opensource y sin costos de APIs externas, para mantener uno de los principios que defendemos la "Soberanía Tecnológica".
- Control lógico inteligente sobre variables ambientales.
- Enfoque modular para incorporar nuevas reglas o parámetros.
- Diseño orientado a investigación, demostración y prototipado.

## Desarrollo 
- Crear el repositorio en mi entorno local.
- Revisar los requisitos del proyecto antes de ejecutar la aplicación.
- Configurar el entorno según las dependencias definidas en el repositorio.
- Ejecutar el simulador desde el punto de entrada principal del proyecto.

## Uso
- Abrir el proyecto en mi entorno de desarrollo.
- Configurar los parámetros climáticos o de simulación.
- Ejecutar la visualización 3D (Disponible para todos online).
- Observar la respuesta del controlador neuro-difuso.

# Nota de propiedad intelectual
El proyecto se publica únicamente como descripción funcional y material de presentación. El código fuente, documentos técnicos, estudios internos, circuitos electrónicos que diseñamos, Hardware IoT usado y otros detalles de implementación permanecen protegidos bajo derechos del autor Ing. Ronny Díaz Lópezy y forma parte de su desarrollo profesioal en su proyecto expermental laboratorio "Ecorural IA" y no se comparten en esta descripción.

