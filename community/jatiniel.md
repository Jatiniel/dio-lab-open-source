 Guia de Contribuição
Star Forks GitHub Issues

Este é um projeto feito para a comunidade, então sinta-se livre para contribuir. Algumas formas de contribuição além do seu exemplo de Profile README, é inserir outros utilitários na pasta utils, ou melhorar a página de pesquisa dos READMEs fazendo modificações nos arquivos da pasta docs.
Além disso, você também pode contribuir:

⚠️ Resolvendo, respondendo ou indicando issues

⭐ Adicionando aos favoritos (star)

Contribuindo no diretório "Community"
A contribuição no diretório "Community" é uma das formas de completar o Desafio do lab "Contribuindo em um Projeto Open Source no GitHub" da Digital Innovation One. Você pode colaborar criando um Profile README contendo informações sobre você que deseje compartilhar com a comunidade.
Para isso, você pode inserir: badges indicando suas habilidades; cards com suas estatísticas no GitHub e projetos que criou, colaborou ou que deseje que outras pessoas colaborem. Além disso, você pode inserir também links para seus desafios de projeto e artigos na plataforma da Digital Innovation One.
Inspire-se consultando os exemplos na pasta community, confira alguns utilitários na pasta utils e use sua criatividade para criar o seu 😊💙.

1) Faça um Fork deste Repositório
Acesse a página principal do repositório e clique no botão "Fork" no canto superior direito da página.

Note

Um "fork" no GitHub é uma cópia de um repositório que pode ser criada por qualquer usuário.
Para mais detalhes, reveja a aula ou acesse a documentação do GitHub: Criar fork de um repositório.

2) Clone localmente
Abra o seu Git Bash e digite o comando git clone seguido da URL do seu fork para clonar o seu repositório localmente. Por exemplo:

git clone https://github.com/SEU_USERNAME/dio-lab-open-source.git
Pressione enter, e uma cópia do seu fork no GitHub será criada localmente.

3) Crie uma nova branch
Utilize o comando git checkout -b para criar e alternar para a nova branch e nomeie-a como feat/community/SEU_USERNAME

Exemplo: git checkout -b feat/community/falvojr

4) Crie o seu Profile README
Dentro da pasta community, crie um arquivo em Markdown (extensão .md) e nomeie com o mesmo nome do seu usuário no GitHub:

Exemplo: community/falvojr.md

4.1) Desenvolva o seu Profile README
Para isso, você pode se inspirar nos exemplos no diretório community e adicionar alguns dos utilitários presentes na pasta utils

5) Adicione suas alterações à "staging area"
Utilize o comando git add community/SEU_USERNAME.md para adicionar sua alteração (nesse caso o arquivo markdown criado) à "staging area" no Git.

6) Crie um Commit
Crie um commit e adicione a mensagem indicando a adição do seu perfil:

git commit -m"feat: add SEU_USERNAME profile"
Important

Verifique a Convenção de Commits para escrever a mensagem do seu commit de forma clara e padronizada.

7) Envie as Alterações para o seu Repositório Remoto
Envie as alterações realizadas no seu repositório local para a branch feat/community/SEU_USERNAME no seu repositório remoto com o comando:

git push origin feat/community/SEU_USERNAME
Warning

Caso você tenha criado seu arquivo diretamente no repositório remoto no GitHub, esse processo não será necessário.

8) Crie um Pull Request.
Atente-se para a seguir as orientações para a contribuição, principalmente:

Seu PR deve modificar apenas o arquivo community/SEU_USERNAME.md (dê uma olhadinha na aba "Files changed");
O nome desse arquivo deve ser exatamente igual ao nome de usuário no GitHub (nossa validação é case-sensitive).
Note

Caso não saiba como criar uma solicitação de pull, reveja o lab ou acesse a documentação do GitHub: Como criar uma solicitação de pull

Após criar o seu Pull Request, nossa automação irá validar a sua submissão. Caso esteja tudo certo, será retornada uma mensagem indicado que seu PR foi aprovado. Do contrário, leia atentamente as orientações e verifique os arquivos modificados para saber se atende as instruções para contribuição.

Convenção de Commits
Tipo de Commit	Descrição	Exemplo
feat	Adiciona uma nova funcionalidade ao projeto.	feat: add USENAME.md profile
fix	Corrige um bug ou problema no projeto.	fix: fixed issue fix#IssueNumber
docs	Altera a documentação do projeto.	docs: update README.md
style	Realiza mudanças na aparência, sem alterar a funcionalidade.	style: add EFFECTNAME to COMPONENT
refactor	Realiza mudanças no código que não alteram a funcionalidade.	refactor: refactor at CLASSNAME
test	Adiciona ou modifica testes no projeto.	test: add unit test for UserService
Referências
ANGULAR. Contributing to Angular
CONVENTIONAL COMMITS. Summary
GITHUB. Configurar diretrizes para os contribuidores do repositório
