# Fashionscape Data

Cache-derived data for the [fashionscape RuneLite plugin](https://github.com/equirs/fashionscape-plugin). The plugin
requests these json files from the master branch at startup (in dev mode, it points to the dev branch instead).

Data for colors and slots are dumped from my [RuneLite fork](https://github.com/equirs/runelite/tree/dump-model),
specifically `ItemSlotDumper` and `ColorDataDumper`. These work similarly to other cache dump utils.

Data for animations and miscellaneous info are all updated manually. I just run the fashionscape plugin in dev mode
since it contains some utilities that help with this, mainly the "Players" dev tool and the plugin's "secret" animations
tab. 
