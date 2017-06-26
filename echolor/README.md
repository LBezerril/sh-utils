# echolor
Color a message according to informed color.

## How to use
```shell
echolor [-n] "String" COLOR
```

## Example
```shell
echolor "Light green text" LIGHTGREEN
```

## Options

`COLOR`

One of the following colors: `BLACK`, `BLUE`, `CYAN`, `DARKGRAY`, `GREEN`, `LIGHTBLUE`, `LIGHTCYAN`, `LIGHTGRAY`, `LIGHTGREEN`, `LIGHTPURPLE`, `LIGHTRED`, `ORANGE`, `PURPLE`, `RED`, `WHITE` or `YELLOW`. If another value is informed, the string will not be colored.

`-n`

Do not output the trailing newline.
