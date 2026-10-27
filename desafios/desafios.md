# Vídeos aulas de apoio extra
1. Assista e siga o passo a passo: https://youtu.be/YF0SvIzxd-M?is=blpouvhEZA_OhISQ
2. Assista e siga o passo a passo: https://youtu.be/TrDBJ9HO3yE?si=nL40ktg9r5cEfTMU
   
# Prática Orientada: Transformando sua Página

- Agora é a hora de colocar a mão na massa e aplicar todo o conhecimento adquirido! Usaremos a página HTML que vocês criaram na semana anterior como base para essa prática.

# Exercício 1: Estilização Básica
Abra seu arquivo HTML da semana anterior e crie um arquivo styles.css para o CSS externo.
Linke o arquivo CSS ao seu HTML no <head>.

# Cores:
- Defina uma background-color suave para o <body>.
- Escolha cores diferentes para cabeçalhos (<h1>, <h2>) e parágrafos (<p>).

# Fontes:
- Altere a font-family para uma fonte mais legível em todo o corpo do texto.
- Ajuste o font-size dos cabeçalhos para que se destaquem e dos parágrafos para uma leitura confortável.

# Espaçamentos (Box Model):
- Adicione padding interno a um <div> ou <section> principal.
- Defina margin entre parágrafos ou seções para evitar que o texto fique "colado".
- Experimente adicionar uma border a um elemento para visualizá-lo melhor.

# Exercício 2: Layout com Flexbox e Responsividade Inicial

- Identifique uma seção da sua página (ex: uma lista de itens, um menu de navegação, ou cards de produtos) que possa se beneficiar de um layout flexível.
- Crie um elemento pai e transforme-o em um contêiner flex com display: flex;.
- Use justify-content e align-items para organizar os itens filhos.

# Crie uma Media Query para telas menores (ex: max-width: 768px).

- Dentro dessa Media Query, altere a flex-direction do contêiner flex para column e ajuste outros estilos (ex: font-size) para otimizar a visualização em dispositivos móveis.

# Lab. Prática | 🎯 Objetivo do Laboratório
Criar a interface de um Dashboard de Serviços para Cidades Inteligentes (Smart Cities) ou um Portal do Cidadão. A aplicação deve ser intuitiva, responsiva e aplicar tendências modernas de UI/UX, utilizando HTML5, CSS3, JavaScript e um framework à escolha da turma (React, Vue, ou frameworks CSS como Bootstrap/Tailwind).

🛠️ O Desafio Técnico: "Cidadão Conectado"
Cenário: A prefeitura local precisa de um novo portal web onde os cidadãos possam relatar problemas na infraestrutura da cidade (ex: buracos na via, iluminação pública apagada). O protótipo atual foi rejeitado por ter péssima usabilidade. A missão dos alunos é recriar essa interface do zero em 2 horas de laboratório.

Requisitos de Entregáveis (Checklist do Aluno)
Estrutura e Framework:

Utilizar um framework CSS (Tailwind, Bootstrap) ou uma biblioteca de componentes (Material UI no React).

A interface deve ser estritamente Mobile First.

Usabilidade Aplicada:

Prevenção de Erros: O formulário de "Novo Relato" deve ter validação visual em tempo real (bordas vermelhas para erro, verdes para sucesso).

Feedback de Ação: Botões devem ter microinterações (estado de loading ao clicar em enviar).

Acessibilidade (a11y): Uso correto de tags semânticas, atributos aria-label e contraste adequado de cores.

Tendência Web (Obrigatório):

Implementar um Toggle (chaveador) para alternar a interface entre Light Mode e Dark Mode usando JavaScript e variáveis CSS.

⏱️ Dinâmica de Execução no Laboratório (Metodologia Ativa)
Para garantir que os alunos não apenas codifiquem, mas planejem e colaborem, divida o tempo do laboratório utilizando sprints e gestão visual:

Fase 1: Planning com Kanban (15 min)

Em duplas ou trios, os alunos devem usar o quadro físico do laboratório (ou Trello) para criar um mini-Kanban (A Fazer, Fazendo, Feito).

Eles devem quebrar o desafio em pequenas tarefas: "Criar HTML base", "Configurar Framework", "Estilizar Header", "Fazer Script do Dark Mode".

Fase 2: Hands-on Code com Pomodoro (1h 20 min)

Ciclo 1 (25 min): Setup do projeto e estruturação do layout principal (Mobile).

Ciclo 2 (25 min): Estilização, formulários e responsividade (Desktop).

Ciclo 3 (25 min): Lógica JavaScript (Validações e Dark Mode).

Fase 3: Code Review e Showcase (25 min)

As duplas trocam de computadores. Uma dupla avalia a usabilidade do projeto da outra simulando ser um cidadão tentando relatar um problema.

O professor valida as entregas focando na arquitetura do código e na experiência do usuário.

💻 Snippet de Apoio: Lógica Base para o Dark Mode (JS + Variáveis CSS)
Caso algum grupo trave na implementação da tendência de Dark Mode, você pode fornecer este esqueleto no quadro:
