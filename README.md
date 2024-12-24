## Password Manager

An Open Source Password Manager for Linux

</br>

*** This is a backup mirror used for testing, imported from github.com/zah20/pwmgr ***

</br>

[Term Paper](https://docs.google.com/document/d/1WU1DhhxxY864XlWm3pJDy-Znjz2RGEpEWyLOp9jbST8/edit?usp=sharing)

[Guide](https://docs.google.com/document/d/1ZrvNczTJIdKSOdlyhuAYqRsed6BR6HrJmqbaNvtLkSU/edit)

[Tutorial](https://www.dropbox.com/s/e81sbk9qaur742l/pwmgr_test.mp4?dl=0)

</br>

** Update Video (July, 2024) **
[Primary Link](https://www.youtube.com/watch?v=j6-eMU_bG4o)
[Backup Link](https://www.dropbox.com/scl/fi/srovv2xxgoudcc7al3zzz/pwmgr_update_07_2024.mp4?rlkey=l2h18w8jna7c6adgk3ww54j9a&st=24vy4zau&dl=0)

</br>
</br>

####                        Installation (Step#1)

Ubuntu:
```

  sudo apt-get install -y git dmenu xclip wxpython-tools keyutils python3-pip libc6

```

Manjaro / Arch Linux:
```

  sudo pacman -S --noconfirm git dmenu xclip python-wxpython keyutils python-pip glibc 

```

</br>

####                        Installation (Step#2)

Python Dependencies

```

  pip3 install --user --break-system-packages getch fernet

```

