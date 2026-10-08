# Ligniumelement website

## Optim image

- Copy paste then run

```
fd -e jpg -e jpeg -e png . ./src/assets/images -x sh -c 'sharp -i "$1" -o "$(dirname "$1")" -f webp && rm "$1"' _ {}
```
