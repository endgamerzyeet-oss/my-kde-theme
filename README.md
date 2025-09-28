# my-kde-theme
Theme I'm making. If something is freedesktop.org compatible, it should work, I don't know.

# Added things
The XML file is for the .pixil file type and is not strictly necessary. However, this pack is built to suit my needs, and I built every icon using https://www.pixilart.com/ , which saves to .pixil files. Soon (again, because I need them), I will be making .png and .svg icons. That's how the flow works

If you want to use my icon for .pixil files, in the prompt run:

```
mkdir -p ~/.local/share/mime/packages
cp ./application-x-pixil.xml ~/.local/share/mime/packages
update-mime-database ~/.local/share/mime
```

If you decide you don't need it (and you probably don't), don't worry:

```
rm ~/.local/share/mime/packages/application-x-pixil.xml
update-mime-database ~/.local/share/mime
```

It's that easy! (Don't screw it up)
