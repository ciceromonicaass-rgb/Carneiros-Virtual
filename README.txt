# CARNEIROS VIRTUAL — Centro de Formação em BNCC Computação

Projeto web offline do Carneiros Virtual, Professor Antônio.

## Como abrir
1. Extraia esta pasta.
2. Abra `index.html` diretamente no navegador.
3. Não é necessário instalar servidor para usar a versão offline.

## Estrutura
- `index.html` — entrada principal.
- `css/style.css` — estilos.
- `js/app.js` — funcionalidades.
- `dados/` — espaço reservado para dados pedagógicos estruturados.
- `documentos/` — espaço para PDFs, normativas e materiais.
- `imagens/` — logotipos, fotos e ilustrações.
- `backups/` — cópias exportadas do sistema.

## Dados
A versão offline salva planos, participantes, presença, diagnóstico e marcações no armazenamento local do navegador. Use a função de exportação para criar backups.

## Próxima evolução
A arquitetura está preparada para separar posteriormente:
- catálogo de cursos;
- módulos e aulas;
- banco completo de habilidades;
- usuários e perfis;
- escolas, turmas e professores;
- avaliações;
- presença;
- certificados;
- relatórios;
- banco de dados online e API.

## Identidade
CARNEIROS VIRTUAL
Professor Antônio
carneirosvirtual.com


## Módulos V7
- Gestão pedagógica offline: escolas, professores e turmas.
- Relatórios de formação.
- Avaliação de conclusão de cursos.
- Certificação vinculada à conclusão de módulos e presença.
- Certificado A4 horizontal.


## V16 — Nova capa visual
A tela inicial foi redesenhada com base na referência visual enviada pelo usuário:
- layout com menu lateral esquerdo;
- identidade creme/dourado;
- marca Carneiros Virtual;
- chamada principal central;
- botão de exploração;
- indicadores;
- cards de categorias;
- busca no menu;
- rolagem independente do menu.


## V17 — Aprimoramento da experiência
- Atalhos rápidos na capa para Plano, Planejamento, Formação e Quiz.
- Gerador de plano ajustado para 4 bimestres.
- Botão flutuante para retornar à capa.
- Busca lateral com filtragem visual.
- Proteção de navegação para evitar erro quando uma seção não existir.
- Acabamento visual mantendo a referência creme/dourado.


## V18 — Criador de Sequência Didática
Nova área para criar sequências de 3, 4 ou 5 aulas por etapa, bimestre e disciplina. Inclui objetivo, referência curricular, desenvolvimento, evidências, recursos, salvamento local e impressão.


## V19 — Gerador de Avaliações
- Avaliações por etapa, bimestre e disciplina.
- Banco inicial de questões para 10 áreas.
- Alternativas embaralhadas a cada geração.
- Gabarito separado.
- Salvamento local.
- Impressão da avaliação e do gabarito.
- Cabeçalho para nome, data, turma e nota.


## V20 — Banco de Questões
- Seleção manual de questões.
- Geração de versões A, B e C.
- Ordem das questões e alternativas alterada entre versões.
- Gabaritos separados.
- Impressão individual ou conjunta.


## V21 — Banco de Questões ampliado
- 50 questões por disciplina em cada etapa/ano.
- 10 disciplinas × 10 etapas = 5.000 questões.
- Banco externo local em JSON, sem internet.
- O Banco de Questões agora filtra por ano + disciplina.
- Seleção manual e versões A/B/C continuam disponíveis.


## V22 — Banco pedagógico enriquecido
Cada uma das 5.000 questões agora possui:
- identificador;
- número;
- enunciado;
- alternativas;
- gabarito;
- dificuldade: Fácil, Médio ou Difícil;
- tema;
- habilidade sugerida;
- objetivo pedagógico;
- justificativa.
Nova área: Análise Pedagógica, com filtros e relatório para impressão.


V24 - SISTEMA AVANÇADO DE AVALIAÇÕES
- Criação automática de avaliações A/B/C
- Filtros por ano, bimestre, disciplina e dificuldade
- Escola, turma e professor
- Salvamento local e impressão
- Gabaritos separados

V25 - GESTÃO ESCOLAR INTEGRADA
Cadastro de escolas, professores, turmas e alunos; lançamento de notas e frequência; resultados por aluno; exportação local JSON.

V26 - CORREÇÃO DO BANCO DO SISTEMA AVANÇADO DE AVALIAÇÕES: leitura correta do banco 20.000 (Ano > Disciplina > Bimestre), contador de questões e geração A/B/C.

V27 - AVALIAÇÃO INTEGRADA: banco bimestral + turma + alunos + lançamento de notas/frequência + relatório.
