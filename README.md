💱 Conversor de Monedas en Java

Este proyecto es un Conversor de Monedas desarrollado en Java, como parte del Challenge ONE – Oracle Next Education / Alura Latam.

La aplicación permite convertir valores entre diferentes monedas utilizando tasas de cambio en tiempo real, consumiendo una API externa y aplicando los principios de la Programación Orientada a Objetos (POO).

📌 Descripción del Proyecto

El Conversor de Monedas es una aplicación de consola que interactúa con el usuario a través de un menú, permitiéndole seleccionar el tipo de conversión deseada e ingresar un valor para obtener el resultado convertido.

El sistema consume datos de una API de tasas de cambio, procesa la información en formato JSON y realiza las conversiones de manera precisa y eficiente.

Este proyecto fue desarrollado con el objetivo de consolidar conocimientos en Java Back-End, buenas prácticas de programación y consumo de APIs.

🚀 Funcionalidades

Menú interactivo por consola

Conversión entre las siguientes monedas:

Dólar (USD) → Peso Argentino (ARS)

Peso Argentino (ARS) → Dólar (USD)

Dólar (USD) → Real Brasileño (BRL)

Real Brasileño (BRL) → Dólar (USD)

Dólar (USD) → Peso Colombiano (COP)

Peso Colombiano (COP) → Dólar (USD)

Consumo de API externa con tasas de cambio actualizadas

Manejo de errores y validaciones de entrada

Arquitectura organizada siguiendo principios de POO

Código limpio, modular y reutilizable

🛠️ Tecnologías Utilizadas

Java 17

IntelliJ IDEA

Exchange Rate API

Gson

Git & GitHub

📦 Estructura del Proyecto
src
└── main
    └── java
        └── com.alura.conversor
            ├── api
            │   └── ExchangeRateClient.java
            ├── modelo
            │   └── ExchangeRateResponse.java
            ├── util
            │   └── ConversorService.java
            └── principal
                └── Principal.java

🔑 API Utilizada

Exchange Rate API
Proporciona tasas de cambio en tiempo real de forma gratuita y sencilla de implementar.

Ejemplo de endpoint utilizado:

https://v6.exchangerate-api.com/v6/API_KEY/latest/USD

▶️ Cómo Ejecutar el Proyecto

Clona este repositorio:

git clone https://github.com/carlostabordayaho-gif/conversor-monedas-java.git

Abre el proyecto en IntelliJ IDEA

Asegúrate de tener Java 17 o superior

Ejecuta la clase:

Principal.java


Sigue las instrucciones del menú en la consola

🧠 Conceptos Aplicados

Programación Orientada a Objetos (POO)

Consumo de APIs REST con HttpClient

Manejo de JSON con Gson

Uso de records

Manejo de excepciones

Separación de responsabilidades

Clean Code

Control de flujo y estructuras de control

📌 Posibles Mejoras (Extras)

Uso de enum para las monedas

Formateo de valores monetarios

Historial de conversiones

Persistencia en archivos

Interfaz gráfica

👤 Autor

Carlos Taborda
Estudiante de Back-End Java – Oracle Next Education / Alura Latam

🌐 Redes Profesionales

Este proyecto forma parte de mi portafolio y fue compartido en LinkedIn como evidencia de aprendizaje y desarrollo profesional.

🏆 Challenge ONE – Oracle Next Education

Proyecto desarrollado como parte del programa Oracle Next Education (ONE) en colaboración con Alura Latam, enfocado en la formación de desarrolladores Back-End con Java.
