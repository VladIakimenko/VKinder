Эта версия приложения собрана на базе ветки development (с выводом описания процессов в терминал).
В ней, помимо сырых питоновских файлов, Вы можете найти скомпилированный main.exe

Перед запуском необходимо:
    создать и расположить env.txt в корне
    
GROUP_ID=
GROUP_TOKEN=
USER_TOKEN=

SQLSYS=postgresql
USER=
PASSWORD=
HOST=localhost
PORT=5432
DATABASE=

    установить и настроить postgres
    создать пустую базу данных вручную при помощи скрипта createdb (или иным способом)
    внести данные о пользователе, пароле и названии БД в env.txt (вносить данные без ковычек после знака “=”)
    запустить приложение через main.exe
