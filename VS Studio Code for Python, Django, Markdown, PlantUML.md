
## Расширения и общие настройки

### Установленные расширения

Этот пакет расширений делает VS Studio Code возможно даже чуть лучше, чем профессиональное издание PyCharm.

Однако стоит помнить, что PyCharm как Macbook - все вылизано, код, аппаратная часть. Но за это надо платить.  

VS Studio Code - как Linux. Надо с ним повозится.         

Вот полный перечень плагинов, которые стоят у меня, на текущий момент:  

| №   | Название Расширения                          | Автор              | Описание                                                                                                                                                    | Комментарии                                                 |
| --- | -------------------------------------------- | ------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------- |
| 1   | SQLTools SQLite                              | Matheus Teixeira   | Расширение для работы с базами данных SQLite в VS Code.                                                                                                     | Работает хорошо с другими SQLTools расширениями.            |
| 2   | Pylance                                      | Microsoft          | Сервер языка для Python, предоставляющий информацию для IntelliSense.                                                                                       | Совместимо с расширениями Python от Microsoft.              |
| 3   | Pylint                                       | Microsoft          | Поддержка линтинга для файлов Python с использованием Pylint.                                                                                               | Может конфликтовать с другими линтерами.                    |
| 4   | Python                                       | Microsoft          | Поддержка языка Python, включая IntelliSense и отладку.                                                                                                     | Основное расширение для работы с Python.                    |
| 5   | Python Debugger                              | Microsoft          | Расширение для отладки Python с использованием debugpy.                                                                                                     | Интегрируется с основным расширением Python.                |
| 6   | Python Environment Manager                   | Don Jayamanne      | Управление Python окружениями и пакетами.                                                                                                                   | Полезно для управления зависимостями проекта.               |
| 7   | Russian Language Pack for Visual Studio Code | Microsoft          | Пакет локализации для VS Code на русском языке.                                                                                                             | Улучшает UX для русскоговорящих пользователей.              |
| 8   | SQLTools                                     | Matheus Teixeira   | Расширение для подключения к различным базам данных.                                                                                                        | ==Требует установки Node JS==                               |
| 9   | SQLTools MySQL/MariaDB/TiDB                  | Matheus Teixeira   | Расширение для работы с MySQL/MariaDB/TiDB.                                                                                                                 | Нужно для работы с этими конкретными СУБД.                  |
| 10  | SQLTools PostgreSQL/Cockroach Driver         | Matheus Teixeira   | Драйвер для работы с PostgreSQL и CockroachDB.                                                                                                              | Идеально подходит для пользователей этих СУБД.              |
| 11  | IntelliCode API Usage Examples               | Microsoft          | Предлагает примеры кода для различных API на GitHub.                                                                                                        | Ускоряет разработку благодаря доступным примерам.           |
| 12  | IntelliSense for CSS class names in HTML     | Zignd              | Автодополнение имен классов CSS в HTML.                                                                                                                     | Улучшает скорость написания и точность кода.                |
| 13  | Live Server                                  | Ritwick Dey        | Локальный сервер для разработки с функцией live reload.                                                                                                     | Незаменим для тестирования фронтенда.                       |
| 14  | Markdown All in One                          | Yu Zhang           | Все необходимое для работы с Markdown, включая ярлыки и предпросмотр.                                                                                       | Упрощает работу с Markdown файлами.                         |
| 15  | Markdown Preview Enhanced                    | Yiyi Wang          | Улучшенный предпросмотр Markdown файлов.                                                                                                                    | Дополнение к Markdown All in One для лучшего предпросмотра. |
| 16  | Dracula Official                             | draculatheme.com   | Тема оформления VS Code.                                                                                                                                    | Популярная тема оформления                                  |
| 17  | Path Intellisense                            | Christian Kohler   | Автодополнение путей к файлам в VS Code.                                                                                                                    | Облегчает навигацию по проекту.                             |
| 18  | PlantUML                                     | jebbs              | Поддержка языка PlantUML для создания диаграмм.                                                                                                             | Важно для визуализации архитектуры систем.                  |
| 19  | Prettier - Code formatter                    | N/A                | Форматирование кода с использованием Prettier.                                                                                                              | Стандарт де-факто для форматирования во многих проектах.    |
| 20  | Auto Rename Tag                              | Jun Han            | Автоматическое переименование парных HTML/XML тегов.                                                                                                        | Снижает риск ошибок при редактировании кода.                |
| 21  | Black Formatter                              | Microsoft          | Поддержка форматирования Python файлов с использованием Black.                                                                                              | Предпочтительный форматтер для многих Python разработчиков. |
| 22  | CSS Peek                                     | Pranay Prakash     | Предоставляет возможность просмотра определений CSS ID и классов.                                                                                           | Упрощает редактирование CSS.                                |
| 23  | Django                                       | Baptiste Darthenay | Сниппеты и синтаксис для работы с Django.                                                                                                                   | Необходим для разработчиков Django.                         |
| 24  | GitHub Copilot                               | GitHub             | Искусственный интеллект для подсказки кода.                                                                                                                 | Может генерировать код на основе комментариев.              |
| 25  | GitHub Copilot Chat                          | GitHub             | Функции чата, управляемые GitHub Copilot.                                                                                                                   | Позволяет общаться с Copilot в процессе кодирования.        |
| 26  | GitLens — Git supercharged                   | GitKraken          | Улучшенная работа с Git в VS Code.                                                                                                                          | Отличный инструмент для визуализации истории Git.           |
| 27  | IntelliCode                                  | Microsoft          | AI-поддержка разработки, включая автодополнение.                                                                                                            | Интегрируется с многими другими расширениями Microsoft.     |
| 28  | Auto Close Tag                               | Jun Han            | Автоматическое закрытие тегов при написании кода, что позволяет разработчикам экономить время и уменьшать количество ошибок при вводе.                      | Снижает риск ошибок                                         |
| 29  | Microsoft Edge Tools for VS Code             | Microsoft          | Плагин для  разработки веб-приложений, который позволяет интегрировать функции браузера Microsoft Edge прямо в среду ра Предпросмотр и дебаггер JS HTML CSS |                                                             |
| 30  | Todo Tree                                    | Gruntfuggly        | Плагин который  позволяет пользователям Visual Studio Code быстро находить, организовывать и управлять заметками TODO и FIXME в их коде                     |                                                             |
| 31  | Indent-Rainbow                               | oderwat            | Плагин который  позволяет визуализировать уровни отступов в коде с помощью цветовой индикации.                                                              |                                                             |
| 32  | Thunder Client                               | Thunder Client<br> | Плагин который  позволяет производить тестирование API прямо из среды Visual Studio Code.                                                                   |                                                             |
| 33  | Markdown Table Prettifier                    | Krisztian Daroczi  | Плагин который  позволяет форматировать таблицы в Markdown для облегчения их чтения и редактирования.                                                       |                                                             |
| 34  | HTML CSS Support                             | ecmel              |                                                                                                                                                             |                                                             |
| 35  | YAML                                         | Red Hat            |                                                                                                                                                             |                                                             |

