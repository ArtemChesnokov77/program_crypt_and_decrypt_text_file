RU

1. Открываем файл "script_crypt_and_decrypt_text_file.py" через любую IDE.

2. Вводим в файле "data.txt" любой текст.

3. Убираем "#" перед строчкой "pyAesCrypt.encryptFile('data.txt', 'data.txt.aes', password)"

4. Ставим "#" перед строчкой "pyAesCrypt.decryptFile('data.txt.aes', 'dataout.txt', password)"

5. Запускам скрипт, вводим пароль. Получаем файл data.txt.aes (он будет содержать зашифрованный текст)

6. Ставим "#" перед строчкой "pyAesCrypt.encryptFile('data.txt', 'data.txt.aes', password)"

7. Убираем "#" перед строчкой "pyAesCrypt.decryptFile('data.txt.aes', 'dataout.txt', password)"

8. Запускаем скрипт, вводим пароль. Получаем файл "dataout.txt" (файл с расшифрованным текстом)

EN


1. Open the file `script_crypt_and_decrypt_text_file.py` using any IDE.

2. Enter any text in the file `data.txt`.

3. Remove the "#" before the line `pyAesCrypt.encryptFile('data.txt', 'data.txt.aes', password)`.

4. Add "#" before the line `pyAesCrypt.decryptFile('data.txt.aes', 'dataout.txt', password)`.

5. Run the script, enter the password. You will get the file `data.txt.aes` (it will contain the encrypted text).

6. Add "#" before the line `pyAesCrypt.encryptFile('data.txt', 'data.txt.aes', password)`.

7. Remove "#" before the line `pyAesCrypt.decryptFile('data.txt.aes', 'dataout.txt', password)`.

8. Run the script, enter the password. You will get the file `dataout.txt` (the file with the decrypted text).