{
  "manifest_version": 3,
  "name": "Forsaken Guest Mod",
  "version": "1.0",
  "description": "Un mod personalizado de Forsaken Guest con animaciones de inicio, sonidos y badges.",
  "developer": {
    "name": "Kolya"
  },
  "icons": {
    "512": "icons/mod_icon.png"
  },
  "mod": {
    "license": "CC-BY-4.0",
    "payload": {
      "theme": {
        "dark": {
          "images": {
            "theme_bg": "wallpapers/background.png"
          },
          "colors": {
            "frame": [15, 15, 15],
            "toolbar": [35, 35, 35],
            "accent": [235, 10, 10],
            "content_background": [20, 20, 20]
          }
        }
      },
      "sounds": {
        "keyboard": {
          "click": "sounds/typing.wav"
        },
        "browser": {
          "click": "sounds/click.wav",
          "tab_open": "sounds/click.wav",
          "tab_close": "sounds/click.wav"
        }
      },
      "startup": {
        "video": "video/startup_animation.mp4",
        "sound": "sounds/startup_sound.wav"
      }
    }
  }
}
