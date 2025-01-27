## Использование утилиты **du**
du - это команда для получения приблизительного объема дискового пространства, используемого указанными при вызове команды файлами или каталогами.

Вот несколько примеров работы с командой du:
- Чтобы просто вывести список папок в определённом каталоге и занимаемое ими место, например, в /var выполните: \
  ![du1](../misc/images/du1.png)
- По умолчанию размер выводится в байтах. Для того, чтобы размер выводился в более читабельном виде используйте опцию -h: \
  ![du2](../misc/images/du2.png)
- Если надо выводить размер не только папок, но и файлов, которые там находятся, используйте опцию -a: \
  <img src="../misc/images/du3.png" alt="du3" width="298"/>
- -c -- ключ вывода в конце общего размера всех папок
- -d -- максимальная глубина вложенности директорий
- -s -- ключ вывода только общего размера