### Настройки


>[!info] Полезные ссылки
>[Одно из лучших видео на эту тему](https://youtu.be/e15PvHRHB_w?si=De__m5Wc3YvNuaVK)


Видео часовое, запаситесь терпением. Там собирается конфиг Python + HTML / CSS + Шаблоны Django
Однако вы можете просто взять это, и разместить у себя в файле `settings.json`

Как открыть этот файл в VS Studio Code?
Чтобы открыть файл `settings.json` в Visual Studio Code (VS Code), выполните следующие шаги:

1. **Откройте VS Code.**
2. **Откройте командную палитру.** Это можно сделать, нажав сочетание клавиш `Ctrl+Shift+P` на Windows/Linux или `Cmd+Shift+P` на macOS.
3. **Введите и выберите "Open Settings (JSON)".** В командной палитре начните вводить "Open Settings" и из предложенных вариантов выберите "Preferences: Open Settings (JSON)". Это действие откроет файл `settings.json`, который содержит пользовательские настройки вашего редактора.
4. **Внесите необходимые изменения в файле `settings.json`.** После того как файл открыт, вы можете добавить или изменить настройки, скопировав нужный код или параметры конфигурации.
5. **Сохраните изменения.** После внесения всех необходимых изменений сохраните файл, нажав `Ctrl+S` на Windows/Linux или `Cmd+S` на macOS.

Это можно сделать так же зайдя в настройки (есть кнопка открыть `settings.json` в верхнем правом углу )

Скопируйте эти настройки туда и сохраните файл.


```json
{
  "editor.mouseWheelZoom": true,
  "sqltools.useNodeRuntime": true,

  // Output settings делаем читаемой киррилицу
  "files.encoding": "utf8",
  "terminal.integrated.charset": "utf8",

  //terminal
  "terminal.integrated.cursorStyle": "line",
  "terminal.integrated.cursorBlinking": true,
  "terminal.integrated.cursorWidth": 10,
  "terminal.integrated.enableFileLinks": "off",
  "terminal.integrated.defaultProfile.windows": "Command Prompt",
  // Шрифт терминала размер
  "terminal.integrated.fontSize": 20,
  //editor
  "editor.minimap.enabled": false,
  "editor.find.seedSearchStringFromSelection": "selection",
  "editor.accessibilitySupport": "off",
  "editor.autoClosingDelete": "never",
  "editor.autoClosingOvertype": "never",
  "editor.definitionLinkOpensInPeek": true,
  "editor.hover.delay": 5000,
  "editor.roundedSelection": false,
  "editor.scrollbar.horizontal": "visible",
  "editor.scrollbar.vertical": "visible",
  "editor.scrollbar.scrollByPage": true,
  "editor.selectionHighlight": false,
  "editor.unicodeHighlight.ambiguousCharacters": false,
  "editor.unicodeHighlight.includeStrings": false,

  // comment like "this is stop sign"
  "debug.autoExpandLazyVariables": true,
  "debug.inlineValues": "on",
  "debug.terminal.clearBeforeReusing": true,

  // disable or change junk features
  "window.commandCenter": false,
  "workbench.startupEditor": "none",
  "explorer.autoReveal": false,
  "explorer.compactFolders": false,
  "files.autoSave": "afterDelay",
  "breadcrumbs.enabled": false,
  "workbench.cloudChanges.autoResume": "off",
  "workbench.cloudChanges.continueOn": "off",
  "workbench.enableExperiments": false,
  "workbench.quickOpen.closeOnFocusLost": false,
  "workbench.settings.enableNaturalLanguageSearch": false,
  "window.density.editorTabHeight": "compact",
  "accessibility.verbosity.comments": false,
  "search.defaultViewMode": "tree",
  "telemetry.telemetryLevel": "off",
  "extensions.closeExtensionDetailsOnViewChange": true,
  "settingsSync.keybindingsPerPlatform": false,

  // git
  "git.autoRepositoryDetection": "subFolders",

  //Setting up Pylance and code analysis.
  "python.languageServer": "Pylance",
  "python.analysis.typeCheckingMode": "basic",
  "python.analysis.diagnosticMode": "openFilesOnly",
  "python.analysis.autoSearchPaths": true,
  "python.analysis.autoImportCompletions": true,
  "python.analysis.completeFunctionParens": true,
  "python.analysis.importFormat": "absolute",

  "python.linting.pylintArgs": [
    "--disable=missing-module-docstring,missing-class-docstring,missing-function-docstring"
  ],

  // Enable display of variable typing.
  "python.analysis.inlayHints.variableTypes": true,
  "python.analysis.inlayHints.functionReturnTypes": true,
  "python.analysis.enablePytestSupport": true,
  "python.analysis.indexing": true,
  "python.analysis.packageIndexDepths": [
    {
      "name": "django", //here is the library you need
      "depth": 3,
      "includeAllSymbols": true
    },

    {
      "name": "selenium",
      "depth": 3,
      "includeAllSymbols": true
    },

    {
      "name": "sqlalchemy",
      "depth": 3,
      "includeAllSymbols": true
    },

    {
      "name": "sqlite3",
      "depth": 3,
      "includeAllSymbols": true
    }
  ],

  "[python]": {
    "editor.defaultFormatter": "ms-python.black-formatter"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },

  // for django:

  "emmet.includeLanguages": {
    "django-html": "html"
  },

  "files.associations": {
    "**/*.html": "html",
    "**/templates/*/*.html": "django-html",
    "**/templates/*/*/*.html": "django-html",
    "**/templates/*": "django-html",
    "**/requirements{/**,*}.{txt,in}": "pip-requirements"
  },

  "[django-html]": {
    "breadcrumbs.showClasses": true,
    "editor.quickSuggestions": {
      "other": true,
      "comments": true,
      "strings": true
    }
  },
  "gitlens.ai.experimental.provider": "openai",
  "gitlens.ai.experimental.anthropic.model": "claude-2.1",
  "inference.model": "codellama:34b-code-q4_K_S",
  "inference.endpoint": "http://localhost:1234/v1/chat/completions",
  "github.copilot.enable": {
    "*": true,
    "plaintext": true,
    "markdown": true,
    "scminput": false
  },
  "notebook.includeCellOutputs": true,
  "gitlens.graph.layout": "editor",
  "gitlens.ai.experimental.openai.model": "gpt-3.5-turbo-16k",
  "gitlens.experimental.generateCommitMessagePrompt": "создай коммит-сообщение, на русском языке. Напиши его в этом поле",
  "gitlens.views.commitDetails.files.layout": "list",
  "git.autofetch": true,
  "markdown-preview-enhanced.revealjsTheme": "night.css",
  "markdown-preview-enhanced.codeBlockTheme": "auto.css",
  "markdown-preview-enhanced.previewTheme": "atom-material.css",
  "markdown-preview-enhanced.enablePreviewZenMode": false,
  "git.confirmSync": false,
  "gitlens.views.commits.files.layout": "tree",
  "workbench.editorAssociations": {
    "*.pickle": "default"
  },
  "diffEditor.maxComputationTime": 0,
  "workbench.iconTheme": "material-icon-theme",
  "gitlens.graph.minimap.additionalTypes": [
    "localBranches",
    "stashes",
    "remoteBranches",
    "tags"
  ],
  "gitlens.codeLens.enabled": false,
  "editor.inlineSuggest.suppressSuggestions": true,
  "cody.autocomplete.enabled": false,
  "diffEditor.ignoreTrimWhitespace": false,
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "git.enableSmartCommit": true,
  "github.copilot.editor.enableAutoCompletions": true,
  "workbench.colorTheme": "Dracula",
  "editor.formatOnSave": true,
  "window.zoomLevel": 1
}


```
## Меняем кодировку Терминала Windows

Если после всех этих настроек, вы видите иероглифы в терминале VS Code, пока переходить к радикальным мерам.

А именно, установить общепринятую во всём мире кодировку UTF-8 для Windows по умолчанию.

Чтобы изменить кодировку терминала на UTF-8 в Windows 11, необходимо выполнить несколько шагов для изменения языковых настроек системы. Это позволит приложениям и терминалам, таким как PowerShell и Command Prompt (cmd), использовать UTF-8 в качестве стандартной кодировки. Вот как вы можете это сделать:

1. **Открытие настроек языка**:
   - Откройте «Настройки» Windows, нажав `Win + I` на клавиатуре.
   - Перейдите в раздел «Время и язык» -> «Язык и регион».

2. **Изменение региональных настроек**:
   - В разделе «Регион» найдите и выберите пункт «Дополнительные параметры языка» или «Административные языковые настройки», в зависимости от версии Windows 11.
   - Нажмите на ссылку «Изменить системный язык...» или «Изменить формат данных...», если таковая имеется.

3. **Включение бета-версии UTF-8**:
   - В открывшемся окне настроек административных языковых параметров найдите раздел, связанный с изменением языка для неюникодных программ. Это может быть вкладка «Административные».
   - Выберите опцию «Изменить язык для неюникодных программ».
   - В новом окне выберите «Изменить системный локаль» или аналогичный пункт.
   - В списке доступных локалей найдите и отметьте опцию «Бета-версия: использовать Unicode UTF-8 для поддержки языка всемирного уровня». Эта опция включит поддержку UTF-8 для всех приложений, включая терминалы.

4. **Применение изменений**:
   - Нажмите «ОК» или «Применить» для сохранения настроек.
   - Система может запросить перезагрузку компьютера для вступления изменений в силу. Перезагрузите компьютер.

После перезагрузки Windows 11 будет использовать UTF-8 в качестве стандартной кодировки для терминалов и приложений, что должно решить проблемы с отображением символов, включая кириллицу, в PowerShell и других терминалах.

## Меняем шрифт Терминала

После этого, могут возникнуть проблемы, т.к. шрифт по-умолчанию не может работать с кириллицей и UTF-8

Чтобы изменить шрифт в PowerShell на Windows 11 на шрифт, поддерживающий UTF-8 и кириллицу, выполните следующие шаги. Это поможет исправить проблему с отображением кириллических символов, таких как русские буквы, которые в настоящее время отображаются как символы сердечек или другие непонятные символы.

1. **Открытие PowerShell**: Сначала откройте PowerShell, кликнув правой кнопкой мыши на кнопку «Пуск» и выбрав «Windows PowerShell» (или «Windows Terminal», если вы используете его).

2. **Открытие настроек шрифта**:
   - Для **Windows PowerShell**: Кликните правой кнопкой мыши на заголовке окна PowerShell и выберите «Свойства». Перейдите на вкладку «Шрифт».
   - Для **Windows Terminal**: Откройте выпадающее меню вкладок и выберите «Настройки» (или нажмите `Ctrl+,`). В разделе «Профили» выберите профиль PowerShell и перейдите к разделу «Внешний вид».

3. **Выбор шрифта**:
   - Выберите шрифт из списка, который поддерживает UTF-8 и кириллицу. Хорошим выбором может быть «Consolas», «Lucida Console», «Courier New» или любой другой моноширинный шрифт, который поддерживает кириллицу и символы Unicode. В Windows Terminal также доступны дополнительные шрифты, такие как «Cascadia Code».

4. **Сохранение настроек**:
   - Для **Windows PowerShell**: После выбора шрифта нажмите «ОК» или «Применить», чтобы сохранить изменения.
   - Для **Windows Terminal**: После выбора шрифта нажмите «Сохранить» на странице настроек.

5. **Проверка поддержки UTF-8**:
   - Убедитесь, что PowerShell или Windows Terminal настроен на использование UTF-8. Вы можете установить кодировку UTF-8 в PowerShell с помощью команды: `chcp 65001`.

6. **Перезапуск PowerShell**:
   - Закройте и снова откройте PowerShell или Windows Terminal, чтобы увидеть изменения.

Если после смены шрифта проблема с отображением кириллицы не исчезла, убедитесь, что ваши системные настройки поддерживают UTF-8. В некоторых случаях может потребоваться дополнительная настройка региональных параметров Windows для полной поддержки UTF-8  


## Ошибка: `No global/local python version has been set yet. Please set the global/local version`

Ошибка, которую вы видите, указывает на то, что для вашего проекта в Visual Studio Code не установлена глобальная или локальная версия Python с помощью инструмента управления версиями Python, `pyenv`. Вот шаги, чтобы решить эту проблему:

1. **Установите `pyenv`**, если ещё не установлен. Для этого вам нужно будет открыть терминал и выполнить соответствующие команды установки для вашей операционной системы. Инструкции по установке можно найти на официальном [GitHub репозитории pyenv](https://github.com/pyenv/pyenv#installation).

2. **Установите нужную версию Python с помощью `pyenv`**. Если вам нужна версия 3.7.4, как указано в сообщении об ошибке, выполните следующие команды в терминале:
   ```bash
   pyenv install 3.7.4
   pyenv global 3.7.4
   ```

3. **Проверьте установку**. Убедитесь, что правильная версия Python установлена и активна с помощью команды:
   ```bash
   python --version
   ```
   Эта команда должна выводить `Python 3.7.4`.

4. **Настройте Visual Studio Code**. Убедитесь, что расширение Python Environment Manager в VS Code правильно настроено для использования версии Python, управляемой `pyenv`. Вы можете проверить и изменить настройки интерпретатора Python через команду `Python: Select Interpreter` в палитре команд (Ctrl+Shift+P).

5. **Перезапустите VS Code**. Иногда необходимо перезапустить VS Code, чтобы изменения вступили в силу.

После выполнения этих шагов попробуйте снова выполнить установку пакета с помощью `pip install mypy`. Если проблемы продолжаются, проверьте, что активный терминал в VS Code действительно использует версию Python, установленную через `pyenv`.


## Разные версии Python через `Python Environment Manager`


Да, с помощью расширения Python Environment Manager в Visual Studio Code вы можете выбирать различные версии Python для вашего проекта, в том числе те, которые управляются через `pyenv`. Вот как вы можете это сделать:

1. **Установите нужные версии Python через `pyenv`**, если они ещё не установлены. Вы можете установить несколько версий и переключаться между ними. Например:
   ```bash
   pyenv install 3.8.0
   pyenv install 3.9.0
   ```

2. **Убедитесь, что `pyenv` корректно настроен**. Для использования в VS Code, `pyenv` должен быть правильно интегрирован в вашу систему. Убедитесь, что пути к `pyenv` и его версиям Python добавлены в переменные среды вашей операционной системы. Это часто делается автоматически, но может потребовать ручной настройки, особенно на Windows.

3. **Выберите версию Python через Python Environment Manager в VS Code**. Откройте палитру команд (Ctrl+Shift+P), введите и выберите `Python:


## Если слетает русский язык

В Visual Studio Code для восстановления русского языка можно использовать команду, которая устанавливает интерфейсный язык. Вот как вы можете это сделать:

1. Откройте **Command Palette**. Это можно сделать через меню или используя сочетание клавиш `Ctrl+Shift+P` (Cmd+Shift+P на macOS).
2. Введите или найдите команду: `Configure Display Language`.
3. Выберите эту команду, и вам должен открыться список доступных языков.
4. Выберите `ru` или `Russian`, чтобы установить русский язык.
5. После выбора языка, Visual Studio Code предложит перезагрузить редактор для применения изменений.

Если этот метод не сработает, вы также можете попробовать изменить конфигурационный файл настроек напрямую:

1. Откройте файл настроек JSON в VS Code, используя команду `Preferences: Open Settings (JSON)` в Command Palette.
2. Добавьте или измените следующую строку:
   ```json
   "locale": "ru"
   ```
3. Сохраните файл и перезагрузите VS Code.
Это должно вернуть русский язык в вашем редакторе. Если проблемы останутся, пожалуйста, уточните, и я попробую помочь дальше.

## Дебаггер в VS code

### Про возможности

Visual Studio Code (VS Code) предлагает мощные возможности для отладки кода на Python благодаря своему встроенному плагину дебаггера. Это позволяет разработчикам эффективно находить и устранять ошибки в их коде. Вот основные аспекты и функции дебаггера в VS Code для Python:

1. **Установка и настройка:**
   - Для начала работы с дебаггером нужно установить расширение Python в VS Code, которое включает в себя поддержку дебаггинга.
   - Также необходимо убедиться, что в вашем рабочем окружении установлен интерпретатор Python и необходимые зависимости, например, `ptvsd` или `debugpy` – библиотеки, которые VS Code использует для дебаггинга.

2. **Конфигурация запуска:**
   - Дебаггер в VS Code позволяет создавать и настраивать конфигурации запуска, которые определяют, как будет запускаться и отлаживаться ваш Python-скрипт. Это делается через файл `launch.json`, где можно задать путь к интерпретатору, аргументы командной строки, рабочую директорию и другие параметры.

3. **Точки останова (breakpoints):**
   - Вы можете устанавливать точки останова, чтобы приостанавливать выполнение программы в определённых местах. Это позволяет вам изучить текущее состояние программы, проверить значения переменных, стек вызовов и т.д.

4. **Просмотр и изменение переменных:**
   - Во время останова программы вы можете просматривать и изменять значения переменных в окне "Variables". Это помогает лучше понять, как данные изменяются в процессе выполнения программы.

5. **Стек вызовов:**
   - Окно "Call Stack" показывает стек вызовов на момент останова программы, что позволяет вам видеть путь, который привёл к текущему месту в коде, и быстро переключаться между функциями и методами.

6. **Консоль дебаггера:**
   - Используя Debug Console, вы можете вводить Python-команды во время останова, что позволяет динамически взаимодействовать с вашим кодом, выполняя выражения или модифицируя объекты.

7. **Управление выполнением:**
   - Дебаггер предоставляет стандартные кнопки управления выполнением программы, такие как "Continue" (продолжить выполнение до следующей точки останова), "Step Over" (выполнить текущую строку и перейти к следующей), "Step Into" (войти внутрь функции, которая собирается выполниться) и "Step Out" (выполнить оставшуюся часть функции и вернуться).

8. **Условные точки останова и точки останова по исключениям:**
   - VS Code позволяет создавать условные точки останова, которые срабатывают, только если выполнено определённое условие. Также можно настраивать точки останова на исключениях, что позволяет приостанавливать выполнение при возникновении ошибок.

Эти функции делают дебаггер в VS Code мощным инструментом для разработки и отладки Python-программ, обеспечивая более глубокое понимание работы кода и упрощая процесс разработки.

### Про настройки

Когда вы начинаете отладку в Visual Studio Code (VS Code), плагин дебаггера предлагает различные опции для того, что именно будет отлаживаться. Это зависит от типа проекта и установленных расширений. Например, в проекте на Django, плагин может предложить варианты для отладки Python кода или Django-приложения. Если установлены дополнительные плагины для JavaScript, такие как для Node.js или расширения для браузеров (например, Edge), то в список опций добавятся и эти технологии.

**Кнопка "Создать launch.json":**
- Когда вы выбираете "Start Debugging" (или нажимаете F5), VS Code предложит создать файл конфигурации `launch.json`, если он не обнаружен в вашем проекте. Этот файл содержит настройки для среды отладки.
- Нажав на кнопку "Create a launch.json file", вы увидите список доступных шаблонов конфигурации, соответствующих различным типам проектов и установленным плагинам. Вы можете выбрать подходящий шаблон (например, для Django или Node.js) и VS Code сгенерирует базовую конфигурацию для вас.

**Файл launch.json:**
- `launch.json` располагается в папке `.vscode` в корне вашего проекта. Этот файл позволяет настроить параметры запуска и отладки, такие как путь к интерпретатору Python, аргументы командной строки, порты, переменные среды и многое другое.
- В файле можно задать несколько конфигураций, что позволяет легко переключаться между различными режимами запуска и отладки, например, между отладкой серверной и клиентской части проекта.

**Нужно ли пушить launch.json в репозиторий?**
- Решение о том, добавлять ли `launch.json` в ваш репозиторий, зависит от того, насколько универсальны настройки в этом файле. Если настройки специфичны для проекта и будут полезны другим разработчикам в вашей команде, то имеет смысл добавить файл в репозиторий.
- Однако, если конфигурация содержит специфические для пользователя пути, секреты или другие чувствительные данные, лучше эти данные вынести в переменные среды или иным образом исключить файл `launch.json` из репозитория, чтобы избежать утечек информации.

Таким образом, `launch.json` играет важную роль в процессе настройки отладки в VS Code, делая её более гибкой и адаптируемой к различным требованиям и условиям разработки.

### Конфигурация для Django

Данный `launch.json` файл содержит конфигурацию для отладки Django-проекта в Visual Studio Code с использованием плагина дебаггера `debugpy`. Рассмотрим подробно каждый атрибут в этом файле:

```json
{
    // Используйте IntelliSense, чтобы узнать о возможных атрибутах.
    // Наведите указатель мыши, чтобы просмотреть описания существующих атрибутов.
    // Для получения дополнительной информации посетите: https://go.microsoft.com/fwlink/?linkid=830387
    "version": "0.2.0",
    "configurations": [
        {
            "name": "Отладчик Python: Django",
            "type": "debugpy",
            "request": "launch",
            "program": "${workspaceFolder}\\django_329\\manage.py",
            "args": [
                "runserver"
            ],
            "django": true
        }
    ]
}
```

1. **version**:
   - Указывает версию формата конфигурации. "0.2.0" – это текущая версия формата для файлов `launch.json` в VS Code.

2. **configurations**:
   - Этот массив содержит одну или несколько конфигураций отладки. В вашем случае здесь одна конфигурация для отладки Django-проекта.

3. **name**:
   - Человекочитаемое имя для конфигурации отладки. Оно отображается в меню выбора конфигурации в VS Code.

4. **type**:
   - Определяет тип дебаггера, который будет использоваться. "debugpy" – это имя дебаггера для Python, разработанного как замена `ptvsd`.

5. **request**:
   - Тип запроса на запуск дебаггера. "launch" означает, что VS Code должен самостоятельно запустить указанную программу в режиме отладки.

6. **program**:
   - Путь к основному исполняемому файлу проекта, который будет запущен дебаггером. `${workspaceFolder}` – это переменная, которая автоматически заменяется на путь к текущей папке проекта в VS Code. Путь указывает на `manage.py` Django-проекта.

7. **args**:
   - Аргументы, которые будут переданы программе при запуске. В данном случае передаётся "runserver", что указывает Django запустить разработческий сервер.

8. **django**:
   - Установка этого параметра в `true` указывает дебаггеру, что отладка происходит в контексте Django-проекта. Это позволяет `debugpy` корректно обрабатывать специфические особенности и поведение Django, например, отладку шаблонов и запросов.

**Включение файла в репозиторий:**
- Добавление `launch.json` в репозиторий может быть полезным, если конфигурация отладки универсальна для всех членов команды и не содержит личной или чувствительной информации. Это обеспечивает единообразие настроек среды разработки среди всех разработчиков проекта.

Это основные аспекты данной конфигурации `launch.json`. Такая структура файла помогает настроить и стандартизировать процесс отладки для проектов на Django в среде Visual Studio Code.

### Конфигурация для JS

Вы можете добавить в файл `launch.json` конфигурацию для отладки JavaScript с помощью Microsoft Edge и Edge DevTools в Visual Studio Code. Вот ваша конфигурация:

```json
{
    "type": "vscode-edge-devtools.debug",
    "request": "launch",
    "name": "Launch Microsoft Edge and open the Edge DevTools",
    "url": "http://localhost:8080",
    "webRoot": "${workspaceFolder}"
}
```

Теперь давайте рассмотрим каждый ключ в этой конфигурации:

1. **type**:
   - `"type": "vscode-edge-devtools.debug"` указывает на тип дебаггера, который будет использоваться для отладки. Здесь используется дебаггер от Visual Studio Code для Edge DevTools, который предназначен для отладки веб-приложений в браузере Microsoft Edge.

2. **request**:
   - `"request": "launch"` означает, что дебаггер должен запустить процесс отладки. В этом контексте VS Code сам запустит экземпляр Microsoft Edge с заданными параметрами для начала сессии отладки.

3. **name**:
   - `"name": "Launch Microsoft Edge and open the Edge DevTools"` это имя конфигурации, которое будет отображаться в списке доступных конфигураций отладки в VS Code. Это имя помогает легко идентифицировать различные конфигурации отладки в проекте.

4. **url**:
   - `"url": "http://localhost:8080"` определяет URL, который будет открыт в Microsoft Edge при запуске отладки. Это должен быть URL вашего локально запущенного веб-приложения, который в данном случае указывает на порт 8080 на локальном хосте.

5. **webRoot**:
   - `"webRoot": "${workspaceFolder}"` указывает путь к корню веб-проекта в файловой системе. `${workspaceFolder}` — это переменная в VS Code, которая автоматически заменяется на путь к папке, открытой в VS Code как рабочее пространство. Этот путь используется дебаггером для разрешения путей к файлам в исходном коде, например, при отображении ошибок или во время степинга по коду.

Эта конфигурация позволяет эффективно отлаживать веб-приложения, запущенные локально, с использованием мощных инструментов разработчика в Microsoft Edge, обеспечивая быстрый доступ к отладке JavaScript, CSS и HTML кода вашего проекта.

#### Варианты запуска EDGE

Существуют различные конфигурации для отладки JavaScript в браузере Microsoft Edge, используя расширение Microsoft Edge Tools для Visual Studio Code. Вот краткое описание каждого из вариантов:

1. **Microsoft Edge Tools: Attach**:
   - Эта конфигурация позволяет подключиться к уже запущенному экземпляру Microsoft Edge. Для этого браузер должен быть запущен с определёнными параметрами, позволяющими отладку через порт. Этот режим полезен, если вы уже работаете с приложением в браузере и хотите начать его отладку без перезапуска.

2. **Microsoft Edge Tools: Launch**:
   - Эта конфигурация запускает новый экземпляр Microsoft Edge в режиме отладки с указанными параметрами (например, с открытой конкретной вкладкой или URL). Это удобно для начала отладки с "чистого листа", когда важно исключить влияние предыдущих сессий браузера.

3. **Microsoft Edge: запуск**:
   - Похож на предыдущий вариант, но может быть частью стандартного расширения VS Code для отладки веб-приложений, не обязательно связанного с Edge Tools. Запускает Edge для отладки веб-приложения.

4. **Microsoft Edge: подключение**:
   - Аналогично первому варианту ("Attach"), это позволяет подключиться к уже запущенному экземпляру Edge. Различия могут касаться деталей реализации в контексте конкретных расширений или версий.

**Для отладки JavaScript в шаблонах Django**:
- Использование расширения Microsoft Edge Tools может быть особенно полезно, так как вы можете визуально отслеживать, как JavaScript взаимодействует с HTML и CSS вашего Django-шаблона.
- Если ваша задача — отлаживать JavaScript, встроенный в Django-шаблоны, я бы рекомендовал использовать **"Microsoft Edge Tools: Launch"**. Это позволит вам начать сессию отладки с нужной вам страницы, и вы сможете в режиме реального времени просматривать изменения и дебажить JavaScript, не влияя на другие вкладки или сессии в браузере.

### Конфигурация запуска Django приложения

```json
       {
            "name": "Запуск Django приложения",
            "type": "python",
            "request": "launch",
            "program": "${workspaceFolder}\\django_329\\manage.py",
            "args": [
                "runserver"
            ],
            "django": true
}
```
Отличается тем, что type идет другого типа (в отличии от Debug режима)