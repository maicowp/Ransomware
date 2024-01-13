# Desafio Ransomware DIO

# Laboratório de teste para Encryption e Decryption.

Abaixo descrito o arquivo teste.txt aplicando a criptografia e posteriormente a descriptografia.
![image](https://github.com/maicowp/Ransomware/assets/81197664/6b80e864-1c44-4e86-a7a5-6e670ceb1c33)

De forma isolada, ao executar o encryption.py o arquivo teste.txt é criptografado e alterado nome para teste.txt.ransomwaretroll
![image](https://github.com/maicowp/Ransomware/assets/81197664/08f9c010-4fd9-43e6-8ff8-70e2246e6e09)

Imagem abaixo mostra o arquivo criptografado:
![image](https://github.com/maicowp/Ransomware/assets/81197664/d1db1370-8c5a-465a-85a5-754e2e2d029a)

Realizado descriptografia e arquivo teste.txt voltou ao normal:
![image](https://github.com/maicowp/Ransomware/assets/81197664/1ae64c50-d3b7-4809-95d3-d0f7f338b5d8)


Caso apresentar o erro ao executar o encrypter.py:
line2, in <module> import pyaes
ModuleNotFoundError: No mudule named 'pyaes'

Para solução, será necessário adicionar a biblioteca pyaes do Python: pip install pyaes
