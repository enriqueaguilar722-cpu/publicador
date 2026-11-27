# Instrucciones para Claude

## Voz en off (predeterminado)

Cuando se pida una voz en off, narración o locución, usar **VoiceStudio (motor CosyVoice)** en la PC del usuario, con su voz clonada. No usar ElevenLabs ni otro servicio de TTS salvo que el usuario lo pida explícitamente.

Rutas en la PC del usuario (Windows):

- Programa: `C:\Users\henri\AppData\Local\Programs\VoiceStudio\VoiceStudio.exe`
- Voces, perfiles y ajustes: `C:\Users\henri\AppData\Roaming\VoiceStudio`
- Motores (CosyVoice): `C:\Users\henri\AppData\Roaming\OmniVoice\engines`

Notas:

- La PC tiene GPU AMD Radeon (el usuario optimizó con Vulkan), no NVIDIA/CUDA.
- Para llegar a la PC hace falta que el usuario la conecte con Remote Control (app de escritorio de Claude → Settings → Claude Code → Remote Control) y comparta una carpeta de trabajo. Si la PC no está conectada, avisar al usuario y no cambiar a otro servicio de voz sin preguntar.
- Llamar al motor por script (sin la interfaz gráfica) cuando sea posible.
