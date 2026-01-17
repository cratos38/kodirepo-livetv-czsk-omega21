# LiveTV CZ/SK - Kodi 21 Omega

🔵 **VERSIÓN PARA KODI 21 OMEGA**

Para Kodi 20 Nexus, usa el repositorio: [kodirepo-livetv-czsk-nexus20](https://github.com/cratos38/kodirepo-livetv-czsk-nexus20)

## Estado

✅ **VERSIÓN 1.5.0** - Funcional con Kodi 21 Omega

### Cambios principales respecto a Nexus (v1.4.23)

- **Nueva API Python**: Usa `InfoTagVideo` en lugar del deprecado `setInfo()`
- **inputstream.adaptive**: Actualizado a versión 21.0.0
- **Compatibilidad**: Código compatible con Kodi 20+ (detección automática de versión)

## Canales Soportados

### República Checa 🇨🇿
| Canal | Live | Catchup |
|-------|------|---------|
| CT1, CT2, CT24, CT Sport, CT:D/art | ✅ | ✅ 7 días |
| Prima, Cool, Max, Krimi, Love, Zoom, Star, Show, CNN | ✅ | ✅ 7 días |
| Nova Cinema | ✅ | ❌ DRM |
| Ocko, Ocko Star, Ocko Express | ✅ | ❌ |

### Eslovaquia 🇸🇰
| Canal | Live | Catchup |
|-------|------|---------|
| STVR Jednotka, Dvojka, Trojka, :24, Sport | ✅ | ✅ ~1200 programas |
| JOJ, Plus, WAU, Family, Cinema, 24 | ✅ | ❌ |
| TA3 | ✅ | ❌ |
| Markiza (requiere cuenta) | ⚠️ | ❌ |

## Instalación

### Método 1: Instalar desde ZIP (Recomendado)

1. Descarga: `plugin.video.livetv.czsk-1.5.0.zip`
2. Kodi → Add-ons → Instalar desde archivo ZIP
3. Selecciona el archivo descargado
4. Sigue las instrucciones en pantalla

### Método 2: Añadir Repositorio

1. Kodi → Configuración → Administrador de archivos
2. Añadir fuente: `https://cratos38.github.io/kodirepo-livetv-czsk-omega21/`
3. Nombre: `LiveTV CZ/SK Omega`
4. Kodi → Add-ons → Instalar desde ZIP → `repository.livetv.czsk-1.1.0.zip`
5. Instalar addon desde el repositorio

## Uso

1. Abre el addon LiveTV CZ/SK
2. **Regenerar EPG** - Descarga la guía de programas
3. **Exportar M3U** - Genera la playlist
4. **Configurar PVR** - Configura PVR IPTV Simple Client
5. Reinicia Kodi
6. Ve a TV → Ver canales

## Catchup (Ver programas pasados)

Para usar catchup:
1. Configura PVR IPTV Simple Client → pestaña Catchup
2. Activa "Override catchup" → Sí
3. Modo Catchup: Separado
4. Fuente de catchup: M3U (si lo soporta)

## Estructura

```
kodirepo-livetv-czsk-omega21/
├── docs/
│   ├── addons.xml
│   ├── addons.xml.md5
│   ├── plugin.video.livetv.czsk/
│   │   ├── addon.xml
│   │   └── plugin.video.livetv.czsk-1.5.0.zip
│   └── repository.livetv.czsk/
│       └── repository.livetv.czsk-1.1.0.zip
└── README.md
```

## Diferencias técnicas Nexus vs Omega

| Característica | Nexus (v1.4.23) | Omega (v1.5.0) |
|---------------|-----------------|----------------|
| API Info | `setInfo('video', {...})` | `InfoTagVideo.setTitle()` |
| inputstream.adaptive | 2.0.0 | 21.0.0 |
| Detección versión | No | Sí |
| Compatibilidad | Kodi 20 | Kodi 20+21 |

## Créditos

- **Autor**: cratos38
- **Basado en**: freeview.sk by cache-sk
- **Fuentes de datos**: iptv-org, iptv-epg.org
- **Licencia**: AGPL-3.0

## Enlaces

- 🏠 [Repositorio GitHub](https://github.com/cratos38/kodirepo-livetv-czsk-omega21)
- 🐛 [Reportar problemas](https://github.com/cratos38/kodirepo-livetv-czsk-omega21/issues)
- 📺 [Versión Nexus](https://github.com/cratos38/kodirepo-livetv-czsk-nexus20)
