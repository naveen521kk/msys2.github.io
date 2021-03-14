---
title: Write protecing Install Folder
summary: 
---

# Write protecing Install Folder

Write protecting install folder(`C:\msys64`) can help in many ways. For example, in you are using pip to install a package, it will happily write to `/mingw64/lib/python3.8/site-packages` which will create conflicts when you are installing the same using Pacman.

## Steps:

1. Go to the directory where you installed msys2, usually `C:\msys64`.
2. Then Right-Click and click on Properties
3. Go to Security tab and Select Advanced
4. 
