Markdown
# Projeto: Excelente Negócio (excelentenegocio)

## 🚀 Status Atual
- **Fase:** Configuração final do banco de dados Supabase (tabela de Clientes ajustada).
- **Último passo concluído:** Definição da estrutura híbrida do banco: colunas básicas/universais em formato `text` (`nome_do_cliente`, `telefone`, `cpf_cnpj`, `tipo`) combinadas com uma coluna coringa **`metadata` (tipo `jsonb`)** para garantir flexibilidade de auto-construção por nicho de mercado através da IA.

## 💡 Decisões Arquiteturais Importantes
- **Abordagem de Auto-Construção (Self-Building):** 
  - Dados fixos ficam em colunas padrão do Postgres.
  - Atributos dinâmicos de cada nicho (ex: detalhes de obras para construtoras, ingredientes para bares) serão gravados na coluna **`metadata` (JSONB)**.
- **Próxima Ferramenta Alinhada (n8n):** 
  - Guardado para o próximo ciclo: o **n8n** será utilizado como motor de automação, integrações e orquestração de fluxos do sistema assim que fecharmos o Supabase.

## 🛠️ Tecnologias Utilizadas
- Supabase (PostgreSQL, Tabelas Híbridas e JSONB)
- n8n (Próxima etapa: Automações)
- GitHub (Controle de versão e preservação de contexto)

## 🎯 Próximo Passo Imediato
- Finalizar a estruturação da tabela d
