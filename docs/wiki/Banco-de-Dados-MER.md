# Banco de dados e Modelo Entidade-Relacionamento

O banco de dados do Vezzo foi modelado para armazenar informações dos perfis, pacientes, profissionais, agendas, horários, consultas e processos relacionados à lista de espera e às notificações.

## Tecnologias
- **PostgreSQL:** sistema gerenciador do banco de dados relacional.
- **Supabase:** serviços de autenticação e banco de dados utilizados no projeto.

## Modelo Entidade-Relacionamento

O MER apresenta as tabelas do banco de dados e seus relacionamentos. A figura corresponde à Figura 29 do Apêndice E do TCC.

![Figura 29 — MER do Vezzo](../imagens/figura-29-mer-vezzo.jpg)

## Estrutura das tabelas

O Apêndice D descreve campos, tipos, restrições e finalidades das tabelas:
`profiles`, `pacientes`, `profissionais`, `agendas`, `horarios`, `consultas`, `fila_espera`, `notificacoes`, `confirmacoes`, `anotacoes_privadas`, `preferencias_encaixe`, `ofertas_encaixe`, `bloqueios`, `recorrencias`, `reagendamentos`, `avaliacoes` e `configuracoes_profissional`.

**Legenda:** PK = chave primária; FK = chave estrangeira; NN = NOT NULL; UQ = UNIQUE. Os identificadores são UUID, salvo indicação específica no documento.