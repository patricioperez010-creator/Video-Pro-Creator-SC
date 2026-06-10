# 🎥 Video Pro Creator

**Tu director creativo IA premium para generar videos de alta calidad sin censura.**

Aplicación completa construida en **n8n** que transforma ideas simples en **prompts cinematográficos profesionales** y genera videos directamente con **Veo 3.1** (y otros modelos).

![Banner](https://via.placeholder.com/800x400/0A0A0A/D4AF37?text=Video+Pro+Creator)

## ✨ Características

- **4 modos completos**:
  - 📝 **Texto → Video** (flujo paso a paso premium: Personaje → Ambientación → Iluminación → Estilo)
  - 🖼️ **Imagen → Video** (Image-to-Video)
  - 🖼️ **Texto → Imagen** (Text-to-Image con Flux)
  - ⚡ **Texto → Video Directo**

- Interfaz elegante y minimalista (HTML premium embebido)
- Todo el output en **español de España**
- Enriquecimiento automático de prompts por IA (nivel director de cine)
- Generación directa de video con Veo 3.1
- Sin formularios largos ni pasos innecesarios
- Totalmente **sin censura**
- Listo para producción

## 🚀 Instalación y Despliegue (En minutos)

### 1. Importar el Workflow
1. Abre tu instancia de **n8n** (local, Docker o n8n.cloud)
2. Ve a **Workflows → Import from Clipboard**
3. Pega el JSON del workflow (`workflow-video-pro-creator.json`)
4. Guarda y activa

### 2. Configurar Credenciales
- **OpenAI** (o Grok/Claude) → Para el enriquecimiento de prompts
- **fal.ai** o **Wavespeed** → Para Veo 3.1 (recomendado)
- (Opcional) Google Vertex AI para Veo oficial

### 3. Activar Webhook
- Activa el workflow
- Copia la **URL del Webhook**
- Ábrela en tu navegador → ¡Tu app ya está en línea!

### Despliegue Recomendado
- **n8n.cloud** (más fácil)
- **Docker** + Railway / Render / Coolify
- Dominio propio con HTTPS

## 📁 Estructura del Repositorio
