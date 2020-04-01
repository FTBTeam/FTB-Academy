FTB Academy

Issues with the modpack as a whole should go in the [Issues page](https://github.com/FTBTeam/FTB-Academy/issues).

Translators can submit Pull Requests [here](https://github.com/FTBTeam/FTB-Academy/pulls).

To translate the quests, make a new lang file in the format of your language (Spanish would be `es_es.lang`, for instance), copy the contents of en_us.lang, and translate it to language. Lang files are in `/resources/assets/lang/`

The guide is a bit more involved to translate, as it doesn't use language keys. Copy the entire `/config/ftbguides/modpack_guide/` folder and rename it, adding the language to the end (so for Russian, it would be `/modpack_guide_ru_ru/`). Missing files will default to the regular `modpack_guide` folder, which means you can delete images from the translated folder safely (unless you want to retake them to translate any text it has in it). To rename pages, open up the `index.json`s and translate the text labeled `title` **only**. Leave the `id`s and folders the way they are now, they won't be seen by the player. The meat of the guide is in the `README.md` files; translate them however you want, just try to keep them similar to the English versions.
