# Cosmic App Library (WIP Pre-Alpha)

Layer Shell App Library application.

# Building

Cosmic App Library is set up to build a deb and a Nix flake, but it can be built using meson.

Some Build Dependencies:
```  
  cargo,
  meson,
  intltool,
  appstream-util,
  desktop-file-utils,
  libxkbcommon-dev,
  pkg-config,
  desktop-file-utils,
```


# Translators

Translation files may be found in the i18n directory. New translations may copy the English (en) localization of the project and rename `en` to the desired [ISO 639-1 language code](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes). Translations may be submitted through GitHub as an issue or pull request. Submissions by email or other means are also acceptable; with the preferred name and email to associate with the changes.