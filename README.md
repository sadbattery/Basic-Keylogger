

![header](https://capsule-render.vercel.app/api?type=slice&height=300&color=gradient&customColorList=0,2,2,5,4,6,8,10,12,14,16,20,30&text=Basic%20Keylogger&fontSize=50&fontAlign=54&rotate=19&fontAlignY=45&textBg=false&animation=twinkling)

<div><p align="left"> <img src="https://komarev.com/ghpvc/?username=sadbattery&label=PageViews:"/></p></div>
A basic Python keylogger program that records keystrokes and saves them to a file using the `pynput library`


### Libraries Used:
+ `pynput`



## How to Use:
+ Run using [Jupyter NoteBook](https://jupyter.org/) or any Python IDE.  

### `For V1.0`

##### How to Run:
+ Run the script and it will start capturing the keystrokes.
##### How to stop:
+ Just press the `Esc Key` to stop the script.

+ It will create a file named `keylog.txt` in the folder from where the script is running.

#### Event Handlers:
+ `on_press(key):` This function is called whenever a key is pressed. It appends the pressed key to the logged_keys list. If the pressed key is a special key (like Shift, Ctrl, etc.), it's converted to a string and logged.
+ `on_release(key):` This function is called whenever a key is released. If the Esc key is pressed, it returns False to stop the listener.


### `For V1.1` 

> Working on it using libraries `threading`,`win32gui` and `psutil`

## Installation:

#### ***pynput :***
> It provides functions to monitor and control the keyboard.
```bash
pip install pynput
```
