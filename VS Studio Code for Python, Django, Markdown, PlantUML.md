
## Инструкция

### Установленные расширения

Этот пакет расширений делает VS Studio Code возможно даже чуть лучше, чем профессиональное издание PyCharm.

Однако стоит помнить, что PyCharm как Macbook - все вылизано, код, аппаратная часть. Но за это надо платить.  

VS Studio Code - как Linux. Надо с ним повозится.         

Вот полный перечень плагинов, которые стоят у меня, на текущий момент:  

| №   | Название Расширения                          | Автор              | Описание                                                                                                                                             | Комментарии                                                 |
| --- | -------------------------------------------- | ------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------- |
| 1   | SQLTools SQLite                              | Matheus Teixeira   | Расширение для работы с базами данных SQLite в VS Code.                                                                                              | Работает хорошо с другими SQLTools расширениями.            |
| 2   | Pylance                                      | Microsoft          | Сервер языка для Python, предоставляющий информацию для IntelliSense.                                                                                | Совместимо с расширениями Python от Microsoft.              |
| 3   | Pylint                                       | Microsoft          | Поддержка линтинга для файлов Python с использованием Pylint.                                                                                        | Может конфликтовать с другими линтерами.                    |
| 4   | Python                                       | Microsoft          | Поддержка языка Python, включая IntelliSense и отладку.                                                                                              | Основное расширение для работы с Python.                    |
| 5   | Python Debugger                              | Microsoft          | Расширение для отладки Python с использованием debugpy.                                                                                              | Интегрируется с основным расширением Python.                |
| 6   | Python Environment Manager                   | Don Jayamanne      | Управление Python окружениями и пакетами.                                                                                                            | Полезно для управления зависимостями проекта.               |
| 7   | Russian Language Pack for Visual Studio Code | Microsoft          | Пакет локализации для VS Code на русском языке.                                                                                                      | Улучшает UX для русскоговорящих пользователей.              |
| 8   | SQLTools                                     | Matheus Teixeira   | Расширение для подключения к различным базам данных.                                                                                                 | Облегчает управление базами данных из VS Code.              |
| 9   | SQLTools MySQL/MariaDB/TiDB                  | Matheus Teixeira   | Расширение для работы с MySQL/MariaDB/TiDB.                                                                                                          | Нужно для работы с этими конкретными СУБД.                  |
| 10  | SQLTools PostgreSQL/Cockroach Driver         | Matheus Teixeira   | Драйвер для работы с PostgreSQL и CockroachDB.                                                                                                       | Идеально подходит для пользователей этих СУБД.              |
| 11  | IntelliCode API Usage Examples               | Microsoft          | Предлагает примеры кода для различных API на GitHub.                                                                                                 | Ускоряет разработку благодаря доступным примерам.           |
| 12  | IntelliSense for CSS class names in HTML     | Zignd              | Автодополнение имен классов CSS в HTML.                                                                                                              | Улучшает скорость написания и точность кода.                |
| 13  | Live Server                                  | Ritwick Dey        | Локальный сервер для разработки с функцией live reload.                                                                                              | Незаменим для тестирования фронтенда.                       |
| 14  | Markdown All in One                          | Yu Zhang           | Все необходимое для работы с Markdown, включая ярлыки и предпросмотр.                                                                                | Упрощает работу с Markdown файлами.                         |
| 15  | Markdown Preview Enhanced                    | Yiyi Wang          | Улучшенный предпросмотр Markdown файлов.                                                                                                             | Дополнение к Markdown All in One для лучшего предпросмотра. |
| 16  | Material Theme                               | Equinusocio        | Тема оформления VS Code.                                                                                                                             | Один из самых популярных тем оформления.                    |
| 17  | Path Intellisense                            | Christian Kohler   | Автодополнение путей к файлам в VS Code.                                                                                                             | Облегчает навигацию по проекту.                             |
| 18  | PlantUML                                     | jebbs              | Поддержка языка PlantUML для создания диаграмм.                                                                                                      | Важно для визуализации архитектуры систем.                  |
| 19  | Prettier - Code formatter                    | N/A                | Форматирование кода с использованием Prettier.                                                                                                       | Стандарт де-факто для форматирования во многих проектах.    |
| 20  | Auto Rename Tag                              | Jun Han            | Автоматическое переименование парных HTML/XML тегов.                                                                                                 | Снижает риск ошибок при редактировании кода.                |
| 21  | Black Formatter                              | Microsoft          | Поддержка форматирования Python файлов с использованием Black.                                                                                       | Предпочтительный форматтер для многих Python разработчиков. |
| 22  | CSS Peek                                     | Pranay Prakash     | Предоставляет возможность просмотра определений CSS ID и классов.                                                                                    | Упрощает редактирование CSS.                                |
| 23  | Django                                       | Baptiste Darthenay | Сниппеты и синтаксис для работы с Django.                                                                                                            | Необходим для разработчиков Django.                         |
| 24  | GitHub Copilot                               | GitHub             | Искусственный интеллект для подсказки кода.                                                                                                          | Может генерировать код на основе комментариев.              |
| 25  | GitHub Copilot Chat                          | GitHub             | Функции чата, управляемые GitHub Copilot.                                                                                                            | Позволяет общаться с Copilot в процессе кодирования.        |
| 26  | GitLens — Git supercharged                   | GitKraken          | Улучшенная работа с Git в VS Code.                                                                                                                   | Отличный инструмент для визуализации истории Git.           |
| 27  | IntelliCode                                  | Microsoft          | AI-поддержка разработки, включая автодополнение.                                                                                                     | Интегрируется с многими другими расширениями Microsoft.     |
| 28  | Auto Close Tag                               | Jun Han            | Автоматическое закрытие тегов при написании кода, что позволяет разработчикам экономить время и уменьшать количество ошибок при вводе.               | Снижает риск ошибок                                         |
| 29  | Microsoft Edge Tools for VS Code             | Microsoft          | Плагин для  разработки веб-приложений, который позволяет интегрировать функции браузера Microsoft Edge прямо в среду ра Предпросмотр и дебаггер JS HTML CSS                                                        |

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
  "workbench.colorTheme": "Material Theme",
  "editor.mouseWheelZoom": true,
  "sqltools.useNodeRuntime": true,

  // Output settings делаем читаемой киррилицу
  "files.encoding": "utf8",
  "terminal.integrated.charset": "utf8",

  //terminal
  "terminal.integrated.cursorStyle": "line",
  "terminal.integrated.cursorBlinking": true,
  "terminal.integrated.cursorWidth": 2,
  "terminal.integrated.enableFileLinks": "off",
  "terminal.integrated.scrollback": 50,
  "terminal.integrated.defaultProfile.windows": "Command Prompt",

  //editor
  "editor.minimap.enabled": false,
  "editor.find.seedSearchStringFromSelection": "selection",
  "editor.accessibilitySupport": "off",
  "editor.autoClosingDelete": "never",
  "editor.autoClosingOvertype": "never",
  "editor.definitionLinkOpensInPeek": true,
  "editor.hover.delay": 2000,
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

    //like this:
    // {
    //     "name": "django",
    //     "depth": 3,
    //     "includeAllSymbols": true
    // }
  ],

  "[python]": {
    "editor.defaultFormatter": "ms-python.black-formatter"
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
  "window.zoomLevel": 2,
 
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