# Документация Kool Tech Tricks

Подробная информация про [Kool Tech Tricks](https://kooltechtricks.org).

Сайт сделан на [Hugo](https://gohugo.io) с использованием темы [Hextra].

## Локальный запуск

Для начала вам понадобится установить следующее программное обеспечение:

- [Git](https://git-scm.com/downloads)
- [Hugo](https://gohugo.io/installation) v0.162.0 или выше
- [Codebook](https://github.com/blopker/codebook#readme) v0.3.42 или выше (для проверки орфографии)

Далее используйте эти команды:

```sh
git clone --recursive https://github.com/KoolTechTricks/docs.kooltechtricks.org
cd docs.kooltechtricks.org
hugo server -D -O  # -O, чтобы открыть в браузере

# Codebook (CLI)
codebook-lsp lint --unique . # Проверка орфографии
codebook-lsp add <WORDS>... # Добавить слова
```

Когда сервер Hugo запущен, вы можете открыть страницу `http://localhost:1313` в
браузере. Содержимое будет обновляться автоматически по мере редактирования.

## Лицензия

Содержимое документации Kool Tech Tricks доступно по лицензии [CC BY-SA 4.0].

Сайт построен на теме [Hextra]. Лицензия: MIT.

[CC BY-SA 4.0]: https://creativecommons.org/licenses/by-sa/4.0
[Hextra]: https://imfing.github.io/hextra
