# INILib
Библиотека для более удобной работы с INI файлами!

# Установка
Зайдите в проект C#
![сосака](https://github.com/Ameterius/INILib/blob/main/wiki/vxod.png?raw=true "Пуста")
В моём случае, это пример как юзать эту либу

Видим эту фигу
![blob уже неактуален](https://raw.githubusercontent.com/Ameterius/INILib/main/wiki/figa.png "blob уже неактуален")

Теперь ищем пункт *Зависимости*
![всё же актуален](https://github.com/Ameterius/INILib/blob/main/wiki/pobeda.png?raw=true "всё же актуален")

Нажимаем правой кнопкой мыши и выбираем пункт помеченный красным цветом
![всё же актуален](https://github.com/Ameterius/INILib/blob/main/wiki/ifuml.png?raw=true "всё же актуален")

И жмём кнопку *Обзор...*
![вввв](https://github.com/Ameterius/INILib/blob/main/wiki/here.png?raw=true "вввв")
Затем выберите библиотеку с расширеннием .dll

И велл доне! Библиотека стоит как конь!

# Использование
В начало кода пропишите
```csharp
using IniFile;
```
Всё, библиотека используется в коде и вы можете использовать методы

#### Методы
*Открытие/Создание файла .ini*
```csharp
IniFile.IniFile(string FileName.ini);
```
> Учтите, файл создатся после записи или прописи значения / секции / ключа

*Запись/Пропись значения*
```csharp
IniFile.IniWriteValue(string section, string key, string value);
```
> В случае отсутствия секции, ключа они будут созданы с такими именами, которые они имеют методе

*Чтение значения ключа*
```csharp
IniFile.IniReadValue(string section, string key);
```
> Лучше использовать как переменную, типо так :
```csharp
var readed_value = IniFile.IniReadValue(string section, string key)
```
