# NutriBalance

Aplicación web en español para registrar comidas y seguir el balance energético diario con una meta orientada a la recomposición corporal.

## Uso

Abre `index.html` en un navegador. Completa **Mi perfil** para calcular una meta inicial y usa **Añadir comida** para registrar alimentos. Escribe o selecciona un alimento del catálogo y la cantidad en gramos (g), mililitros (ml) o litros (L): la app estima automáticamente calorías, proteínas, carbohidratos y grasas. También puedes corregir los valores manualmente según la etiqueta nutricional. Puedes cambiar de fecha, editar o eliminar registros y anotar vasos de agua.

El calculador incluye alimentos frecuentes con valores nutricionales promedio por 100 g o 100 ml. Las estimaciones pueden variar según la marca, preparación y receta; los alimentos que no están en el catálogo se pueden registrar introduciendo sus datos manualmente.

También puedes seleccionar una foto de la tabla nutricional al añadir una comida. El reconocimiento de texto se ejecuta en el dispositivo y requiere conexión a internet la primera vez para cargar el lector; comprueba los valores reconocidos antes de guardar. Luego se calculan según los gramos o mililitros indicados.

Los datos se guardan en el almacenamiento local del navegador. No se envían a un servidor.

## Objetivos

La estimación usa la ecuación de Mifflin–St Jeor para el metabolismo basal, un factor de actividad para aproximar el gasto total, proteína de 2 g/kg, grasas de 0,8 g/kg y carbohidratos para completar las calorías. Recomposición propone inicialmente un ajuste moderado de -200 kcal frente al gasto estimado. Puedes fijar una meta calórica manual en tu perfil.

Estas cifras son orientativas y no sustituyen una evaluación profesional. La fórmula ofrece una estimación poblacional y puede no ser adecuada para menores de 18 años, embarazo, lactancia o condiciones médicas; en esos casos consulta con un profesional de salud.

## Publicación

El sitio es estático y no requiere dependencias. Para publicarlo con GitHub Pages, abre **Settings → Pages**, selecciona la rama `main` y la carpeta raíz, y guarda.


## Uso en teléfono

El sitio puede instalarse como aplicación en la pantalla de inicio y guarda en caché la interfaz para abrirla sin conexión después de la primera visita. En navegadores compatibles, usa **Instalar** dentro de la app o la opción **Añadir a pantalla de inicio** del menú del navegador. La disponibilidad de instalación depende del navegador y del dispositivo.
