# random_wallpaper
Python shell script which downloads random picture from unsplash and set it as wallpaper

### Disclaimer 
Wallpapers are downloaded at random , I take no responsibility for any inappropriate content.
- **`Wallpaper source`** : <a href="https://unsplash.com/">unsplash</a>  

### Dependencies

Install following programs on your system.

- **`python >= 3 `** : It's a python script
- **`feh`** : to set wallpaper

### Settings image resolution

change the BASEURL in random_wallpaper file by adding the required resolution in url 
- Example Setting resolution to 1920x1080
```bash
BASEURL = 'https://source.unsplash.com/random/1920x1080'
```

### Running
Clone the repo and cd into the directory
```bash
$ git clone https://github.com/CH4ND4N-x/random_wallpaper.git
$ cd random_wallpaper
```
Give execute permission
```bash
$ chmod +x random_wallpaper
```
Ececute
```bash
$ ./random_wallpaper
```
To retain the wallpaper after reboot, execute ~/.fehbg in either config or autostart file of your window manager

- for i3wm add this to config
```bash
$ exec_always ~/.fehbg
```
- for open box add this to autostart file 
```bash
$ ~/.fehbg &
```
