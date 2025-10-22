# Ciudad Viva BCN

## Objetivo del proyecto

Este proyecto tiene como finalidad ofrecer una herramienta interactiva para entender el impacto del turismo en los barrios de Barcelona. Permite a los usuarios decidir dónde vivir o qué zonas evitar según la saturación turística, mediante mapas, rankings y recomendaciones de pisos.

## Descripción 

Permite explorar el impacto del turismo en Barcelona mediante:

Mapas interactivos con información sobre viviendas de uso turístico (HUTs).

Ranking de barrios más tranquilos y más saturados.

Recomendaciones personalizadas de pisos.

Chatbot que responde dudas sobre la vivienda y la saturación turística.

Diseño responsive y moderno con Tailwind CSS y Framer Motion.

# Capturas de pantalla

Página principal
<p align="center"> <img src="https://github.com/user-attachments/assets/216820ce-5ac6-4299-a3e4-e1af64634824" alt="Home Screenshot" width="500" /> </p>

Chat Bot <br>
<p align="center"> <img src="https://github.com/user-attachments/assets/940c30fb-6e4d-41d3-80b3-07f73310bfbd" alt="Chat Bot Screenshot" width="300" /> </p>

Mapa (path "/mapa")
<p align="center"> <img src="https://github.com/user-attachments/assets/cfb7fafe-3163-4f7f-af3d-92fbf2fd949b" alt="Mapa Screenshot" width="600" /> </p>

Recomendación (path "recomendaciones")
<p align="center"> <img src="https://github.com/user-attachments/assets/137a809c-fc60-49bb-9233-3a18267a4cf8" alt="Recomendaciones Screenshot" width="500" /> </p>

Ranking (path"/ranking")
<p align="center"> <img src="https://github.com/user-attachments/assets/a6ef1eb7-5faf-422b-bd48-a23e95708b7c" alt="Ranking Screenshot" width="600" /> </p>

# Frontend de Hackaton

## Instalación y despliegue
Clonar el repositorio:

git clone https://github.com/HackatonServeiOcupacio2025/Hackaton.git
cd Hackaton

Instalar dependencias:
npm install

Iniciar la aplicación en modo desarrollo:
npm run dev

Luego abre en tu navegador:
👉 http://localhost:5173


## Tecnologías

React 19, React Router DOM

Estilos	Tailwind CSS, Framer Motion

Mapas	Mapbox GL, Leaflet, React Leaflet, Leaflet.Heat

Interactividad	React Chatbotify

Gestión y Build	Vite

Control de versiones	Git y GitHub

# Backend de Hackaton

## API para el Hackaton de Servicios de Ocupación 2025

La API conecta con las bases de datos de opendata de Barcelona para recoger y gestionar los datos necesarios.

## Puntos finales
OBTENER /api/pisosFull
Devuelve un listado con todos los pisos turísticos de Barcelona

OBTENER /api/pisos
Devuelve un listado reducido de los pisos turísticos de Barcelona.

OBTENER /api/pisosDiez
Devuelve un listado con 10 pisos turísticos de cada Distrito de Barcelona

OBTENER /api/puntosDeInteres
Devuelve un listado con puntos turísticos

POST /api/suscribirse
Almacena el email del usuario para contactar con el

## Iniciar
npm i
inicio de npm


## Equipo

¿Tienes dudas o quieres saber más sobre el proyecto?

Puedes contactar a las desarrolladoras a través de sus perfiles profesionales:

<table style="width:100%; border-collapse: collapse; border: none; text-align:center;">
  <tr>
    <td style="border: none; padding: 10px;">
      <b>Ana Aguilera</b><br>
      <a href="https://www.linkedin.com/in/ana-aguilera-morales/">LinkedIn</a> |
      <a href="https://github.com/AnaAguileraMorales88" target="_blank">GitHub</a>
    </td>
    <td style="border: none; padding: 10px;">
      <b>Sergi Diaz Lopez</b><br>
      <a href="https://www.linkedin.com/in/sergi-diaz-lopez/">LinkedIn</a> |
      <a href="https://github.com/sergidl">GitHub</a>
    </td>
        <td style="border: none; padding: 10px;">
      <b>Montse Muñoz </b><br>
      <a href="https://www.linkedin.com/in/montserrat-munoz-cabrera-ba202b227/">LinkedIn</a> |
      <a href="https://github.com/Montc027">GitHub</a>
    </td>
        <td style="border: none; padding: 10px;">
      <b>Alejandro Diaz</b><br>
      <a href="https://www.linkedin.com/in/alejandro-diaz-corredera/">LinkedIn</a> |
      <a href="https://github.com/sixfantasy">GitHub</a>
    </td>
        <td style="border: none; padding: 10px;">
      <b>Mio Ogura</b><br>
      <a href="https://www.linkedin.com/in/mio-ogura/">LinkedIn</a> |
      <a href="https://github.com/miaryl">GitHub</a>
    </td>
        <td style="border: none; padding: 10px;">
      <b>Cristian Miguel Bo</b><br>
      <a href="https://www.linkedin.com/in/cristian-miguel-bo-88784223a">LinkedIn</a> |
      <a href="https://github.com/CristianMiguelBo">GitHub</a>
    </td>

  </tr>
</table>








