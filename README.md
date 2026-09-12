# Portal Terra — correção com Flexbox

Template didático inspirado no wireframe fornecido para a aula de Redes de Computadores.

> A página utiliza apenas HTML e CSS, sem frameworks.

## Tecnologias e ferramentas

- HTML5;
- CSS3;
- EditorConfig;
- Prettier;
- Visual Studio Code.

## Estrutura do projeto

```text
rci-portal-terra/
├── .github/
│   └── pull_request_template.md
├── .vscode/
│   ├── extensions.json
│   └── settings.json
├── css/
│   ├── reset.css
│   └── styles.css
├── docs/
│   └── guia-padronizacao-codigo.md
├── img/
│   └── .gitkeep
├── .editorconfig
├── .gitignore
├── .prettierignore
├── .prettierrc.json
├── index.html
├── LICENSE
└── README.md
```

## Executar o projeto

Abra o arquivo `index.html` utilizando a extensão Live Server do Visual Studio Code.

## Documentação

Os materiais didáticos de HTML e CSS estão disponíveis no repositório [Fundamentos de Desenvolvimento Web I](https://github.com/ifc-dev-web2/rc-web1-fundamentos).

---

## Objetivos da aula

- reconhecer os elementos pai e filho de um container flexível;
- utilizar `display: flex` para organizar elementos em linha;
- aplicar `justify-content`, `align-items` e `gap`;
- controlar o espaço dos elementos com `flex` e `flex-basis`;
- permitir que os elementos quebrem de linha com `flex-wrap`;
- alterar a direção dos elementos em telas menores com `flex-direction`;
- criar um layout responsivo usando media queries.

## Onde o Flexbox foi aplicado

| Região    | Classe principal    | Conceito trabalhado                  |
| --------- | ------------------- | ------------------------------------ |
| Cabeçalho | `.topo__conteudo`   | `justify-content: space-between`     |
| Menu      | `.navegacao__lista` | alinhamento, `gap` e `flex-wrap`     |
| Placar    | `.placar__jogo`     | alinhamento central em linha         |
| Destaques | `.destaques`        | divisão proporcional com `flex`      |
| Chamadas  | `.chamadas`         | quatro itens flexíveis em linha      |
| Editorias | `.editorias`        | quatro colunas de mesma largura      |
| Celular   | media queries       | quebra de linha e mudança de direção |

## Roteiro

1. Identifique os grandes blocos visuais da página.
2. Lembre-se que o Flexbox deve ser aplicado ao elemento pai.
3. Comece pelo cabeçalho e entenda o eixo principal e o eixo transversal.
4. Monte os dois destaques e compare `flex: 2` com `flex: 1`.
5. Crie as quatro chamadas usando `flex: 1` e `gap`.
6. Repita o padrão na seção de editorias.
7. Reduza a largura do navegador e observe o efeito das media queries.
8. Troque os blocos coloridos por imagens locais.

```bash
git clone https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git
```

Entre no diretório criado:

```bash
cd NOME-DO-REPOSITORIO
```

Abra o projeto completo no Visual Studio Code:

```bash
code .
```

> Substitua `SEU-USUARIO` pelo seu usuário do GitHub e
> `NOME-DO-REPOSITORIO` pelo nome definido para a atividade.

## Contexto acadêmico

| Informação  | Descrição                                         |
| ----------- | ------------------------------------------------- |
| Instituição | Instituto Federal Catarinense — Campus Araquari   |
| Curso       | Técnico em Redes de Computadores                  |
| Disciplina  | Desenvolvimento Web I                             |
| Organização | [IFC Dev Web II](https://github.com/ifc-dev-web2) |

## Autoria

Projeto desenvolvido por **[Prof. Cristofer Sousa](https://github.com/cristofersousa)** durante as atividades de Desenvolvimento Web I.

## Licença

Este projeto está disponível sob os termos definidos no arquivo
[LICENSE](./LICENSE).
