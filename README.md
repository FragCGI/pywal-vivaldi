Go to vivalid://experiments
Check "Allow CSS modifications"

Make custom CSS directory
  ie: /home/user/.config/vivaldi/custom

Go to:
  vivaldi://settings/appearance/
  Edit Custom UI modifications
    Set to custom CSS directory

Copy vivaldi.css to /home/user/.config/wal/templates/

Run pywal

Create link to custom CSS created by pywal:
  ln -s /home/user/.cache/wal/vivaldi.css /home/user/.config/vivaldi/custom/vivaldi.css

Go to:
  vivaldi://restart
