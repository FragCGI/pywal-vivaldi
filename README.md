Go to ```vivaldi://experiments```

Check "Allow CSS modifications"

Create a custom CSS directory

ie: ```/home/user/.config/vivaldi/custom```

Go to ```vivaldi://settings/appearance/```

Edit Custom UI modifications and set it to the custom CSS directory

Copy ```vivaldi.css``` to ```/home/user/.config/wal/templates/```

Run pywal

Create link to custom CSS created by pywal:

ie: ```ln -s /home/user/.cache/wal/vivaldi.css /home/user/.config/vivaldi/custom/vivaldi.css```

Go to ```vivaldi://restart```
