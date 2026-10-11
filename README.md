# ConfuserEx2-Unpacker
Мой custom распаковщик для файлов .NET которые были обфусцированны при помощи ConfuserEx2, код написал недавно. Не поддерживает ConfuserEx1.0.0, тестил распаковку на версии ConfuserEx2(1.6.0.0) на скринах показал до и после.( использовался максимальный протект все функции были включены ) после распаковки файл запускается

![Before](https://github.com/CusDec-dev/ConfuserEx2-Unpacker/blob/main/673.png)
![Unpacking log](https://github.com/CusDec-dev/ConfuserEx2-Unpacker/blob/main/672.png)
![After](https://github.com/CusDec-dev/ConfuserEx2-Unpacker/blob/main/671.png)

для чего сделал свой?:
анпакеры которые я обычно использовал самый популярный который использует CawkEmulatorV4 не годится на ConfuserEx2 на гитхабе особого интересного с фиксом EntryPoint не нашел ведь мне он был важен чтобы даже после снятия всех слоев обфускаций файл был запускаемым и рабочим.

[ + ] Функции:
1. Anti-Tamper
2. Anti-Dump
3. Anti-Debug
4. Anti-ILdasm
5. Constants protection
6. Resource protection
7. Compressor
8. Hardening protection
9. invalid metadata
10. References proxy
11. Watermarking
12. TypeScrambler
13. NameProtection
