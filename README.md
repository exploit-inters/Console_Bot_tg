# Console_Bot_tg
Телеграм в качестве консоли от Linux

Бот для телеграма, который позволяет использовать телеграм как консоль вашего компьютера.
Выполнит любую команду которая отдает свои данны через stdout.

Некоторые команды реализованы в этом скрипте:
- "cd dir" смена директории
- "cd .." подняться в родительскую директорию
- "get file" получить указанный файл

Использование:
- вписать нужные параметры в блоке "Настройки"
- запустить файл скрипта
- для включения контекста управления, набрать в чате с ботом /dir
  в ответ получите информационное сообщение о том что доступ разрешен и контекст включен
- отправьте нужную команду, примеры команд: "ls", "pwd", "ls -al", "cd ..", "cd dir"
- выход из контекста "dir_exit"