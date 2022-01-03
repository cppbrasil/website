+++
title = "Contribuindo"
description = "Como contribuir com a sessão blog do Cpp Brasil."
date = 2022-01-03T08:50:45+00:00
draft = false
template = "blog/page.html"

[taxonomies]
authors = ["Patrick"]

[extra]
lead = "Este post explica como pessoas podem contribuir com o nosso blog!"

+++

# Como funciona

O website do Cpp Brasil é criado utilizando o [Zola](https://www.getzola.org), um gerador de sites estaticos.
Com isso, é possivel escrever posts utilizando markdown com uma estrutura definida estrutura.

Um exemplo minimo pode ser encontrado no post [Hello World](@/blog/202201-hello-world.md), onde o código é definido como:

```md
+++
title = "Hello World"
description = "Primeiro post do blog!"
date = 2022-01-03T08:50:45+00:00
draft = false
template = "blog/page.html"

[taxonomies]
authors = ["Patrick"]

[extra]
lead = "Este é o nosso primeiro posto do blog <b>Cpp Brasil</b>!"

+++

O primeiro de muitos!
```

O arquivo se encontra dentro da pasta `content/blog`, onde os posts devem ser incluidos.
Para facilitar a organização, o arquivo tem o seguinte formato de nome: `XXXXYY-blog-title.md`,
onde XXXX é o ano e YY o mês.

Para adicionar informação sobre o autor do blog, basta adicionar um novo arquivo com o nome do autor em `content/authors`,
utilizando o seguinte template.

```
+++
title = "Patrick Pereira"
description = "Random Open Source developer."
date = 2022-01-03T08:50:45+00:00
draft = false
+++

Random Open Source developer.

[@patrickelectric](https://github.com/patrickelectric)
```
