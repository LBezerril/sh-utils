# sh-utils
Diversos utilitários em POSIX Shell

## [echolor](./echolor)
Colore uma mensagem de acordo com a cor informada.

**Uso**
```shell
echolor [-n] "String" COLOR
```

**Exemplo**
```shell
echolor "Texto em verde claro" LIGHTGREEN
```

**Opções**

`COLOR`

Uma das seguintes cores: `BLACK`, `BLUE`, `CYAN`, `DARKGRAY`, `GREEN`, `LIGHTBLUE`, `LIGHTCYAN`, `LIGHTGRAY`, `LIGHTGREEN`, `LIGHTPURPLE`, `LIGHTRED`, `ORANGE`, `PURPLE`, `RED`, `WHITE` ou `YELLOW`. Se outro valor for informado, a string não será colorida.

`-n`

Evita quebra de linha.
