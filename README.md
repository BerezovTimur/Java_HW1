### Отчёт о тестировании приложения KeyValidator

03/04/2020 было проведено:
- тестирование установки приложения KeyValidator
- тестирование документации приложения KeyValidator
- дымовое тестирование приложения KeyValidator.

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:

- ошибка в документации https://github.com/BerezovTimur/Java_HW1/issues
- ошибка ключа 80b427f8-92cd-3aae-ba04-03927fbe17c6 https://github.com/BerezovTimur/Java_HW1/issues/2
- ошибка ключа 387eedc6-12e9-3b32-9881-63b6b5e85317 https://github.com/BerezovTimur/Java_HW1/issues/3
- ошибка ключа 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 https://github.com/BerezovTimur/Java_HW1/issues/4

В процессе тестирования использовались следующие тест-план:

 1. Скачать файл по адресу https://github.com/netology-code/javaqa-homeworks/raw/master/intro/artifacts/KeyValidator.class
 2. Открыть руководство пользователя по адресу https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md
 3. В папке со скаченным файлом (KeyValidator.class) запустить Git Bash
 4. В консоли Git Bash убедиться в наличии установленной Java командой java -version.
 5. В консоли Git Bash запустить файл KeyValidator.class командой java KeyValidator <необходимый ключ>
 6. Наблюдать результат

В качестве тестовых данных использовались данные из "Руководство использования KeyValidator":

Валидные ключи:

- 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
- 80b427f8-92cd-3aae-ba04-3927fbe17c6
- b295bc63-9f03-3b4b-af80-969b39f8c262
- 387eedc6-12e9-3b32-9881-63b6b5e85317
- c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180

Невалидные ключи:

- 18252235-78e0-44a5-8720-556f0c7da17a
- e66075b6-ddad-445e-baf6-161b3289522b
- b6d53250-f07e-4352-a293-6102ddf7f1ca
- c2bc778a-1cb9-46c6-b435-0489649d2a42
- 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

Тестирование производилось в следующем окружении:

- Windows 10 64 bit
-  Java 11.0.6
