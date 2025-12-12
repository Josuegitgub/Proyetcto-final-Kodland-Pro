# 🌱 EcoBot: Tu Amigo Ambiental en Discord

![EcoBot Banner](https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif)

¡Hola! Soy **EcoBot**, un asistente ambiental para Discord que combina educación y entretenimiento para ayudarte a cuidar nuestro planeta. No soy solo un bot de consejos aleatorios, ¡soy tu compañero en la lucha contra el cambio climático! 💚

## 🚀 Sobre el Proyecto

EcoBot nació como un proyecto educativo para proporcionar información ambiental de manera accesible y divertida.
Combinando:
- **Consejos prácticos** basados en fuentes científicas
- **Inteligencia artificial** para respuestas personalizadas
- **Contenido interactivo** con GIFs y memes
- **Recursos verificados** de instituciones como Naciones Unidas

¡Más de **120 consejos ecológicos** organizados en 6 categorías fundamentales para un impacto real!

## ✨ Características Principales

### 📚 Consejos Especializados por Categoría
- 💧 **Agua**: 20 consejos prácticos para ahorrar y proteger el agua
- 🌳 **Tierra**: 20 técnicas para cuidar el suelo y prevenir la erosión
- 🌬️ **Aire**: 20 hábitos para mejorar la calidad del aire en interiores y exteriores
- ⚡ **Energía**: 20 estrategias para reducir consumo energético
- ♻️ **Residuos**: 20 métodos para reducir, reutilizar y reciclar
- 🦋 **Biodiversidad**: 20 acciones para proteger la flora y fauna

### 🤖 Inteligencia Artificial Integrada
- Respuestas personalizadas usando **Google Gemini API**
- Asistente conversacional que entiende consultas complejas
- Tonos amigables con emojis y lenguaje natural

### 🎮 Experiencia de Usuario Dinámica
- **GIFs de saludo** aleatorios para una mejor experiencia
- **Sistema interactivo** que pregunta si quieres más información
- **Memes educativos** sobre cambio climático para romper la tensión
- **Enlaces a artículos** de fuentes confiables

## ⚙️ Requisitos Técnicos

### **Python:** 
- Versión 3.8 o superior (recomendado 3.10+)

### **Librerías Necesarias:**
```bash
pip install discord.py google-generativeai
```

### **Credenciales Externas:**
- **Token de Discord Bot** (desde [Discord Developer Portal](https://discord.com/developers/applications))
- **API Key de Google Gemini** (desde [Google AI Studio](https://makersuite.google.com/))

## 🛠️ Instalación Paso a Paso

1. **Clona el repositorio:**
```bash
git clone https://github.com/JosueXT/Eco-Bot.git
cd Eco-Bot
```

2. **Instala las dependencias:**
```bash
pip install discord.py google-generativeai
```

3. **Configura tus credenciales:**
   - Abre el archivo `bot.py`
   - Busca la línea: `genai.configure(api_key="TU_API_KEY_DE_GOOGLE_AQUI")`
   - Reemplaza `"TU_API_KEY_DE_GOOGLE_AQUI"` con tu API Key real de Google Gemini
   - Busca la línea: `client.run("TOKEN_DE_TU_BOT_AQUI")`
   - Reemplaza `"TOKEN_DE_TU_BOT_AQUI"` con tu token real de Discord Bot

4. **Ejecuta el bot:**
```bash
python bot.py
```

> **⚠️ Importante:** Nunca compartas tus tokens o claves API.

## 📋 Comandos Disponibles

| Comando | Descripción | Ejemplo |
|---------|-------------|---------|
| **`$comandos`** | 📋 Muestra todos los comandos disponibles | `$comandos` |
| **`$hola`** | 👋 Te saluda con un GIF aleatorio | `$hola` |
| **`$cuidar_agua`** | 💧 Consejo aleatorio para ahorrar agua | `$cuidar_agua` |
| **`$cuidar_tierra`** | 🌳 Consejo para proteger el suelo | `$cuidar_tierra` |
| **`$cuidar_aire`** | 🌬️ Consejo para mejorar calidad del aire | `$cuidar_aire` |
| **`$cuidar_energia`** | ⚡ Consejo para ahorrar energía | `$cuidar_energia` |
| **`$cuidar_residuos`** | ♻️ Consejo para gestión de residuos | `$cuidar_residuos` |
| **`$cuidar_biodiversidad`** | 🦋 Consejo para proteger biodiversidad | `$cuidar_biodiversidad` |
| **`$memes`** | 😂 Meme aleatorio sobre cambio climático | `$memes` |

✨ **¡Cualquier otro mensaje!** - EcoBot usará IA para responderte como un amigo ambiental.

## 🔗 Recursos Oficiales

- **[Agua - ONU](https://www.un.org/es/climatechange/science/climate-issues/water)**
- **[Tierra - Foro Económico Mundial](https://es.weforum.org/stories/2024/12/por-que-la-salud-del-suelo-es-esencial-para-combatir-el-cambio-climatico/)**
- **[Aire - Fundación Aquae](https://www.fundacionaquae.org/wiki/106-consejos-para-reducir-la-contaminacion-del-aire/)**
- **[Energía - Instituto del Agua](https://institutodelagua.es/cambio-climatico/energia-y-cambio-climaticocambio-climatico/)**
- **[Residuos - Formae Activa](https://formaeactiva.com/reduccion-de-residuos-claves-para-un-futuro-sostenible/)**
- **[Biodiversidad - ONU](https://www.un.org/es/climatechange/science/climate-issues/biodiversity)**

## 🤝 Cómo Contribuir

¡Las contribuciones son bienvenidas! Puedes:
- ✨ Añadir nuevos consejos a los diccionarios
- 🎨 Proponer nuevos GIFs o memes educativos
- 🤖 Mejorar las respuestas de la IA con mejores prompts
- 🌐 Traducir el bot a otros idiomas
- 🔒 Mejorar la seguridad del manejo de tokens

1. Haz un fork del repositorio
2. Crea tu rama de características (`git checkout -b feature/nueva-funcionalidad`)
3. Haz commit de tus cambios (`git commit -am 'Añade nueva funcionalidad'`)
4. Sube tu rama (`git push origin feature/nueva-funcionalidad`)
5. Abre un Pull Request

## 📜 Licencia

Este proyecto está bajo la licencia **MIT License** - ver el archivo [LICENSE](LICENSE) para más detalles.

## 💡 Soporte

¿Tienes problemas o ideas? ¡Contáctame!
- **GitHub Issues**: [Abrir un issue](https://github.com/JosueXT/Eco-Bot/issues)
- **Email**: Josuedev08@gmail.com

---

**¡Gracias por ayudar a cuidar nuestro planeta!** 🌍✨  
*Hecho con ❤️ y Python por JosueXT*
