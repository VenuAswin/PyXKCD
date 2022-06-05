# PyXKCD
A python script to show random XKCD comics.  
You need feh image viewer installed.
Downloads a random xkcd comic into the temporary filesystem, ```/tmp``` and used ```feh``` to view the image. Place the code in your PATH, make in executable, and run the command.
You can use ```xdg-open``` instead of ```feh``` in the source code to use your default image viewer

```python
def show_image(self) :
        subprocess.Popen(["feh", "/tmp/image"]) #replace feh with xdg-open
        exit()
```

```bash
chmod u+x pyxkcd  #make is executable
pyxkcd #runs the program 
```
