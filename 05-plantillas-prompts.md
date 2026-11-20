# Plantillas de prompts reutilizables

Esta sección reúne estructuras que el alumnado puede adaptar durante los ejercicios.

## 1. Prompt básico con contexto

```text
Actúa como [rol o perspectiva útil].
Quiero conseguir [objetivo concreto].
Contexto: [situación, destinatarios y datos relevantes].
Restricciones: [tiempo, presupuesto, nivel, preferencias].
Formato de salida: [tabla, lista, esquema, texto].
Si falta información importante, indícalo; no inventes datos.
```

## 2. Mejorar una respuesta

```text
Revisa tu respuesta anterior.
Mantén [lo que me interesa conservar].
Cambia [lo que quiero mejorar].
Añade [detalle o restricción nueva].
Explícame brevemente qué has cambiado.
```

## 3. Aprender paso a paso

```text
Explícame [tema] para alguien con nivel [inicial/intermedio].
Incluye un ejemplo cotidiano.
Después, hazme una pregunta cada vez y espera mi respuesta.
Corrige mis errores y adapta la dificultad.
```

## 4. Analizar un documento sin inventar

```text
Analiza el documento adjunto.
Distingue:
1. Información que aparece expresamente en el documento.
2. Interpretaciones o inferencias.
3. Puntos que no se pueden confirmar.
Resume las acciones pendientes e indica dónde se mencionan, si es posible.
```

## 5. Comparar alternativas

```text
Compara [opciones] según [criterios].
Mi presupuesto o límite es [valor].
Presenta ventajas, inconvenientes y dudas en una tabla.
No inventes precios ni disponibilidad; distingue lo comprobado de lo estimado.
```

## 6. Crear una infografía

```text
Crea una infografía [horizontal/vertical] sobre [tema].
Público: [destinatarios].
Incluye [número] ideas clave.
Estilo visual: [descripción precisa].
Usa textos breves, títulos claros y elementos visuales legibles.
```

### Estilos definidos en este curso

- **`/apuntes`**: infografía con apariencia de apuntes manuscritos sobre papel blanco cuadriculado, bolígrafos de colores y composición didáctica.
- **`/pizarra-beltza`**: infografía con fondo de pizarra negra, textos manuscritos con tizas de colores y dibujos sencillos.

Estas etiquetas funcionan como **atajos descriptivos del material didáctico**: no son comandos nativos universales. Si no hay instrucciones personalizadas asociadas, incluye la descripción del estilo en el prompt.

## 7. Extraer acuerdos de una reunión

```text
A partir de esta transcripción, crea un acta.
Separa temas tratados, decisiones confirmadas, tareas, responsables y plazos.
Para cualquier dato ausente, escribe «No consta».
No conviertas opiniones o propuestas en decisiones aprobadas.
```

## 8. Solicitar una automatización

```text
Quiero un recordatorio con el título [nombre].
Frecuencia: [diaria/semanal/mensual].
Día y hora: [dato y zona horaria].
Mensaje: [contenido del recordatorio].
Confírmame si la tarea se ha creado realmente o si solo has preparado la solicitud.
```
