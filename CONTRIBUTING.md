<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"></a>
    <span> Guia de Contribuição</span>
</h1>

[![Star](https://img.shields.io/github/stars/elidianaandrade/dio-lab-open-source?style=social)](https://github.com/elidianaandrade/dio-lab-open-source/stargazers)
[![Forks](https://img.shields.io/github/forks/elidianaandrade/dio-lab-open-source?style=social)](https://github.com/elidianaandrade/dio-lab-open-source/forks)
[![GitHub Issues](https://img.shields.io/github/issues/elidianaandrade/dio-lab-open-source?style=social)](https://github.com/elidianaandrade/dio-lab-open-source/issues/)

 Este é um projeto feito para a comunidade, então sinta-se livre para contribuir. Algumas formas de contribuição além do seu exemplo de Profile README, é inserir outros utilitários na pasta [`utils`](https://github.com/elidianaandrade/dio-lab-open-source/tree/main/utils), ou melhorar a página de pesquisa dos READMEs fazendo modificações nos arquivos da pasta [`docs`](https://github.com/elidianaandrade/dio-lab-open-source/tree/main/docs). <br>
 Além disso, você também pode contribuir:
 
⚠️ Resolvendo, respondendo ou indicando **issues**

⭐ Adicionando aos favoritos (**star**) 

##  Contribuindo no diretório "Community" 
 A contribuição no diretório "Community" faz parte do Desafio do lab **Contribuindo em um Projeto Open Source no GitHub** da [Digital Innovation One](https://www.dio.me/). Você pode colaborar criando um Profile README contendo informações sobre você que deseje compartilhar com a comunidade. Para isso, você pode inserir: badges indicando suas habilidades; cards com suas estatísticas no GitHub e projetos que criou, colaborou ou que deseje que outras pessoas colaborem. Além disso, você pode inserir também links para seus desafios de projeto e artigos na plataforma da [Digital Innovation One](https://www.dio.me/). <br>
 Inspire-se consultando os exemplos na pasta [`community`](https://github.com/elidianaandrade/dio-lab-open-source/tree/main/community), confira alguns utilitários na pasta [`utils`](https://github.com/elidianaandrade/dio-lab-open-source/tree/main/utils) e use sua criatividade para criar o seu 😊💙.

### Instruções
1. Faça um **Fork** deste repositório;
2. Clone localmente: `git clone https://github.com/SEUUSERNAME/dio-lab-open-source.git`;
3. Adicione o remote upstream para manter seu repositório local atualizado: `git remote add upstream https://github.com/elidianaandrade/dio-lab-open-source.git`;
    > Utilize o comando `git pull upstream main` para baixar e mesclar as alterações no seu repositório local com base na branch `main` deste repositório original de onde você fez o fork, ou `git fetch upstream main` para baixar sem mesclar. Veja mais em: [Primeiros Passos com Git e GitHub](https://github.com/elidianaandrade/dio-curso-git-github/blob/main/materiais-de-apoio/03-primeiros-passos-com-git-e-github.md).
4. Crie uma nova **branch** e nomeie como `feat/community/seunomedeusuario`;
    > Exemplo: `feat/community/elidianaandrade`
5. Dentro da pasta [`community`](https://github.com/elidianaandrade/dio-lab-open-source/tree/main/community), crie um arquivo em Markdown (extensão `.md`) e nomeie com o mesmo nome do seu usuário no GitHub;
    > Exemplo: `elidianaandrade.md` <br>
6. Desenvolva o seu perfil. Para isso, você pode ver exemplos na pasta [`community`](https://github.com/elidianaandrade/dio-lab-open-source/tree/main/community) e adicionar alguns dos utilitários presentes na pasta [`utils`](https://github.com/elidianaandrade/dio-lab-open-source/tree/main/utils);
    > **Observação:** Use os outros exemplos como inspiração e não cópia.
7. Adicione suas alterações à "staging area" com o comando `git add community/seunomedeusuario.md`;
8. Crie um commit e adicione a mensagem indicando a adição do seu perfil `git commit -m"feat: add seunomedeusuario profile"`;
9. Envie as alterações para o seu repositório remoto `git push origin feat/community/seunomedeusuario`; 
10. Crie um **Pull Request**.

## Convenção de Commits

| Tipo de Commit | Descrição                                                                                                 |
| -------------- | --------------------------------------------------------------------------------------------------------- |
| `feat`         | Adiciona uma nova funcionalidade ao projeto.                                                              |
| `fix`          | Corrige um bug ou problema no projeto.                                                                    |
| `docs`         | Altera a documentação do projeto. Ex.: README, comentários no código.                                     |
| `style`        | Realiza mudanças na aparência, sem alterar a funcionalidade.                                              |
| `refactor`     | Realiza mudanças no código que não alteram a funcionalidade.                                              |
| `test`         | Adiciona ou modifica testes no projeto.                                                                   |

##### Exemplo commit

`feat: adicionado novo arquivo`


## Referências
- [ANGULAR. Contributing to Angular](https://github.com/angular/angular/blob/22b96b9/CONTRIBUTING.md)
- [CONVENTIONAL COMMITS. Summary](https://www.conventionalcommits.org/en/v1.0.0/)
- [GITHUB. Configurar diretrizes para os contribuidores do repositório](https://docs.github.com/pt/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors)


Problema ao acessar a pasta "community"

Bug
Mensagem de erro:
Desculpe, tivemos que truncar este diretório para 1.000 arquivos. 15.975 entradas foram omitidas da lista. As informações do último commit podem ser omitidas.
Falha ao carregar as informações de commit mais recentes.

Parece que o repositório é muito grande e está excedendo os limites de visualização ou capacidade do sistema.

Reproduzir
Etapas para reproduzir o comportamento:

Vá para 'https://github.com/digitalinnovationone/dio-lab-open-source'
Clique em 'community'
Aguarde
Ver erro
Sugestões de melhorias:
Uma melhoria que poderia ser implementada para lidar com o problema de visualização de grandes repositórios seria a implementação de paginação ou filtros de busca mais eficientes. Aqui está uma sugestão de melhoria:

Implementação de Paginação:
Em vez de exibir todos os arquivos de uma vez, o sistema poderia exibir apenas uma parte deles por página, permitindo que o usuário navegue pelas páginas para visualizar todo o conteúdo. Isso reduziria a carga no sistema e tornaria mais fácil para os usuários acessarem o conteúdo completo do repositório, mesmo em casos de grande volume de dados.

Filtros de Busca Avançados:
Outra melhoria seria a implementação de filtros de busca avançados, permitindo que os usuários refinassem sua pesquisa para encontrar os arquivos específicos que estão procurando. Isso poderia incluir filtros por data de modificação, tipo de arquivo, autor do commit, entre outros critérios relevantes.

Essas melhorias não só ajudariam a lidar com o problema atual de visualização de grandes repositórios, mas também melhorariam a experiência do usuário ao tornar a navegação e busca mais eficientes e intuitivas.

o GitHub oferece funcionalidades para lidar com grandes repositórios e facilitar a navegação e busca de arquivos.
Veja algumas dessas funcionalidades:

Paginação:
O GitHub implementa a paginção em muitas de suas visualizações, como listas de arquivos em uma pasta ou resultados de pesquisa. Isso permite que os usuários naveguem pelos resultados de maneira mais controlada, visualizando um número limitado de itens por página.

Filtros de Busca:
A barra de pesquisa do GitHub permite que os usuários filtrem os resultados por nome do arquivo, conteúdo do arquivo, autor do commit, data e outros critérios. Além disso, é possível usar operadores de busca avançados para refinar ainda mais os resultados da pesquisa.

Explorador de Arquivos:
O GitHub possui um explorador de arquivos que permite aos usuários visualizarem a estrutura de pastas do repositório e navegar entre os arquivos de forma hierárquica. Isso facilita a localização de arquivos específicos dentro do repositório.
Visualização de Diferenças: Ao visualizar um arquivo, você pode ver as diferenças entre versões específicas do arquivo e até mesmo comparar entre branches diferentes. Isso é útil para entender as mudanças feitas ao longo do tempo e colaborar em projetos com outras pessoas.

Essas funcionalidades ajudam a lidar com repositórios de diferentes tamanhos e facilitam a navegação e colaboração em projetos hospedados no GitHub.
