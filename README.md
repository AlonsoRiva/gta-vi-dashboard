<div align="center">

# 🌴 GTA VI · Señales desde Vice City
### Desafío de Visualización de Datos · ADY1104

*Dashboard ejecutivo para Rockstar · Infografía · Defensa de 5 minutos*

</div>

| | |
|---|---|
| **Integrantes** | (completar con los nombres del equipo) |
| **Herramienta** | Dashboard propio en HTML y JavaScript (un solo archivo, se abre en cualquier navegador). Infografía en PDF. |
| **Pregunta ejecutiva** | ¿Qué debe priorizar Rockstar al comunicar GTA VI según los comentarios analizados? |

---

## 🎯 Hallazgo principal
Las reacciones a los tres videos son mayormente neutrales (84,5 %). La crítica se concentra en **plataformas y rendimiento**: 6 de 30 comentarios del tema son negativos (**20 %**), frente a 5,2 % en toda la muestra (23 de 439). Es **3,8 veces** el promedio.
Tráiler y personajes concentran el 36 % de los comentarios, con 1 negativo entre 159.

## ✅ Decisión y comprobación
| | |
|---|---|
| **Decisión a evaluar** | Una pieza piloto que aclare plataformas y rendimiento, sin cambiar el resto de la estrategia. |
| **Comprobación** | Medir el % de negativos del tema en videos nuevos, con etiquetas validadas por personas y al menos 100 comentarios del tema. |

## 📁 Contenido de la carpeta
| Archivo | Qué es |
|---|---|
| `dashboard/dashboard_gta_vi.html` | Tres vistas: Resumen ejecutivo, Temas y comparaciones, Evidencia y calidad. Estética de Vice City, modo claro y oscuro, funciona en móvil. |
| `infografia/infografia_equipo.pdf` | Infografía ejecutiva de una página con la idea principal. |
| `data/GTA_VI_Datos_Visualizacion.xlsx` | Copia del dataset utilizado (439 comentarios anonimizados). |

## 🔎 Filtros del dashboard
Video, sentimiento y tema principal. Se aplican a las tres vistas. Un clic en un tema de la vista 2 abre sus comentarios en la vista 3, que además tiene búsqueda de texto.

## 🎨 Decisiones visuales
- **Composición:** dona de sentimiento con leyenda. **Comparación:** barras de % negativo por tema, ordenadas y con base cero.
- El sentimiento usa los colores del catálogo del dataset y además símbolos (▲ ● ▼) y texto, así el color no es el único medio.
- Se usan porcentajes porque los videos tienen 263, 52 y 124 comentarios.
- Barras rayadas y el símbolo ⚠ marcan temas con menos de 20 comentarios.

## ⚠️ Limitaciones
- El sentimiento es una propuesta asistida, sin validación humana definitiva.
- El tema se asignó por palabras clave. “Otros temas” agrupa el 32,6 % y varios comentarios sobre retrasos quedaron ahí.
- Muestra de tres videos: son reacciones a videos, no experiencia real de juego, y no representan a toda la comunidad.
- Plataformas y rendimiento tiene solo 30 comentarios (6 negativos y 6 positivos). La lectura es preliminar y no establece causas.
- Los temas con menos de 20 comentarios no se usan como base de la conclusión.
