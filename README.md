# AYU Digital

Front-end institucional e de agendamento para a Academia AYU.

## Descrição

O AYU Digital é o projeto de PVI (Práticas de Vivências Interdisciplinares) desenvolvido para a Academia AYU, uma academia de fitness premium localizada em Foz do Iguaçu — PR. O projeto consiste na criação da camada de front-end de um sistema web institucional, contemplando a apresentação da academia, dos planos, da equipe de professores e a simulação de agendamento de aula experimental. Nesta etapa, o trabalho é exclusivamente front-end (HTML, CSS e JavaScript), sem banco de dados ou back-end.

## Problema a ser resolvido

A Academia AYU não possui uma presença digital condizente com seu posicionamento premium no mercado. Atualmente, a divulgação de planos, modalidades e horários, o agendamento de aulas e o relacionamento com alunos e interessados são conduzidos de forma manual e fragmentada — por telefone, WhatsApp e indicação boca a boca — sem uma vitrine digital unificada. Isso gera perda de oportunidades de captação de novos alunos, inconsistência na comunicação da identidade de marca e dificuldade dos interessados em consultar informações e agendar aulas de forma autônoma.

## Requisitos operacionais

- Navegador web moderno (Chrome, Firefox, Edge ou Safari atualizados)
- Não requer instalação de dependências, servidor ou banco de dados para execução — basta abrir o arquivo `index.html`
- Conexão com a internet apenas para carregamento de fontes externas (caso utilizadas)
- Para desenvolvimento: um editor de código (ex.: VS Code) e, opcionalmente, uma extensão de live server para pré-visualização

## Ferramentas utilizadas

- **HTML5** — estruturação semântica das páginas
- **CSS3** — estilização, responsividade e efeitos visuais
- **JavaScript** — interatividade, validações e integração com WhatsApp
- **Git/GitHub** — versionamento e hospedagem do repositório
- **Visual Studio Code** — editor de código utilizado no desenvolvimento

## Funcionalidades

Visão geral das principais funcionalidades do site:

- Apresentação institucional da Academia AYU (história e proposta do espaço)
- Galeria de fotos da estrutura
- Exibição dos planos (mensal, semestral e anual)
- Apresentação da equipe de professores
- Simulação de agendamento de aula experimental, com envio automático para o WhatsApp da academia
- Layout responsivo (desktop, tablet e celular)

A lista completa e detalhada de todas as funcionalidades previstas está no arquivo [Functions.md](docs/Functions.md).

## Estrutura de arquivos e pastas

```
.
|-- ARQUIVOS.md
|-- FUNCIONALIDADES.md
|-- README.md
|-- assets
|   |-- fonts
|   `-- images
|       |-- estrutura
|       |-- logo-ayu.png
|       |-- planos
|       `-- professores
|-- css
|   |-- responsive.css
|   `-- style.css
|-- docs
|   |-- resumo-expandido.pdf
|   |-- termo-de-abertura.pdf
|   `-- termo-de-mentoria.pdf
|-- index.html
`-- js
    |-- agendamento.js
    |-- carrossel.js
    `-- main.js

10 directories, 13 files
```

A descrição detalhada do papel de cada arquivo e pasta está no arquivo [Files.md](docs/Files.md).

## Autores

- Gabriel Barbosa Feijó
- Fernando Vinícius Faccin Bonete
- Gustavo Aparecido da Rocha

**Docente orientador:** Bruno Luiz Schuster Rech
**Mentor:** Jean Lucas Gomes Pereira

Curso de Análise e Desenvolvimento de Sistemas — Faculdade Uniguaçu, Foz do Iguaçu.

---

Repositório: [github.com/gabrielbarbosafeijo-cpu/Documentation](https://github.com/gabrielbarbosafeijo-cpu/Documentation)
