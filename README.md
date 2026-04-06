# [Наш Discord сервер](https://discord.gg/Zqy6rsqdyQ)
# Инструкция по установке DrakanHex7
>(тыкайте по ссылкам чтобы открыть)

## Prism Launcher
### Для [Prism Launcher](https://prismlauncher.org/) и его **[пиратского аналога](https://github.com/ElyPrismLauncher/ElyPrismLauncher/releases/download/10.0.2/ElyPrismLauncher-Windows-MSVC-Setup-10.0.2.exe)** с авто обновлениями:
- Скачиваем [**DrakanHex7Prism.zip**](https://raw.githubusercontent.com/alexyzer/DrakanHex7/main/DrakanHex7Prism.zip), перетаскиваем в окно лаунчера и запускаем.


## Modrinth
### Для [Modrinth](https://modrinth.com/app) и его [пиратского аналога](https://git.astralium.su/didirus/AstralRinth/releases/download/AR-0.10.2701/AstralRinth%20App_0.10.2701_x64-setup.exe) с авто обновлениями:
- Скачиваем [**DrakanHex7.mrpack**](https://raw.githubusercontent.com/alexyzer/DrakanHex7/main/DrakanHex7.mrpack).
- Заходим в настройки сборки Launch hooks и в Pre-launch вставляем ```java -jar packwiz-installer-bootstrap.jar https://raw.githubusercontent.com/alexyzer/DrakanHex7/main/pack/pack.toml -bootstrap-no-update```
- **Если у вас не находит java**, замените ```java``` на путь до джавы, указанный в лаунчере.

## Остальные
### Для другого любого нормального лаунчера:
- **Проверьте, чтобы в папке не оставались моды от других сборок!**
- Скачиваем Майнкрафт 1.20.1 с загрузчиком Forge.
- Скачиваем [**DrakanHex7Other.zip**](https://raw.githubusercontent.com/alexyzer/DrakanHex7/main/DrakanHex7Other.zip) (тыкните по ссылке)  и переносим  содержимое в папку .minecraft
- Если папки нет, можете создать её сами, либо запустить версию хотя бы один раз.
- Нужно использовать файл `УСТАНОВИТЬ.bat` из папки майнкрафта для **скачивания/обновления** сборки.
## Для Tlauncher:
- То же что и выше, но нужно создать отдельный профиль, и **ВЫКЛЮЧИТЬ** систему скинов Tlauncher и Sodium, чтобы он не докачивал лишние моды.

# Aдрес сервера:
>```213.152.43.53:25753```

>```drakanhex.mcmagic.space``` **<- ПРОКСИ**