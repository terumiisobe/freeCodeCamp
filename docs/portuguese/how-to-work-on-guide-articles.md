# Como trabalhar em artigos de Guia

Com a sua ajuda, nós podemos criar uma ferramenta de referência compreensível que irá ajudar milhões de pessoas que estão aprendendo a programar nos próximos anos. 💛

Você pode:

- [Ajudar Criando e Editando Artigos de Guia](#steps-for-creating-and-editing-guide-articles).
- [Ajudar revisando <i>pull requests</i> para Artigos de Guia]()

## Passos para Criar e Editar Artigos de Guia

1. 🍴 [Fazer <i>fork</i> a este repositório](https://github.com/freeCodeCamp/freeCodeCamp#fork-destination-box)
2. 👀️ Seguir as instruções de contribuição listadas abaixo.
3. 🔧 Fazer algumas mudanças impressionantes!
4. 📖 Ler este [guia de melhores práticas](/docs/style-guide-for-guide-articles).
5. 👉 [Fazer um <i>pull request</i>](https://github.com/freeCodeCamp/freeCodeCamp/compare)
6. 🎉 Ter o seu <i>pull request</i> aprovado - sucesso!

Ou apenas [crie uma <i>issue</i>](https://github.com/freeCodeCamp/freeCodeCamp/issues) - qualquer pequena ajuda conta! 😊

### [Siga estas instruções recomendadas do nosso Guia de Estilo para um artigo de Guia mais atraente](/docs/style-guide-for-guide-articles.md)

### Criando um <i>Pull request</i> (PR) para propor mudanças

Existem duas maneiras de propor uma mudança ao repositório, depois de editar ou adicionar um artigo de Guia:

- [Usando a interface web GitHub no seu <i>browser</i>](#using-the-github-web-interface-on-your-browser).
- [Trabalhando na máquina pessoal](#working-on-your-local-machine) (_recomendado_ para pré-visualizar as mudanças).

#### Usando a interface web GitHub no seu <i>browser</i>

Assista a demonstração no vídeo ou siga os passos abaixo:

**[A FAZER]** Atualizar a gravação do GIF.

![GIF mostrando os passos da interface GitHub](#)

1. Vá até a pasta **"pages"** (localizada no [`guide`](/guide)) e encontre o artigo raíz que gostaria de escrever ou editar.

    > Todos os artigos estarão num arquivo index.md

2. Clique no <kbd>Edit this file</kbd> ícone com o lápis e faça as suas mudanças ao arquivo no <i>GitHub-flavored Markdown</i>.

    > Se o icon estiver cinza e dando o aviso "You must be on a branch to make or propose changes to this file", então você está provavelmente na <i>tree</i> de outra pessoa. No canto superior esquerdo da página, terá uma caixa para seleção que dirá "Tree: #######". Clique na opção e mude o <i>branch</i> para "master". Agora o ícone lápis deve estar clicável.

3. Vá até ao fim da tela e adicione uma mensagem de <i>commit</i> explicando as suas mudanças.

    (Opcional): Nós recomendamos fortemente que você faça uma mensagem de <i>commit</i> convencional. Isto é uma boa prática que você verá em alguns dos repositórios <i>Open Source</i> mais populares. Como developer, isto vai te encorajar a seguir as práticas padrão.

    Alguns exemplos de mensagens de <i>commit</i> convencionais:

    ```md
    fix: update HTML guide article
    fix: update build scripts for Travis-CI
    feat: add article for JavaScript hoisting
    docs: update contributing guidelines
    ```

    Mantenha-as curtas, não mais que 50 caracteres. Você sempre pode adicionar mais informações na descrição da mensagem de <i>commit</i>.

    Isto não leva tempo adicional comparado com uma mensagem não convencional como 'update file' ou 'add index.md'

    Você pode aprender mais [aqui](https://www.conventionalcommits.org/en/v1.0.0-beta.2/#why-use-conventional-commits).

4. Então, selecione a opção para **"Create a new branch for this commit and start a pull request"** e clique em <kbd>Propose file changes</kbd>.

5. No próxima tela você poderá adicionar outros detalhes sobre o seu PR, depois clique em <kbd>Create pull request</kbd>.

Parabéns 🎉! Você acabou de criar um <i>pull request</i>.

#### Trabalhando na máquina pessoal (_recomendado_ para pré-visualizar mudanças)

Não é obrigatório trabalhar na sua máquina pessoal, a não ser que queira pré-visualizar as suas edições ou trabalhar com correções de <i>UI</i> e otimizações. Este método também é recomendado caso encontre problemas com git como conflitos de <i>merge</i>, <i>rebasing</i>, etc.

##### Leia estas recomendações em [Como configurar o freeCodeCamp localmente](/docs/how-to-setup-freecodecamp-locally.md)

### Ter um PR aceito

Aqui estão algumas instruções que os <i>reviewers</i> seguem ao analisar PRs:

- tem uma descrição e título relevantes
- o PR respeita o [guia de estilo](/docs/style-guide-for-guide-articles)
- nós seguimos dicas QA padrão encontradas em [Directrizes de Moderador](https://forum.freecodecamp.org/t/freecodecamp-moderator-guidelines/18295)
- desde que um <i>pull request</i> melhore ou expanda o guia, nós aceitamos mesmo que contenha Inglês imperfeito ou conteúdo incompleto
- <i>pull requests</i> mais antigos são analisados primeiro

#### Etiquetas

- **content** é para <i>pull requests</i> que modificam o conteúdo dos artigos no guia (adicionam um novo artigo ou atualisam um já existente)
- **duplicate** é para <i>pull requests</i> que têm o mesmo conteúdo que outro PR aberto
- **changes requested** é para <i>pull requests</i> que precisam de mudanças antes de serem <i>merged</i>
- **stale** é para <i>pull requests</i> com uma <i>label</i> _"changes requested"_  que não tem atividade após 2 semanas e será fechado em seguida
  - Um <i>pull requests</i> _stale_ deve ser fechado.
  - Aqui está [um exemplo](https://github.com/freeCodeCamp/freeCodeCamp/pull/235).

#### Conteúdo Conflitante/Duplicado

UM PR é considera um **duplicado** se faz mudanças ao mesmo artigo que outro PR.

Em geral, um <i>reviewer</i> irá:

1. Ordenar PR por mais antigo
2. Procurar PRs com conteúdo similar
3. <i>Merge</i> do mais antigo para o mais recente

É muito provável que existirão conflitos de <i>merge</i> com PRs duplicados.

<i>Reviewers</i> farão todos os esforços para resolver estes conflitos e combinar os PRs duplicados.

#### Pedir Mudanças

Se um <i>pull requests</i> não é perfeito, o <i>reviewer</i> poderá:

- pedir mudanças ao contribuidor e adicionar a <i>label *changes requested*</i>
- consertar problemas menores e fazer um <i>commit</i> acima do PR

#### Travis CI Build

Todos os PRs devem passar a verificação do Travis CI antes de acontecer o <i>merge</i>.

Se um PR quebra o <i>build</i> (uma verificação Travis CI falha e mostra um "X" vermelho) existem três causas prováveis.

Você precisará de resolver o provlema antes de podermos <i>merge</i> o teu PR:

1. O seu PR cria um novo artigo e falta o ficheiro 'index.md' em algum lugar.
    - Todas as pastas no `src/pages` precisam de um arquivo `index.md` (e o nome deve ser `index.md`).
    - Dois cenários prováveis são
      - você nomeou o arquivo do novo arquivo diferente de `index.md`, ou
      - você criou a ambos uma nova pasta, e uma sub-pasta, e escreveu o novo artigo na sub-pasta mas esqueceu de colocar um arquivo `index.md` na nova pasta
2. O teu PR criou uma nova pasta e o nome da pasta não está formatado corretamente.
    - O nome da sua pasta deve ser todo em minúsculo e formatado em <i>kebab-case</i> (ex. minha-nova-pasta).
3. O artigo não tem o campo `title` no topo.
    - Por favor leia a seção do [Title](#title) abaixo, em seguida de  [Guia de Estilo para escrever artigos](/docs/style-guide-for-guide-articles.md).

### Quando fechamos um <i>pull requests</i>

Nós fechamos PR
- se um PR mais antigo do mesmo artigo é <i>merged</i> e o seu PR não adiciona conteúdo novo
- se há nunhum/pouco esforço nele(ex.: copiar e colar de outra fonte como a Wikipédia)
- se há texto copiado de uma fonte com </i>copyright</i>i - ver [problema de citação](https://github.com/freeCodeCamp/freeCodeCamp/issues/2503)
- se não respeita o [Guia de Estilo para escrever artigos](/docs/style-guide-for-guide-articles.md)
- se não respeita o [Academic Honesty policy](https://www.freecodecamp.org/academic-honesty)
- se está parado (se a mudança é pedida e não há atividade durante duas semanas)

Também, se estiveres trabalhando em um artigo <i>"stub"</i>, as tuas mudanças devem ser substanciais o suficiente para substituir o texto <i>stub</i>.

Não aceitamos um PR que só adiciona links à seção de "Mais Informação:".

O repositório tem um script `Normalise.js` que adiciona atributos a links, mas também procura o texto "This is a stub..." via um RegEx.

Se encontrado, vai reverter o artigo texto de volta para o texto <i>stub</i> genérico (e apagar as suas mudanças).

Este é comportamento pretendido, visto que nos permite atualizar todos os <i>stubs</i> se o <i>template stub</i> mudou por alguma razão.

### Conseguir Ajuda

Existe uma comunidade de suporte de uma equipa inteira de contribuidores, com quem poderá trocar ideias e pedir opiniões sobre a sua escrita.

Mantenha-se ativo no [chat room de contribuidores](https://gitter.im/freecodecamp/contributors) e faça muitas perguntas.

---

## Passos para revisar <i>pull requests</i> para artigos de Guia

> Esta secção é direccionada a <i>reviewers</i> deste repositório.

## Squash e Merge

Nós usamos a opção <kcd>Squash and merge</kcd> quando combinamos o PR que mantém o histórico de <i>commits</i> limpo.

![GIF - Squash and merge](https://files.gitter.im/FreeCodeCamp/Contributors/56MQ/9cb8db153d7bb1b3576cd1ffc207e39d.gif)

### Filtrando PRs

> PR, Open, Oldest First, Travis CI Build successful, no one assigned, no comments

[`is:pr is:open sort:updated-asc status:success no:assignee comments:0`](https://github.com/freeCodeCamp/freeCodeCamp/pulls?utf8=%E2%9C%93&q=is%3Apr%20is%3Aopen%20sort%3Aupdated-asc%20status%3Asuccess%20no%3Aassignee%20comments%3A0)

> PR, Open, Oldest First, Does not have labels: `platform`, `enhancement`, `invalid` or `changes requested`

[`is:pr is:open sort:updated-asc -label:platform -label:enhancement -label:invalid -label:"changes requested"`](https://github.com/freeCodeCamp/freeCodeCamp/pulls?utf8=%E2%9C%93&q=is%3Apr%20is%3Aopen%20sort%3Aupdated-asc%20-label%3Aplatform%20-label%3Aenhancement%20-label%3Ainvalid%20-label%3A%22changes%20requested%22).

### Templates

> Você pode criar o seu próprio templates na feature do GitHub [**Saved replies**](https://github.com/settings/replies/) ou usar os abaixo.

#### Agradecimento

Em inglês:
```markdown
Thank you for your contribution to the page! 👍
We're happy to accept these changes, and look forward to future contributions. 🎉
```

Em português:
```markdown
Obrigado pela sua contribuição à página! 👍
Estamos muito felizes em aceitar estas mudanças e esperamos ver mais contribuições suas no futuro. 🎉
```

#### Agradecimento e parabenização

> Para agradecer e encorajar a primeira contribuição de um contribuidor.

Em inglês:
```markdown
Hi @username. Congrats on your first pull request (PR)! 🎉

Thank you for your contribution to the page! 👍
We're happy to accept these changes, and look forward to future contributions. 📝
```

Em português:
```markdown
Olá @username. Parabéns pelo seu primeiro pull request (PR)! 🎉

Obrigada pela sua contribuição para a página! 👍
Estamos muito felizes em aceitar estas mudanças e esperamos ver mais contribuições suas no futuro. 📝
```

#### Erro de Build

Em inglês:
```markdown
Hey @username

So I'd love to be able to merge your changes but it looks like there is an error with the Travis CI build. ⚠️

Once you resolve these issues, I will be able to review your PR and merge it. 😊

Em português:
```markdown
Olá @username

Adoraria juntar as suas mudanças mas parece que há um erro com o Travis CI build. ⚠️

Assim que resolver este problema, poderei rever o teu PR e combinar ao repositório. 😊

---

> Fique à vontade para referenciar o [Guia de Estilo para escrever artigos](https://github.com/freeCodeCamp/freeCodeCamp#article-title) para este repositório na maneira correta de formatar um artigo para que o seu Travis CI build seja aprovado. ✅
>
> Também é uma boa prática no GitHub escrever uma breve descrição das suas mudanças quando cria um PR. 📝
```

#### Syncing Fork

> Quando o PR não está atualizado quanto ao `master` <i>branch</i>.

Em inglês:
``````markdown
Hey @username

So I'd love to be able to merge your changes but it looks like there is an error with the Travis CI build. ⚠️

```bash
Error: ENOTDIR: not a directory, open 'src/pages/java/data-abstraction/index.md'
```

This particular error was not actually caused by your file but was an old error caused by merging faulty code to the `master` branch. It has since been resolved.

To pass the build, you will have to sync the latest changes from the `master` branch of the `freeCodeCamp/freeCodeCamp` repo.

Using the command line, you can do this in three easy steps:

```bash
git remote add upstream git://github.com/freeCodeCamp/freeCodeCamp.git

git fetch upstream

git pull upstream master
```

If you're using a GUI, you can simply `Add a new remote...` and use the link `git://github.com/freeCodeCamp/freeCodeCamp.git` from above.

Once you sync your fork and pass the build, I will be able to review your PR and merge it. 😊

Em português:
``````markdown
Olá @username

Adoraria juntar as suas mudanças mas parece que há um erro com o Travis CI build. ⚠️

```bash
Error: ENOTDIR: not a directory, open 'src/pages/java/data-abstraction/index.md'
```

Este erro em particular não foi causado pelo seu arquivo mas por um erro antigo causado pelo <i>merge</i> de código defeituoso ao `master` <i>branch</i>. Mas ele foi resolvido.

Para ser aprovado, você terá que sincronizar as mudanças mais recentes do `master` <i>branch</i> do repositório do `freeCodeCamp/freeCodeCamp`.

Usando a linha de comando, você poderá fazer isto em três passos fáceis:

```bash
git remote add upstream git://github.com/freeCodeCamp/freeCodeCamp.git

git fetch upstream

git pull upstream master
```

Se estás a usar um GUI, pode simplesmente `Add a new remote...` e usar o link `git://github.com/freeCodeCamp/freeCodeCamp.git` acima
Assim que resolverer este problema, poderei rever o teu PR e juntar ao repositório. 😊

---

> Fique a vontade para referênciar o artigo de [Sincronizar um Fork](https://help.github.com/articles/syncing-a-fork/) do GitHub para mais informação em como manter o teu <i>fork</i> atualizado com o repositório principal. 🔄
>
> Também é uma boa prática no GitHub escrever uma breve descrição das suas mudanças quando cria um PR. 📝
``````

#### Conflitos de Merge

> Quando o PR tem conflitos de merge que precisam ser resolvidos.¹

Em inglês:
```markdown
Hey @username

So I'd love to be able to merge your changes but it looks like you have some merge conflicts. ⚠️

Once you resolve these conflicts, I will be able to review your PR and merge it. 😊

---

> If you're not familiar with the merge conflict process, feel free to look over GitHub's guide on ["Resolving a merge conflict"](https://help.github.com/articles/resolving-a-merge-conflict-on-github/). 🔍️
>
> Also, it's good practice on GitHub to write a brief description of your changes when creating a PR. 📝
```

Em português:
```markdown
Olá @username

Adoraria juntar as suas mudanças mas parece que tem alguns conflitos de <i>merge</i>. ⚠️

Assim que resolver estes problemas, poderei rever o seu PR e juntar ao repositório. 😊

---

> Se não estivere familiarizado com o processo de conflito de <i>merge</i>, consulte o guia do GitHub quanto a ["Resolver um conflito de merge"](https://help.github.com/articles/resolving-a-merge-conflict-on-github/). 🔍️
>
> Também é uma boa prática no GitHub escrever uma breve descrição das suas mudanças quando cria um PR. 📝
```

¹ Se é um utilizador a contribuir pela primeira vez tem um problema de <i>merge</i> os <i>mantainers</i> irão resolver o conflito por eles.

#### Duplicado

> Quando um PR é repetitivo ou duplicado.

Em inglês:
```markdown
Hey @username

It seems that similar changes have already been accepted earlier for this article you're editing, sorry about that. 😓

If you feel you have more to add, please feel free to open up a new PR.

Thanks again! 😊

> Hey @username

It seems that similar changes have already been accepted earlier for this article you're editing, sorry about that. 😓

If you feel you have more to add, please feel free to open up a new PR.

Thanks again! 😊

---

> If you have any questions, feel free to reach out through [Gitter](https://gitter.im/FreeCodeCamp/Contributors) or by commenting below. 💬
```

Em português:
```markdown
Olá @username

Parece que mudanças semelhantes já foram aceites antes para este artigo que está editando, desculpe. 😓

Se achar que tem mais a adicionar, fique à vontade para abrir outro PR.

Obrigado mais uma vez! 😊
---

> Se tem alguma dúvida, nos contate através do [Gitter](https://gitter.im/FreeCodeCamp/Contributors) ou comentando abaixo. 💬
```

#### Fechar pull requests inválidos

> Quando o PR é inválido.

Em inglês:
```markdown
Hey @username

You haven't actually added any content so I will be  invalid pull requests this PR and marking it as `invalid`. 😓️

Feel free to open another PR though! 👍
```

Em português:
```markdown
Olá @username

Você não adicionou nenhum conteúdo portanto vou ter de invalidar este <i>pull request</i> e marcá-lo como `invalid`. 😓️

Fique à vontade para abrir outro PR! 👍
```
