# Integrando o uso de Python e R

Este é o output!!

A função do R `system("python script.py")` irá executar o [script em python](https://github.com/gomesfellipe/python-Rmarkdown/blob/master/CodigoTestePython.py) que gera e salva a imagem [foo.png](https://github.com/gomesfellipe/python-Rmarkdown/blob/master/foo.png), veja:

```{r}
system("python CodigoTestePython.py")
```
Após isso, basta introduzir a imagem com o comando `![descrição da imagem](local da imagem)` que irá aparecer como no exemplo:

![](foo.png)
