# IIvMobS-2-LR4
Вся лаба по сути уже написана в ЛМС. 
# Установка зависимостей
Заходим в командную строку в проекте и вводим следующие команды:
1) pip install SpeechRecognition
2) pip install gTTS
3) pip install PyAudio (возможно возникновение ошибки) Если возникла ошибка - просто скачайте PyAudio в интернете и установите через команду pip install <название скачанного файла> 
4) pip install pyttsx3 pypiwin32

Остается лишь добавить свои варианты фраз в данное место в коде
![image](https://github.com/namedvice/IIvMobS-2-LR4/assets/52739357/2807a8cc-1d4b-421c-91de-b5cc5e88ebef)

Мой пример:
elif 'say hi' in zadanie:
        talk('Haaaaaaaaaaaaay!')
    elif 'say why' in zadanie:
        talk('WOOOOOOOOOOOOAH!')
    elif 'say you' in zadanie:
        talk('Ooooooooooh!')

        location = command()
    elif 'play music' in zadanie:
        talk('papaaa ba baaaaaaa!')
    elif 'keep counting' in zadanie:
        talk('one, two, three, four!')
    elif 'my name is' in zadanie:
        talk('nice to meet you! my name is ...')
