# Nota sobre projetos Open source: 

Nós não nos importamos se você quebra as coisas. Este é um playground e nós incentivamos o fracasso com freqüência. Use isto como um campo de prática e aproveite para contribuir com projetos que você cria com seus colegas estudantes. Muitos estudantes adquiriram experiência do mundo real "trabalhando em equipe" ao trabalhar nesses projetos.


## Um guia para começar

1. Leiam o maravilhoso [_gitStarted Guia](https://github.com/zero-to-mastery/start-here-guidelines/blob/855a00243db60c71905f6e3afd95ebf2cf7459a0/gitstartedguideoptimized.pdf) de um colega da ZTM  [@wanraitelli](https://github.com/wanraitelli).

   Confira [os videos do Andrei no github](https://www.udemy.com/the-complete-web-developer-in-2018/learn/v4/t/lecture/8725782/) ou este tutorial gratuito: http://makeapullrequest.com/.

2. Na [ pagina do GitHub  deste repositorio ](https://github.com/SENAI-FATEC-Developers/comecem-aqui-regras), clique no botão "Fork".

   ![fork image](https://help.github.com/assets/images/help/repository/fork_button.jpg)

3.  Clone  _seu forked repository_  para o seu computador:

   ![code ui](https://docs.github.com/assets/images/help/repository/code-button.png)

     Por exemplo, execute esse comando no seu terminal:

    ```bash
    git clone https://github.com/<your-github-username>/start-here-guidelines.git
    ```

    **Troque \<your-github-username\>!**

    Leia mais sobre [forking](https://help.github.com/en/github/getting-started-with-github/fork-a-repo) e [cloning a repo](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).


4.  Antes de você fazer qualquer alteração , [ mantenha seu fork sincronizado](https://www.freecodecamp.org/news/how-to-sync-your-fork-with-the-original-git-repository/) para evitar conflitos "merge" our "merge conflict":

    ```bash
    git remote add upstream https://github.com/zero-to-mastery/start-here-guidelines.git
    git pull upstream master
    ```

    Se você estiver com um **merge conflict**, você deve resolve-lo .  Pesquise como resolve-lo ou tente este guia ; [opensource.com](https://opensource.com/article/20/4/git-merge-conflict).

5. No seu computador , abra seu editor de texto , e adicione seu nome de usuario  ao arquivo `CONTRIBUTORS.md` .

6.  Adicione as alterações com os comandos `git add`, `git commit` ([escreva um bom comentario de "commit"](https://chris.beams.io/posts/git-commit/), se possivel (obs: o link esta com conteudo em ingles.)):

    ```bash
    git add CONTRIBUTORS.md
    git commit -m "Add <your-github-username>"
    ```

    **Altere \<your-github-username\>!**

7. Envie as alterações _para seu repositorio_:

    ```bash
    git push origin master
    ```

8. Para ir a pagina do GitHub  _your fork_,  e fazer um pull request:

    ![pull request image](https://help.github.com/assets/images/help/pull_requests/choose-base-and-compare-branches.png)

     Leia mais sobre  "pull requests " no site [GitHub help pages](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

9. Espere ate que um dos moderadores anexe "merge" seu "pull request" . Vamos informa-lo se houver algum conflito.

10. Junte-se a um projeto e comece a contribuir ou crie seu proprio  grupo ou aplicativo. Não seja timido e aproveite desenvolver em equipe.  Caso queira outras opções de projetos Open source , não deixe de verificar a [Zero to Mastery](https://github.com/zero-to-mastery).  [Veja esse guia ](https://github.com/zero-to-mastery/start-here-guidelines/blob/master/Get_Started.md) para mais informações ao escolher um projeto (PS: pertence ao ZTM e está em ingles).

11. Para ver o icone SENAI FATEC Developer ou  Zero to Mastery  no seu perfil do GitHub, [siga esses passos](https://help.github.com/articles/publicizing-or-hiding-organization-membership/) (você deve completar o passo 1 e 2 para funcionar).

## Anatomia de um projeto de código aberto:

Um típico projeto de código aberto tem os seguintes tipos de pessoas:

**Autor***: A(s) pessoa(s) ou organização(ões) que criou(m) o projeto.

**Proprietário***: A(s) pessoa(s) que tem(m) propriedade administrativa sobre a organização ou repositório (nem sempre a mesma(s) que o autor original).

**Mantenedores***: Contribuintes responsáveis por conduzir a visão e gerenciar os aspectos organizacionais do projeto (podem também ser autores ou proprietários do projeto).

**Contribuidores***: Todos aqueles que contribuíram com algo de volta para o projeto.

**Membros da comunidade***: Pessoas que utilizam o projeto. Elas podem ser ativas em conversas ou expressar sua opinião sobre a direção do projeto.

