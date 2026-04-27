# Estado de Lotes Interactivo

Visualizador web interactivo para consultar el estado de lotes en un desarrollo inmobiliario.  
Este proyecto es una mejora sobre una versión anterior, incorporando retoques visuales, optimizaciones y una mejor experiencia de usuario.

## 🚀 Demo

🔗 Ver online: https://estadolotes.vercel.app/ 

## 📌 Descripción

La aplicación muestra un plano interactivo en formato SVG donde cada lote cambia de color según su estado actual:

- 🟢 Disponible  
- 🟡 Reservado  
- 🔴 Vendido  
- ⚫ No Disponible  
- 🔴 Desarrollador  

Además, al pasar el mouse sobre cada lote se visualiza información detallada como:

- Número de lote  
- Superficie  
- Calado  
- Metros de costa  
- Estado  
- Valor (si está disponible)  
- Financiación disponible  

## ⚙️ Tecnologías utilizadas

- HTML5  
- CSS3  
- JavaScript Vanilla  
- SVG interactivo  
- Google Sheets API (fuente dinámica de datos)

## ✨ Mejoras realizadas

- Loader de carga mientras se obtienen datos  
- Tooltip dinámico que sigue al cursor  
- Mejoras visuales en hover de lotes  
- Limpieza y ajustes de estilos  
- Mejor organización del código JavaScript  
- Datos conectados en tiempo real desde Google Sheets  

## 📂 Funcionamiento

1. La web consulta una hoja de cálculo mediante Google Sheets API.
2. Obtiene el estado de cada lote.
3. Colorea automáticamente cada parcela en el mapa.
4. Al posicionar el cursor sobre un lote, muestra su información.

## 🛠️ Posibles mejoras futuras

- Responsive para mobile  
- Filtros por estado  
- Buscador de lote por número  
- Panel administrativo  
- Animaciones más avanzadas  
