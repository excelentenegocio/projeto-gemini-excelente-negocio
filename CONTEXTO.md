# Projeto: Excelente Negócio (excelentenegocio)

## 🚀 Status Atual
- **Fase:** Arquitetura inicial, configuração do Supabase e lógica de Auto-Construção por IA.
- **Último passo concluído:** Validação da estrutura enxuta do banco de dados para suportar múltiplos nichos comerciais (desde vendas corporativas complexas até vendas rápidas de balcão).

## 💡 Decisões Arquiteturais Importantes
- **Abordagem de Auto-Construção (Self-Building):** O sistema utilizará IA para adaptar-se dinamicamente à diversidade de nichos de mercado conforme o uso.
- **Núcleo do Banco de Dados (Supabase):** 
  - Foco inicial em apenas duas entidades base essenciais: **Clientes** e **Produtos/Serviços**.
  - Utilização de estruturas flexíveis (como colunas `JSONB` / metadados no PostgreSQL) para permitir que a IA armazene atributos específicos de cada nicho (ex: dados de construtoras vs. itens de um bar) sem engessar o schema principal.
- **Flexibilidade de Vendas:** O sistema deve suportar tanto vendas com cliente identificado (PJ/PF) quanto vendas rápidas de balcão (consumidor genérico).

## 🛠️ Tecnologias Utilizadas
- Supabase (PostgreSQL, Auth e Bancos de Dados)
- GitHub (Controle de versão e preservação de contexto)

## 🎯 Próximo Passo Imediato
- Criar oficialmente as tabelas iniciais (`clientes` e `produtos`) no painel do Supabase.
