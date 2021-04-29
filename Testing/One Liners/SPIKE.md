## Alias Script
```bash
echo "alias copy = 'xclip -selection clipboard'" >> ~/.bashrc
```

## Export Files
```bash
zip -r spike.zip spike/
python -m http.server 12121
```

## SSH Local Port Bind
```bash
ssh -J anthony@52.70.247.48 anthony@localhost -p PORT -ND 2324
```