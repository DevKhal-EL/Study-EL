# ROADMAP — Study-EL
Este roadmap registra a direção de desenvolvimento do Study-EL. Ele não é um contrato de funcionalidades nem uma sequência imutável: as etapas podem ser ajustadas conforme o projeto evoluir, novas necessidades aparecerem e as decisões técnicas forem amadurecendo.

O foco imediato é concluir o planejamento do sistema de acesso e construir sua primeira versão. As etapas posteriores representam a direção pretendida, não funcionalidades já implementadas ou decisões definitivas.
---
# Fase 1 — Planejamento e prototipação

Objetivo: definir a proposta do projeto e preparar o primeiro recorte de desenvolvimento.
- [x] Definir o propósito do Study-EL.
- [x] Identificar o problema que motivou o projeto.
- [x] Definir o sistema de acesso como primeiro ponto de desenvolvimento.
- [ ] Aprender o fluxo necessário no Figma e criar o protótipo da tela de acesso.
- [ ] Definir a identidade visual inicial.
- [ ] Estudar e definir a arquitetura do sistema de acesso.
- [ ] Fazer a modelagem conceitual, lógica e física dos dados necessários.

## Fase 2 — Interface e fundamentos do frontend

Objetivo: desenvolver a primeira interface utilizando HTML e CSS, fortalecendo os fundamentos antes de adotar um framework.
- [ ] Implementar a interface inicial com HTML e CSS.
- [ ] Trabalhar a estrutura semântica e a organização dos estilos.
- [ ] Implementar a responsividade.
- [ ] Validar a interface em diferentes tamanhos de tela.
- [ ] Organizar a estrutura inicial do frontend.
A intenção é começar com as tecnologias fundamentais e compreender o que está sendo construído. A adoção de um framework poderá ser avaliada posteriormente, quando fizer sentido para a evolução da aplicação.

## Fase 3 — Backend, dados e autenticação

Objetivo: implementar o funcionamento do sistema de acesso e integrá-lo à interface.
- [ ] Consolidar a escolha da tecnologia de backend. Java com Spring é a direção atual do planejamento.
- [ ] Implementar o backend do sistema de acesso.
- [ ] Preparar a persistência de dados com PostgreSQL.
- [ ] Implementar o fluxo de cadastro e autenticação.
- [ ] Estudar e aplicar os cuidados de segurança necessários ao tratamento de credenciais e sessões.
- [ ] Integrar a interface ao backend.
- [ ] Testar os fluxos implementados e tratar os erros identificados.
As tecnologias indicadas representam o planejamento atual e poderão ser confirmadas ou revistas durante o estudo da arquitetura.

## Fase 4 — Testes de concorrência e investigação de desempenho

Objetivo: utilizar o sistema de acesso para estudar o comportamento da aplicação quando várias pessoas tentam utilizá-la ao mesmo tempo.
- [ ] Preparar uma forma de simular múltiplos usuários realizando cadastros e acessos.
- [ ] Executar testes com diferentes volumes de usuários simultâneos.
- [ ] Observar tempos de resposta, falhas e gargalos.
- [ ] Investigar os problemas encontrados e testar possíveis soluções.
- [ ] Documentar os resultados e as decisões tomadas.
A intenção não é afirmar que o Study-EL já suportará milhares ou milhões de usuários. Quero criar simulações controladas para observar como o sistema se comporta, identificar limitações e aprender a lidar com problemas de concorrência e desempenho. Conceitos como cache e escalabilidade poderão ser explorados quando houver uma necessidade técnica que justifique seu uso.

## Fase 5 — Estrutura dos laboratórios e evolução da plataforma

Objetivo: estabelecer como novos conhecimentos poderão ser aplicados dentro do Study-EL.
- [ ] Definir uma estrutura inicial para os laboratórios de estudo.
- [ ] Identificar uma primeira necessidade da própria plataforma que justifique um novo laboratório ou módulo.
- [ ] Implementar essa parte mantendo sua relação com o propósito do Study-EL.
- [ ] Registrar os conceitos e tecnologias aplicados.
- [ ] Identificar partes que possam ser revistas ou reimplementadas com novos conhecimentos.
O conteúdo e a ordem dos laboratórios ainda não estão definidos. As escolhas devem surgir das necessidades do projeto e dos conhecimentos que eu quiser aplicar, sem inserir sistemas desconectados apenas para praticar uma tecnologia.
---
### Possibilidades futuras — ainda em avaliação

As ideias abaixo fazem parte da direção que imagino para o Study-EL, mas ainda não são compromissos de implementação:
- Trilhas de conhecimento: organizar referências de estudo, como aulas, canais, livros, repositórios e documentação, para ajudar outras pessoas a estudar determinados assuntos e encontrar caminhos para praticá-los.
- Participação de outros estudantes: permitir que outras pessoas acompanhem o projeto, se inspirem nele e, futuramente, contribuam documentando e aplicando conhecimentos na resolução de necessidades reais da plataforma.
- Novos laboratórios e sistemas internos: ampliar o ambiente conforme novas necessidades e oportunidades de aprendizado aparecerem.
- Revisão de tecnologias e soluções: reconstruir ou aprimorar partes da aplicação quando novos conceitos, padrões ou ferramentas justificarem a mudança.
Critério para atualizar o roadmap
Uma nova etapa deve entrar neste planejamento quando houver uma razão clara para ela existir no Study-EL. O roadmap deve acompanhar o desenvolvimento real: itens concluídos devem refletir entregas verificáveis, ideias ainda incertas devem permanecer identificadas como possibilidades e mudanças de direção devem ser ajustadas sem tentar preservar um plano que deixou de fazer sentido.
