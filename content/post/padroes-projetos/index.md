---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Padroes de Projetos"
subtitle: "Padroes de Projetos na liguagem de programação Ladder"
summary: ""
authors: []
tags: []
categories: []
date: 2021-11-26T14:36:17-03:00
lastmod: 2021-11-26T14:36:17-03:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image: "tia-portal-kop-editor.png"
  caption: "Portal TIA - Siemens"
  focal_point: "Center"
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
# Introdução
Quando eu estava na graduação eu tive uma cadeira de padrões de projetos de desenvolvimento de software, o curso focava 100% em estudar os padrões do GORF (Padrões de Projetos: Soluções Reutilizáveis). Mais tarde, no mestrado, eu me encantei e passei algumas horas da vida folheando o livro do Fowler (Patterns of Enterprise Application Architecture). Ficava encantando como esses livros mostravam trechos de códigos e arquiteturas que poderiam ser utilizadas e reutilizadas por profissionais do desenvolvimento de software, muitas vezes esses livros e outros eram realmente complicados, mas davam uma sensação de que era a forma correta de se escrever código e de se construir um sistema.

No mês passado tive da manutenção e adicionar funcionalidades em um sistema de automação de uma fabrica que estava sendo ampliada. Foi nesse momento que começou aquela sensação de estranhamento inicial que me incomodou bastante todo código que esse programador primário fez parecia pra mim um código macarrônico, prolixo e sem qualquer tipo de estrutura ou padrão, sendo justo com o rapaz, ele escrevia bons comentários, que foi o que me ajudou bastante. 

Primeiro, vamos ao simples, o código do software de supervisão estava razoavelmente bem escrito, tentava dar uma cara de programação orientada a objetos e apesar de ter falhado em alguns momentos no geral foi bom. Mas quando eu abri o código do CLP, foi como dito acima e aquele desejo de “apagar tudo e fazer do meu jeito do zero” veio a tona (como sempre nesses casos). Mas ai que eu pensei, quem disse que do meu jeito é o jeito certo ou o melhor jeito de escrever aquelas rotinas?

Enfim, resolvi criar um pouco de coragem e pesquisar o que a ciência da Engenharia da Automação e Controle tem pra nos oferecer no que eu vou chamar de padrão de projetos para automação (Sim igual o nome usado no desenvolvimento de Software mesmo, vejo muitos paralelos). A tentativa dessa série de artigos é transcrever aqui tudo que for descobrindo (tal qual James T. Kirk) e quando possível complementar com a minha experiencia.

**TL;DR**

Vou reunindo aqui informações sobre padrões de projetos no desenvolvimento de projetos para automação e controle.

# Padroes de Codigo
Mapeamento
