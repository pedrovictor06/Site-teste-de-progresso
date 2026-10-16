# Sistema de Alocação – Teste de Progresso (protótipo de baixa fidelidade)
 
Protótipo somente front-end (HTML, CSS e JavaScript básicos). Sem servidor, sem banco de dados e com dados fictícios. Nada é salvo ao recarregar a página.
 
## Como usar
Abra o `index.html` no navegador. Na tela de login, digite qualquer matrícula e escolha o perfil.
 
## Perfis e telas
- **Aluno:** início e inscrição (US02), minha alocação (US03), aviso de mudança de sala (US05), comprovante com código (US04)
- **Coordenação:** painel (US19), configuração (US06), salas (US07), alunos e pendências (US08), distribuição com revisão, ajuste manual e publicação (US09, US10, US11), remanejamento (US12), relatórios (US13)
- **Fiscal:** lista da sala com horário da última atualização (US14, US15)
- **Regra de capacidade (US16):** vale na distribuição, no ajuste manual e no remanejamento
## Roteiro de teste sugerido
1. Entre como **Aluno** e confirme a inscrição.
2. Entre como **Coordenação** e importe a lista de alunos (menu Alunos).
3. Em **Distribuição**, gere, revise e publique.
4. Em **Remanejar**, interdite uma sala e escolha uma sala de contingência.
5. Volte como **Aluno** (veja o aviso e o comprovante) e como **Fiscal** (veja a lista).
## O que é simulado
Login, importação de lista, exportação PDF/planilha e notificações. No sistema real, isso depende de back-end.
 
## Fora do escopo
US18 (validação avançada de importação), classificada como Won't no MoSCoW.
