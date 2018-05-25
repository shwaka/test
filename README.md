シンタックスハイライトのtest

```python
def hoge(n):
    return n*10
```

```tex
\documentclass{article}

\begin{document}
\begin{equation*}
  \int_0^1x dx = \frac{1}{2}
\end{equation*}

\end{document}
```

```console
$ ls | grep hoge
$ for f in *; do rm $f; done
```

```ShellSession
$ cd /tmp
$ PS1='$ '
```

# from why_CUI.md

```ShellSession
for i in a b c d e; do echo "hoge $i" > test$i.txt; done
for i in a b c d e; do mv test$i.txt hoge$i.txt; done
for i in a b c d e; do rm hoge$i.txt; done
```

```ShellSession
for f in *.tex; do platex $f; dvipdfmx ${f/tex/dvi}; done
```

```ShellSession
$ for i in a b c d e; do echo "hoge $i" > test$i.txt; done
$ for i in a b c d e; do mv test$i.txt hoge$i.txt; done
$ for i in a b c d e; do rm hoge$i.txt; done
```

```ShellSession
$ for f in *.tex; do platex $f; dvipdfmx ${f/tex/dvi}; done
```
