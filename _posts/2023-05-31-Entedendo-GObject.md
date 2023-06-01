---
title: Entedendo GObjects
published: true
---

## Introdução:

Estou começando a estudar o GTK4 mas para isso é preciso conhecer a GLib. 
Este post vai ser um overview sobre o que é o GObject e como ele funciona.

* * *
## O que é o GObject?

O GObject é uma biblioteca que implementa um sistema de objetos para a linguagem C, ele faz parte da bilioteca GLib e é utilizado por varios softwares como GTK, GStreamer, e diversos aplicativos do projeto Gnome.

Para que já esta familiarizado com o paradigma de orientação a objetos (OO) vai ser mais facil de entener, se voce não esta acostumado a utilizar nenhuma linguagem com OO, recomendo que leia um pouco sobre o assunto antes de continuar.

Recaptulando um pouco sobre a linguagem C, ela é uma linguagem de programação de baixo nivel, ou seja, ela é uma linguagem que esta mais proxima da linguagem de maquina e não possuiu muitos dos recursos que os programados que utilizam linguagem mais "modernas" como Python, Java e C# estão acostumados, como a Orientação a objetos e gerenciamento automatico de mememoria (Garbage Collector).

Não entenda isso como uma critica a linguagem C, enquanto outras linguagens entregam algumas abstrações que simplificam a vida dos desenvolvedores, a linguagem C entrega um controle maior sobre o que esta acontecendo no seu programa, o que pode ser muito util em alguns casos, mas tras uma complexidade maior para o desenvolvedor.

Uma grande vantagem do GObject, que não fica tão clara a primeira vista, é que sendo um sistema de objectos escrito em C, as classes (GObject) definidos em C podem ser usados em qualquer linguagem que possa chamar uma biblioteca em C, e isso inclui praticamente todas as linguagens de programação.


* * *
## Preparando o ambiente de desenvolvimento


* * *
## Primeiro exemplo



* * *
## Referencias
*   [GObject Tutorial](https://docs.gtk.org/gobject) 
*   [GObject Documentation](https://docs.gtk.org/gobject/tutorial.html)
*   [GObject Tutorial By ToshioCP](https://github.com/ToshioCP/Gobject-tutorial) 


* * *

Text can be **bold**, _italic_, ~~strikethrough~~ or `keyword`.

[Link to another page](another-page).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# [](#header-1)Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## [](#header-2)Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### [](#header-3)Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### [](#header-4)Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### [](#header-5)Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### [](#header-6)Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![](https://assets-cdn.github.com/images/icons/emoji/octocat.png)

### Large image

![](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
