<div align="center">

# ¡Hola! Soy Pedro Pablo Rivas Arboleda 
### Desarrollador de Software | Backend (Java & Spring Boot) · Multiplataforma (Flutter Desktop & Mobile) · IoT

 **Buenaventura, Valle del Cauca, Colombia**  
 Estudiante de **Ingeniería de Sistemas** & **Tecnología en Análisis y Desarrollo de Software (ADSO)**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Pedro_Pablo_Rivas_Arboleda-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pedro-pablo-rivas-arboleda-02021a2a5/)
[![Gmail](https://img.shields.io/badge/Contacto-pedropablo200322%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pedropablo200322@gmail.com)
[![Portafolio](https://img.shields.io/badge/Perfil-Ingenier%C3%ADa_de_Software-10B981?style=for-the-badge&logo=github&logoColor=white)](https://github.com/tu-usuario)

</div>

---

##  Sobre Mí

Soy un desarrollador de software apasionado por construir sistemas desde sus cimientos lógicos hasta experiencias de usuario fluidas. Mi enfoque combina la rigurosidad del **desarrollo Backend empresarial (Java & Spring Boot)** con la versatilidad del **desarrollo nativo multiplataforma (Flutter para Windows Desktop y Android)**.

-  Diseño software aplicando **Clean Architecture**, principios **SOLID** y **Programación Orientada a Objetos (POO)**.
-  Creador y autor intelectual de **OmniReader**, un ecosistema multiplataforma de lectura digital con motores propios de descompresión binaria en memoria, persistencia en **SQLite (FFI)** y sincronización **Wi-Fi**.
-  Experiencia integrando **Inteligencia Artificial Generativa (Google Gemini SDK)** en aplicaciones móviles y orquestando hardware físico mediante arquitecturas **IoT (Arduino Mega + ESP32)**.
-  Líder juvenil activo como **Secretario de Asuntos Juveniles en ASOCOMUNAL Buenaventura**, impulsando procesos de articulación comunitaria y formación tecnológica.

---

##  Stack Tecnológico

### **Lenguajes & Frameworks Principales**
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

### **Bases de Datos, IA & Sistemas Embebidos (IoT)**
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite_FFI-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Google Gemini](https://img.shields.io/badge/Google_Gemini_API-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino_Mega-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)

### **Arquitectura, Construcción & Herramientas**
![Maven](https://img.shields.io/badge/Apache_Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)
![PlantUML](https://img.shields.io/badge/PlantUML-F06292?style=for-the-badge&logo=uml&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
[![Antigravity](https://img.shields.io/badge/Antigravity-FF6F61?style=for-the-badge&logo=antigravity&logoColor=white)](https://antigravity.dev)

---

##  Proyectos Destacados de Ingeniería

### 1.  OmniReader — Ecosistema Multiplataforma de Lectura Digital y Gestión de Biblioteca
> **Proyecto Insignia · Autoría y Propiedad Intelectual Propia** | `Windows Desktop (x64)` & `Android`

Aplicación nativa de alto rendimiento diseñada desde cero para la lectura, organización, anotación, análisis estadístico y sincronización inalámbrica de libros electrónicos, novelas ligeras, documentos técnicos, cómics y mangas en formatos **EPUB (v2/v3), PDF, CBZ y CBR (RAR/ZIP)**.

- **Arquitectura Limpia Multiplataforma:** Estructurada bajo **Clean Architecture** y principios **SOLID**, logrando más del **95% de código compartido** entre compilaciones nativas de escritorio (**Windows C++ / CMake**) y dispositivos móviles (**Android**).
- **Motor Propio de Descompresión Binaria (`_Rar29Unpacker`):** Algoritmo escrito en **Dart puro** que decodifica bloques de cabecera RAR (`0x74`), reconstruye **4 árboles de códigos de Huffman** y gestiona una ventana deslizante de **4 MB en memoria RAM** para extraer secuencias de imágenes de archivos `.cbr` sin depender de binarios externos restringidos.
- **Visor Multimodal y Subrayador Propio (`_OmniHighlighterContextMenu`):**
  - *Texto Refluible:* Personalización en vivo de 3 temas (Claro, Sepia, Oscuro), 4 tipografías, márgenes, interlineado y subrayador flotante de 5 colores con salto directo al párrafo exacto vía `GlobalKey`.
  - *Página Fija (Cómics, Mangas y PDF HD):* Vistas de Página Simple, **Doble Página (Spread en PC)**, **Cascada Continua (Webtoon)** y lectura oriental **Manga**, más soporte **Drag & Drop (`DropTarget`)** en escritorio.
- **Persistencia Relacional y Red Local:** Almacenamiento en **SQLite (`sqlite3` FFI nativo)** con registro exacto por coordenada (`lastLocator`), colecciones personalizadas, métricas de lectura, respaldos locales y **sincronización inalámbrica vía Wi-Fi**.

<details>
<summary>🔎 <b>Ver desglose técnico de la arquitectura de OmniReader</b></summary>
<br>

| Módulo / Capa | Implementación Técnica |
| :--- | :--- |
| **Parsers & Motores** | `EpubParser` (XML/OPF v2 y v3), `PdfParser` (renderizado HD con `pdfx`/`pdfium`), `CbzParser` (ZIP) y `_Rar29Unpacker` (RAR v29/v4 en memoria). |
| **Persistencia de Datos** | Base de datos relacional **SQLite3 FFI** para metadatos, progreso por píxel (`lastLocator`), citas subrayadas multicolor y sesiones de lectura. |
| **Interacción & UI** | Menú contextual flotante propio, controles adaptativos para ratón/teclado (efectos *hover*, Drag & Drop) y gestos táctiles en Android. |
| **Conectividad** | Sincronización de biblioteca y progreso en red local mediante transferencia **Wi-Fi** entre PC y móvil. |

</details>

**Stack:** `Flutter` · `Dart` · `SQLite3 FFI` · `C++ / CMake` · `Clean Architecture` · `SOLID` · `Algoritmos de Huffman` · `Wi-Fi Sync`

---

### 2.  Sistema de Gestión para Mantenimiento de Vehículos
> **Backend Empresarial & Arquitectura de Software** | `Java` & `Spring Boot`

Plataforma backend diseñada para administrar y controlar el flujo operativo, historial técnico, órdenes de servicio y programación de mantenimiento vehicular, priorizando la escalabilidad y el bajo acoplamiento.

- **Clean Architecture & SOLID:** Separación estricta entre la lógica de dominio (reglas de negocio), casos de uso e infraestructura para facilitar las pruebas unitarias y la evolución del sistema.
- **Persistencia Relacional:** Diseño e integración de base de datos relacional en **MariaDB**, asegurando integridad referencial y consultas optimizadas para historiales técnicos.
- **Automatización y Gestión:** Configuración modular de dependencias y ciclo de compilación mediante **Apache Maven**.

**Stack:** `Java` · `Spring Boot` · `MariaDB` · `Maven` · `Clean Architecture` · `Principios SOLID`

---

### 3.  Finanzas AI — Asistente Móvil Inteligente de Gestión Financiera
> **Mobile Full-Stack & Inteligencia Artificial Generativa** | `Flutter`, `Firebase` & `Gemini API`

Aplicación móvil multiplataforma que permite a los usuarios registrar sus movimientos económicos diarios y recibir asesoría financiera personalizada en tiempo real impulsada por Inteligencia Artificial.

- **Asesoría con IA Generativa:** Integración directa del **SDK de Google Generative AI (API de Gemini)** para analizar patrones de ingresos/gastos del usuario y generar recomendaciones de ahorro y presupuesto contextualizadas.
- **Backend Serverless en Tiempo Real:** Persistencia de datos en la nube y sincronización de movimientos financieros utilizando **Firebase**.
- **Experiencia de Usuario (UI/UX):** Interfaz limpia, intuitiva y minimalista desarrollada en **Flutter y Dart**, incluyendo diseño de identidad visual propia.

**Stack:** `Flutter` · `Dart` · `Firebase` · `Google Generative AI SDK (Gemini API)`

---

##  Otros Proyectos de Ingeniería, IoT y Arquitectura

| Proyecto | Enfoque | Descripción Técnica | Tecnologías |
| :--- | :--- | :--- | :--- |
| **🚦 Sistema Inteligente de Control Semafórico y Monitoreo Vial** | `IoT` · `Hardware` · `Web` | Intersección vial automatizada a escala ($60 \times 60\text{ cm}$) que sincroniza **8 módulos de semáforo**, sensores y relés mediante una arquitectura distribuida entre un **Arduino Mega** (control físico por cableado UTP) y un **ESP32** conectado a un **Dashboard Web IoT** en tiempo real. | `C++` · `Arduino Mega` · `ESP32` · `Dashboard Web IoT` |
| **🍽️ Smart Meal** | `Arquitectura` · `UML` · `UI` | Especificación de requisitos, diseño de arquitectura de software, modelado de diagramas de clases rigurosos en **PlantUML** bajo **POO** y prototipado de interfaz de usuario para una plataforma gastronómica. | `PlantUML` · `POO` · `Prototipado UI` |
| **💻 La Bestia Definitiva** | `Technical Writing` · `Hardware` | Repositorio de documentación técnica estandarizada en Markdown, análisis de cuellos de botella y matrices comparativas para arquitecturas de hardware de alto rendimiento. | `Markdown` · `GitHub` · `Arquitectura de Hardware` |

---

##  Enfoque de Ingeniería

```text
+-----------------------------------------------------------------------------------+
|                        ARQUITECTURA LIMPIA (CLEAN ARCHITECTURE)                   |
|                                                                                   |
|   [ Presentación / UI ]  --->  Flutter (Windows Desktop & Android) / Web IoT      |
|            |                                                                      |
|   [ Dominio / Reglas  ]  --->  Casos de Uso · Principios SOLID · POO              |
|            |                                                                      |
|   [ Datos / Motores   ]  --->  Spring Boot · SQLite FFI · MariaDB · Firebase      |
|                                Motores Binarios (_Rar29Unpacker) · Gemini AI SDK  |
+-----------------------------------------------------------------------------------+
```

---

##  Contacto y Colaboración

Estoy abierto a oportunidades laborales como **Junior Backend Developer (Java / Spring Boot)**, **Junior Mobile / Multiplatform Developer (Flutter)** o **Software Engineer Junior**, así como a proyectos de innovación tecnológica.

-  **Correo electrónico:** [pedropablo200322@gmail.com](mailto:pedropablo200322@gmail.com)
-  **LinkedIn:** [linkedin.com/in/pedro-pablo-rivas-arboleda](https://www.linkedin.com/in/pedro-pablo-rivas-arboleda-02021a2a5/)
-  **Ubicación:** Buenaventura, Valle del Cauca, Colombia (Disponible para trabajo remoto o presencial/híbrido)

<div align="center">
  <sub><i>"Construyendo software limpio, desde algoritmos binarios en memoria hasta arquitecturas empresariales escalables."</i></sub>
</div>
