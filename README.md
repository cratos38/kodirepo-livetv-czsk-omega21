# LiveTV CZ/SK - Kodi Addon

🔵 **For Kodi 20 Nexus and Kodi 21 Omega**

Watch free live TV channels from Czech Republic and Slovakia.

## Version 1.5.2

✅ **All channels working in PVR IPTV Simple Client!**

### What's New in v1.5.2
- Fixed "Codec id 27 require extradata" error
- Uses Freeview method (FFmpeg direct playback)
- All channels now work: JOJ, CS Film, CS History, CS Mystery, Prima, Nova, etc.
- Works with both Kodi Nexus and Omega

## Supported Channels

### Czech Republic 🇨🇿
| Channel | Live | Catchup |
|---------|------|---------|
| ČT1, ČT2, ČT24, ČT Sport, ČT:D/art | ✅ | ⚠️ |
| Prima, Cool, Max, Krimi, Love, Zoom, Star, Show, CNN | ✅ | ⚠️ |
| Nova, Nova Cinema, Nova Action, Nova Gold | ✅ | ❌ |
| Óčko, Óčko Star, Óčko Express | ✅ | ❌ |

### Slovakia 🇸🇰
| Channel | Live | Catchup |
|---------|------|---------|
| STVR Jednotka, Dvojka, :24, Šport | ✅ | ⚠️ |
| JOJ, JOJ Plus, WAU, JOJ Family, JOJ Cinema, JOJ 24 | ✅ | ❌ |
| CS Film, CS History, CS Mystery | ✅ | ❌ |
| TA3 | ✅ | ❌ |
| Markíza, Doma, Dajto | ✅ | ❌ |

⚠️ **Catchup**: Works but with issues (may play wrong program). Will be fixed in future update.

## Installation

### Method 1: Install from Repository (Recommended)

1. Kodi → Settings → File Manager
2. Add source: `https://cratos38.github.io/kodirepo-livetv-czsk-omega21/`
3. Name: `LiveTV CZSK`
4. Kodi → Add-ons → Install from ZIP → Select the repository
5. Kodi → Add-ons → Install from repository → LiveTV CZ/SK Repository
6. Install **LiveTV - CZ/SK**

### Method 2: Direct ZIP Install

1. Download: [plugin.video.livetv.czsk-1.5.2.zip](https://cratos38.github.io/kodirepo-livetv-czsk-omega21/plugin.video.livetv.czsk/plugin.video.livetv.czsk-1.5.2.zip)
2. Kodi → Add-ons → Install from ZIP file
3. Select the downloaded file

## Usage

1. Open **LiveTV CZ/SK** addon
2. Select **Regenerate EPG** (downloads program guide)
3. Select **Export M3U Playlist**
4. Select **Configure PVR Simple Client**
5. Restart Kodi
6. Go to **TV** → Watch channels!

## Technical Notes

This addon uses the "Freeview method" for playback:
- Does NOT use inputstream.adaptive (causes extradata errors in Omega)
- Headers passed in URL with pipe separator: `url|headers`
- FFmpeg handles HLS streams directly
- More reliable playback for all channels

## Credits

- **Author**: cratos38
- **Based on**: freeview.sk by cache-sk
- **Data sources**: iptv-org, iptv-epg.org
- **License**: AGPL-3.0

## Links

- 🏠 [GitHub Repository](https://github.com/cratos38/kodirepo-livetv-czsk-omega21)
- 🐛 [Report Issues](https://github.com/cratos38/kodirepo-livetv-czsk-omega21/issues)
