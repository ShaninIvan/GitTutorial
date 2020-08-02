## Установка Git на Windows 10

[<-- Назад](./1_Git_and_Github.md)
[Содержание](./readme.md)
[Вперед -->](./3_Settings_Git.md)

---

Для работы с Git, его необходимо сначала установить на компьютер. Мы будем ставить его на систему Windows 10 x64.

Переходим на [официальный сайт Git](https://git-scm.com/downloads) и и выбираем "Windows". Загрузка должна начаться сама, но если этого
не произошло, нажмите "Click here to download manually".

![GitDownload](./assets/GitInstall/Download.png)

### **Процесс установки Git:**

1. Открываем загруженный файл и соглашаемся с лицензией, нажав "Next".

![Step1](./assets/GitInstall/Step1.png)

2. Выбираем путь, по которому Git будет установлен в вашей системе. Не следует путать это с путем репозитория — они создаются отдельно.

![Step2](./assets/GitInstall/Step2.png)

3. Выберираем необходимые компоненты Git:
    * *Additional icons* — добавляет иконки Git на рабочий стол;
    * *Windows Explorer integration* — добавляет действия в контекстное меню Windows (правая кнопка мыши). Git Brash и Git GUI 
    соответственно;
    * *Git LFS (Large File Support)* — расширение Git для работы с большими файлами;
    * _Associate .git* configuration files with the default text editor_ — ассоциирует файлы типа .git* с текстовым редактором Windows,
    стоящим по умолчанию;
    * *Use a TrueType font in all console windows*  — во всех консольных окнах будет использоваться шрифт TrueType;
    * *Check daily for Git for Windows updates* — ежедневно проверять обновления Git.

![Step3](./assets/GitInstall/Step3.png)

4. Выбираем название папки в меню "Пуск" Windows, либо отказываемся от ее создания.

![Step4](./assets/GitInstall/Step4.png)

5. Выбираем редактор кода, который Git будет использовать по умолчанию.

![Step5](./assets/GitInstall/Step5.png)

6. Выбираем способ использования из командной строки:
    * *Use Git from Git Bash only* — использование только из командной строки Bash;
    * *Use Git from the Windows Command Prompt* — использование командной строки Bash, а также минимальный набор 
    команд Git из консоли Windows;
    * *Use Git and optional Unix tools from the Windows Command Prompt* — использование Git и утилит Unix из командной строки Windows,
     в этом случае будут перезаписаны некоторые утилиты Windows, например find и sort.

![Step6](./assets/GitInstall/Step6.png)

7. Выберете библиотку, которая будет использована при подключении по протоколу HTTPS:
    * *OpenSSL* — сертификаты сервера будут проверяться с использованием Unix-файла ca-bundle.crt;
    * *Windows Secure Channel* — сертификаты сервера будут проверяться с использованием стандартной библиотеки Windows.

![Step7](./assets/GitInstall/Step7.png)

8. Убедитесь, что вы выбрали способ обработки окончания строк "*Checkout Windows-style, commit Unix-style line endings*". 
Это значение гарантирует, что Git преобразует LF в CRLF при проверке текстовых файлов. При выполнении текстовых файлов 
CRLF также преобразуется в LF. Это мера совместимости для защиты новых строк в текстовых файлах, что позволяет легко работать 
с текстовыми файлами в Windows и на платформах Unix.

![Step8](./assets/GitInstall/Step8.png)

9. Выберите, какой териминал будет использоваться с Git Bash:
    * *MinTTY* - терминал Unix;
    * *Windows* - стандартный терминал Windows.

![Step9](./assets/GitInstall/Step9.png)

10. Поведение Git Pull оставляем по умолчанию.

![Step10](./assets/GitInstall/Step10.png)

11. Как и менеджер учетных данных.

![Step11](./assets/GitInstall/Step11.png)

12. Выбираем дополнительные опции:
    * *File system caching* — кэширование файловой системы;
    * *Symbolic links* — разрешить символьные ссылки.

![Step12](./assets/GitInstall/Step12.png)

13. Жмем "Install".

---
[<-- Назад](./1_Git_and_Github.md)
[Содержание](./readme.md)
[Вперед -->](./3_Settings_Git.md)
