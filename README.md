Installation:
  1. Make sure you're using python version 3.6+ to run the code successfully.You can find out with the **python -V**.
  2. Download the source code. Type **https://github.com/Stakepy/telegram-clock** in the Terminal or just download the [zip](https://github.com/Stakepy/telegram-clock/archive/master.zip).
  3. First of all you need to install some libraries with commands:
  4. pip3 install PyTelegramBotAPI
  5. pip3 install telethon
  6. pip3 install opencv-python

For a successful launch, you need:
  1. In the config/config.py file, change the api details to your own. Here you can find api_id and api_hash (https://my.telegram.org/auth)
  2. Being in the same folder as requirements.txt type pip install -r requirements.txt in the terminal.
  3. Being in the same folder as main.py enter python main.py in the terminal

PS:  If you want to change the time zone, you need to change from e.g. "default=valid_tz('Europe/Kiev')" to "default=valid_tz('Your Timezone')" in the file main.py
