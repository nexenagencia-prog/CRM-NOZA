# NOZA Control

Painel interno para organizar a operação da NOZA: projetos e tarefas, equipe e suporte, contatos, campanhas, despesas e assinaturas, metas e faturamento. Inclui um planejador visual de feed do Instagram com grade reordenável e prévia para celular ou desktop.

## Rodar localmente

Abra `index.html` no navegador ou publique os três arquivos (`index.html`, `styles.css` e `app.js`) em um host de site estático.

## O que já funciona

- Cadastros, edição e exclusão de tarefas, equipe, chamados, contatos, campanhas, despesas/assinaturas e metas mensais.
- Visão geral com pendências de tarefas, chamados fora do prazo, contatos a retomar e renovações próximas.
- Interface com tipografia ampliada e cartões de serviços; metas e faturamento organizados em blocos mensais.
- Indicadores de faturamento previsto e realizado, metas, tráfego e custos cadastrados; filtros mensais atualizam os números e campanhas exibidos.
- Registro de funções de suporte e SDRs, responsáveis e custos mensais da equipe.
- Prazo de resposta por chamado, com contagem de atrasados e chamados sem atendente.
- Cadastro de serviços de IA e plataformas, com plano/modelo, fornecedor, frequência, renovação e responsável.
- Planejador de conteúdo: upload e redução das imagens, grade de nove posições, ordenação por arrastar e alternância entre prévia de celular e desktop.
- Exportação e importação de backup em JSON.

## Armazenamento nesta versão

Os dados ficam no `localStorage` do navegador em que o painel foi aberto. Assim, esta versão serve como protótipo funcional para estruturar a operação. Para a equipe compartilhar os mesmos registros entre pessoas e dispositivos, o próximo passo é conectar autenticação e banco de dados, por exemplo ao Supabase, com permissões por usuário. Não coloque dados reais de clientes ou chaves privadas nesta versão local.

## Publicação

É um site estático e pode ser publicado em hospedagem que aceite `index.html` na raiz. Não há dependências de build ou chaves de API no projeto.
