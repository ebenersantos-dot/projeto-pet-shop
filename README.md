# Petpaw Pet Shop

Site institucional de pet shop com foco em apresentação de serviços e captação de agendamentos online.

## Sobre o projeto

Este projeto foi criado para consolidar conhecimentos em **HTML** e **CSS**, com evolução gradual para **JavaScript**.
A proposta é oferecer uma experiência simples, clara e confiável para tutores que desejam conhecer os serviços da clínica e solicitar atendimento para seus pets.

## Objetivo

- Praticar e evoluir habilidades de front-end com HTML e CSS.
- Construir uma página realista para um pet shop com identidade visual própria.
- Simular um fluxo de agendamento completo, incluindo página de confirmação.

## Funcionalidades atuais

- Header fixo com navegação rápida por seções.
- Seção de destaque com mensagem principal da marca.
- Exibição dos principais serviços oferecidos.
- Formulário de agendamento com campos obrigatórios.
- Redirecionamento para página de confirmação após envio do formulário.
- Personalização da confirmação com nome do tutor e do pet (via parâmetros da URL).
- Botão e links de retorno para a página inicial.
- Rodapé com links de navegação em todas as páginas.
- Layout responsivo para desktop, tablet e mobile.
- Barra de rolagem visual oculta (mantendo a rolagem funcional).

## Como o site funciona

1. O usuário acessa a página principal (`index.html`) e navega pelas seções.
2. No bloco de agendamento, preenche os dados do tutor, do pet, serviço, data e horário.
3. Ao clicar em **Confirmar agendamento**, o formulário redireciona para `confirmation-pg.html`.
4. A página de confirmação exibe a mensagem de sucesso com os nomes enviados no formulário.
5. O usuário pode retornar para a home pelo botão de retorno, pela logo ou pelo rodapé.

## Tecnologias utilizadas

- **HTML5**
- **CSS3**
- **JavaScript (vanilla)** para personalização da mensagem de confirmação
- **Google Fonts** para tipografia

## Estrutura do projeto

```bash
projeto-pet-shop/
├── index.html
├── confirmation-pg.html
├── styles.css
├── img/
└── README.md
```

## Screenshots

### Página inicial

![Prévia da página inicial do Petpaw](./img/dog-colo.jpg)

### Confirmação de agendamento

![Prévia da página de confirmação do Petpaw](./img/digo-colo.png)

> Dica: para portfólio, você pode substituir essas imagens por capturas reais de tela e manter os arquivos em `img/screenshots/`.

## Como executar localmente

Como é um projeto estático, não precisa de build nem instalação de dependências.

1. Clone o repositório:

```bash
git clone <url-do-repositorio>
```

2. Acesse a pasta do projeto:

```bash
cd projeto-pet-shop
```

3. Abra o arquivo `index.html` no navegador.

Dica: se preferir, rode com extensão como **Live Server** no VS Code para facilitar o desenvolvimento.

## Próximos passos

- Integrar o formulário com back-end para persistir agendamentos.
- Adicionar validações mais avançadas de formulário (máscaras e regras de data/horário).
- Enviar confirmação automática por e-mail ou WhatsApp.
- Melhorar SEO e acessibilidade com ajustes adicionais de semântica e metadados.

## Autor

Desenvolvido por **Ebener Santos** para prática e evolução em front-end.

## Status

Projeto em desenvolvimento contínuo.
