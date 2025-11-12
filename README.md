# Gerenciamento-tarefas-engenharia-software
Repositório de Sistema de Gerenciamento de Tarefas trabalho engenharia de software
1.📘 Introdução

Este relatório tem como objetivo demonstrar a aplicação prática dos conceitos de Gerência de Configuração de Software (GCS), por meio da utilização do Git e GitHub para controle de versão, colaboração e gestão de artefatos.

O projeto escolhido é um Sistema de Gerenciamento de Tarefas (To-Do List), que permite cadastrar, editar e excluir tarefas, bem como marcar aquelas já concluídas.

Neste projeto será apresentado como as atividades serão deivididas e praticadas pelo integrantes do projeto.

2.🧩 Planejamento da Configuração

2.1📦 Itens de Configuração

Os principais itens de configuração definidos para o projeto foram:

-Código-fonte do sistema (arquivos .html, .css, .js);

-Documento README.md com descrição do projeto;

-Arquivo de configuração .gitignore;

-Relatórios e documentação do projeto;

-Scripts de teste e exemplos de uso.

2.2🏷️ Convenções de Nomeação

Foram adotadas as seguintes convenções:

-Branches com nomes descritivos, utilizando kebab-case (exemplo: feature-adicionar-tarefa);

-Commits iniciando com o tipo da alteração:

-feat: para novas funcionalidades;

-fix: para correções;

-docs: para alterações na documentação;

-refactor: para melhorias de código.

2.3🔢 Política de Versionamento

Foi utilizada a convenção SemVer (Semantic Versioning):

-1.0.0: Versão inicial do sistema;

-1.1.0: Inclusão de novas funcionalidades;

-1.1.1: Correções de bugs ou pequenas alterações.

2.4🌿 Política de Branching

O modelo adotado foi baseado em Git Flow, com as seguintes branches principais:

-main – versão estável do código;

-develop – branch de desenvolvimento;

-feature/* – branches para novas funcionalidades;

-hotfix/* – branches para correções rápidas.

2.5💾 Estratégia de Backup e Recuperação

Como o projeto está hospedado no GitHub, o próprio repositório remoto atua como backup principal.
Cada integrante também mantém uma cópia local atualizada. Em caso de falha ou exclusão acidental, o código pode ser restaurado via clone do repositório remoto.

3.🤝 Controle de Versão e Colaboração

Cada integrante trabalhou em branches diferentes:

- Matheus Rocha: feature-interface

- Ellen Domeni: feature-validacao-form

- Maria Eduarda: feature-marcar-tarefa

- Luiz Felipe: hotfix-correcao-css

Durante o desenvolvimento, foram simulados conflitos intencionais ao editar a mesma função no arquivo script.js.
Após detectar o conflito no pull request, foi feita a resolução manual, escolhendo as partes corretas de cada branch.

Os commits seguiram uma convenção padronizada, por exemplo:

- feat: adicionar botão de excluir tarefa
- 
- fix: corrigir erro na função de validação
- 
- docs: atualizar README com instruções de uso

Após os merges bem-sucedidos, foram criadas tags de versão:

- v1.0.0 – versão inicial
- v1.1.0 – inclusão da função “editar tarefa”
- v1.1.1 – correção de bug na exclusão de tarefa

4.🧾 Histórico de Commits (Exemplo)

       AUTOR     |           MENSAGEM DO COMMIT	                |    DATA
_________________________________________________________________________________________

Matheus Rocha	   |      feat: criar estrutura inicial do projeto	  |     03/11/2025

_________________________________________________________________________________________

Ellen Domeni	   |      feat: adicionar validação de formulário	  |     04/11/2025

_________________________________________________________________________________________

Maria Eduarda	   |      feat: implementar função de marcar tarefa       |     04/11/2025

_________________________________________________________________________________________

Luiz Felipe	   |      fix: corrigir erro de CSS	                |     05/11/2025

_________________________________________________________________________________________

Matheus Rocha    |      merge: integrar branch develop com main	  |     06/11/2025



5.🧠 Dificuldades e Soluções Adotadas

                DIFICULDADES     |                                   SOLUÇÃO
______________________________________________________________________________________________________________________________

Conflitos de merge simultâneos	 |      Reunião rápida entre os membros e uso da ferramenta de comparação visual do GitHub

______________________________________________________________________________________________________________________________

Falhas de push por autenticação     |      Configuração de tokens pessoais (PAT) e SSH keys

______________________________________________________________________________________________________________________________

Erros em commits indevidos          |      Uso do comando git revert para desfazer alterações com segurança


