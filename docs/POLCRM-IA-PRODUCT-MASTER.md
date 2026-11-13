# POLCRM IA — Documento Mestre do Produto

> Fonte de verdade inicial para posicionamento, produto e evolução do POLCRM IA.
> Escopo exclusivo: POLCRM IA. Não misturar com FLUX SMX ou qualquer outra marca/produto.

## 1. Identidade e posicionamento

**Nome oficial:** POLCRM IA  
**Categoria:** CRM conversacional com inteligência artificial.  
**Natureza:** plataforma de tecnologia comercial que combina relacionamento, gestão de oportunidades, comunicação e automação.

**Posicionamento central:** o POLCRM IA ajuda empresas a organizar conversas, estruturar processos comerciais, acompanhar oportunidades e melhorar a execução das vendas com CRM, inteligência artificial, telefonia e automações.

**Promessa de valor (diretriz de posicionamento):** transformar contatos e conversas dispersas em processos comerciais organizados, acompanháveis e escaláveis.

Não prometer resultados financeiros garantidos. Benefícios e métricas precisam ser demonstrados por dados reais de clientes.

## 2. Componentes conhecidos do produto

Com base no contexto de produto disponível, o POLCRM IA contempla ou foi concebido em torno de:

- **CRM:** organização de contatos, leads, oportunidades e histórico de relacionamento.
- **Conversas:** centralização e acompanhamento de interações comerciais.
- **Inteligência artificial:** apoio à comunicação, atendimento e execução de tarefas comerciais.
- **PABX e telefonia:** recursos de telefonia empresarial.
- **Ligações:** gestão e acompanhamento de chamadas.
- **Automações:** fluxos para reduzir tarefas manuais e apoiar o processo comercial.

**Importante:** esta lista registra o escopo conhecido, não comprova que cada módulo esteja implementado, ativo ou disponível em produção. Validar cada funcionalidade no código e no ambiente real antes de apresentá-la como pronta.

## 3. Público e problemas que busca resolver

Públicos a validar e priorizar:
- Pequenas e médias empresas com operação comercial.
- Equipes de vendas e atendimento.
- Negócios que recebem leads por múltiplos canais.
- Gestores que precisam de visibilidade sobre contatos, oportunidades e desempenho.

Problemas centrais:
- Conversas e informações espalhadas em diferentes canais.
- Perda de histórico e contexto dos clientes.
- Falta de padronização no acompanhamento de leads.
- Falta de visibilidade sobre etapas e responsabilidades.
- Atividades repetitivas que podem ser automatizadas.
- Dificuldade para conectar atendimento, telefonia e processo de vendas.

## 4. Princípios de produto

1. **Conversas ligadas ao contexto:** cada interação deve contribuir para o histórico do relacionamento.
2. **Processo antes de automação:** automatizar fluxos claros, com regras e responsáveis definidos.
3. **Visibilidade comercial:** gestores devem compreender o andamento das oportunidades.
4. **Simplicidade operacional:** reduzir fricção para vendedores e atendentes.
5. **IA com supervisão:** deixar claro quando uma ação é automatizada e permitir revisão humana em decisões relevantes.
6. **Segurança e privacidade:** proteger dados pessoais e comerciais, aplicar controle de acesso e registrar ações relevantes.
7. **Integrações confiáveis:** tratar falhas, duplicidades, limites e reprocessamento de eventos.

## 5. Diretrizes de marca e comunicação

- Escrever sempre **POLCRM IA**.
- Não renomear, rebatizar ou associar o produto a FLUX SMX.
- Linguagem: tecnológica, comercial, objetiva, confiante e orientada a resultados operacionais.
- Comunicar CRM + IA + PABX + ligações + automações como proposta integrada, sem afirmar capacidades não verificadas.
- Toda peça pública deve diferenciar funcionalidades disponíveis, em implantação e planejadas.

## 6. Experiência e interface

Direção para a experiência:
- Interface moderna, profissional e responsiva.
- Hierarquia visual clara para operação diária.
- Navegação simples entre contatos, conversas, oportunidades, chamadas e automações.
- Estados explícitos: carregando, vazio, sucesso, erro e sem permissão.
- Acessibilidade, boa legibilidade e consistência entre módulos.
- Evitar efeitos visuais que prejudiquem velocidade, clareza ou usabilidade.

A identidade visual definitiva (paleta, tipografia, arquivos de logo, mascote e componentes) deve ser extraída dos ativos oficiais existentes. Não inventar códigos de cor ou redesenhar logotipos sem referência aprovada.

## 7. Requisitos técnicos e de qualidade

Ao auditar ou desenvolver:
- Identificar stack, estrutura, dependências e comandos reais do projeto antes de alterar código.
- Não presumir backend, banco, provedores, APIs ou integrações sem evidência no repositório ou ambiente.
- Nunca expor chaves, tokens, credenciais, segredos ou dados pessoais em código, logs ou documentação.
- Usar variáveis de ambiente e documentar nomes de variáveis sem registrar seus valores.
- Validar autenticação, autorização por papel, isolamento entre organizações/contas e proteção de dados.
- Implementar validação de entrada, tratamento de erros, logs sem dados sensíveis e limites de requisição.
- Testar fluxos críticos e cenários de falha antes de publicar.
- Não remover, substituir ou migrar dados de produção sem autorização explícita.

## 8. Integrações e sincronização

A conexão entre GitHub e Lovable ainda precisa ser confirmada no workspace do Lovable. A existência deste repositório no GitHub, por si só, não comprova que o projeto Lovable esteja conectado a ele.

Checklist de verificação:
- Confirmar a conta GitHub autorizada no Lovable.
- Confirmar que o projeto correto é POLCRM IA.
- Confirmar o repositório `cristianoferreirasmx/POLCRM-SITE`.
- Confirmar a branch principal `main`.
- Verificar se commits feitos no Lovable aparecem no GitHub.
- Verificar se commits feitos no GitHub são refletidos no Lovable.
- Conferir conflitos, permissões e estado de sincronização antes de editar arquivos em paralelo.

## 9. O que ainda precisa ser confirmado

Este documento é uma base estratégica inicial, não uma especificação funcional completa. Confirmar com o produto e o código:
- Funcionalidades realmente implementadas e disponíveis.
- Canais de conversa suportados.
- Recursos e limites reais da IA.
- Provedor e capacidades do PABX/telefonia.
- Automações existentes.
- Modelo de dados, entidades e relacionamentos.
- Papéis, permissões e multi-tenancy.
- Integrações externas e webhooks.
- Planos, preços, cobrança e limites comerciais.
- Métricas, resultados de clientes e provas sociais autorizadas.
- Logotipo, mascote, paleta e demais ativos oficiais.

## 10. Instrução permanente para assistentes de desenvolvimento

Você está trabalhando exclusivamente no **POLCRM IA**. Preserve o nome, o escopo e a identidade do produto. Antes de implementar qualquer recurso, inspecione o código e os ativos existentes, identifique o que já funciona e proponha mudanças compatíveis com a arquitetura atual. Não invente funcionalidades, integrações, credenciais, dados ou resultados. Não misture o POLCRM IA com FLUX SMX. Priorize segurança, confiabilidade, clareza operacional, experiência do usuário e evolução incremental.

---
Documento inicial criado a partir do contexto estratégico disponível. Atualizar somente com informações verificadas no produto, no código ou aprovadas pelo responsável.
