Fluxo de Consulta — Agendamento inteligente para consultórios particulares
Equipe: Brenno Rodrigues, Mariana Vieira, Lucas Viana
Público-alvo: Profissionais autônomos de atendimento particular (ex: psicólogos) que gerenciam a própria agenda, e seus pacientes/clientes
Tipo de aplicação: Aplicação web responsiva (mobile-first)
Plataforma(s): Web (acessível via navegador em celular ou computador, sem necessidade de instalação)
Domínio: Saúde/bem-estar — atendimento particular (ex: psicologia)
Previsão de entrega: (definir conforme cronograma da disciplina)
Visão geral
Sistema web de agendamento para profissionais autônomos de atendimento particular (com foco em psicólogos, mas aplicável a outros profissionais de consulta individual), com fila de espera automática e realocação de horários quando um paciente cancela ou falta. O sistema resolve tanto o lado do profissional (agenda organizada, menos tempo perdido com faltas) quanto o do paciente (interface simples pra marcar consulta e entrar em lista de espera por um horário melhor).
Problema
Profissionais autônomos de atendimento particular, como psicólogos, costumam gerenciar a própria agenda de forma manual — WhatsApp, papel, planilha ou agendas genéricas que não são pensadas pra esse tipo de atendimento. Isso gera três problemas concretos:

Faltas e cancelamentos de última hora geram horários vagos que poderiam ser preenchidos por outro paciente, mas o profissional não tem tempo/ferramenta pra avisar rapidamente quem estava interessado naquele horário.
Gestão manual consome tempo do profissional, que precisa responder mensagem por mensagem pra marcar, remarcar e confirmar consultas, tempo que poderia estar dedicado ao atendimento.
Pacientes que querem um horário específico (já ocupado) não têm como "entrar na fila" de forma organizada — dependem de lembrar de perguntar de novo depois.

Esse problema é relevante porque afeta diretamente a renda do profissional autônomo (horário vago = sessão não paga) e a experiência do paciente, que muitas vezes desiste de tentar remarcar.
Solução proposta
Uma plataforma web com dois módulos:

Módulo do paciente: interface simples pra visualizar horários disponíveis com aquele profissional, agendar consulta, ou entrar em uma fila de espera quando o horário desejado estiver ocupado, com lembretes automáticos antes da sessão.
Módulo do profissional: painel para visualizar a agenda do dia/semana, registrar faltas/cancelamentos e ter a realocação automática do horário para o próximo paciente da fila de espera, com notificação automática enviada a ele.

O diferencial central é a automação da realocação: em vez do profissional precisar avisar manualmente quem queria aquele horário, o sistema identifica quem está na fila de espera e libera o horário automaticamente para o próximo interessado, notificando-o na hora.
Funcionalidades
Cadastro e login do profissional (agenda própria) e do paciente
Visualização de horários disponíveis por dia/semana
Agendamento de consulta em horário livre
Entrada automática em fila de espera quando o horário desejado está ocupado
Realocação automática do horário em caso de falta/cancelamento, com notificação ao próximo da fila
Lembretes automáticos antes da consulta (e-mail ou WhatsApp)
Painel do profissional para gerenciar agenda, faltas e confirmações
Histórico de consultas do paciente com aquele profissional
Diferencial / Concorrência
Existem ferramentas de agendamento genéricas no mercado (Calendly, Google Agenda, agendas de clínica como Doctoralia), que resolvem bem o agendamento simples, mas nenhuma delas trata a fila de espera com realocação automática como o núcleo do sistema — o horário vago por falta geralmente fica perdido até o profissional divulgar manualmente que abriu. Grupos de WhatsApp e agendas manuais, que são o que profissionais autônomos mais usam hoje, não têm nenhuma automação.

O diferencial do projeto está em resolver especificamente o problema do horário perdido por falta, algo que ferramentas de agenda genéricas não tratam como funcionalidade própria, e em ser pensado pro fluxo real de um profissional autônomo (poucos horários por dia, relação mais pessoal com o paciente) em vez de agendas corporativas complexas.
Inovação / Criatividade
Automação como núcleo do sistema: a realocação de horário não depende do profissional lembrar de avisar alguém — o sistema faz isso sozinho.
Pensado pro fluxo real de atendimento particular: poucos horários por dia, relação de confiança com o paciente, necessidade de discrição (dado sensível de saúde mental, por exemplo).
Redução de perda de renda do profissional por meio de um problema de automação bem definido e mensurável (taxa de reaproveitamento de horários vagos).
Escopo do projeto
Essencial (MVP — obrigatório)
Cadastro/login do profissional e do paciente
Listagem de horários disponíveis da agenda do profissional
Agendamento em horário livre
Entrada em fila de espera quando o horário desejado está ocupado
Realocação automática do horário para o próximo da fila em caso de falta/cancelamento
Painel do profissional para visualizar agenda e registrar faltas/cancelamentos
Importante (se houver tempo)
Lembretes automáticos por e-mail antes da consulta
Histórico de consultas do paciente
Confirmação de presença pelo paciente (reduz falta não avisada)
Opcional (baixa prioridade)
Notificação via WhatsApp (em vez de só e-mail)
Suporte a múltiplos profissionais na mesma plataforma (ex: uma clínica com vários psicólogos)
Pagamento/sinal online no ato do agendamento
Planejamento (simplificado)
Etapa
Descrição
Prazo
1
Definição do projeto, requisitos e modelagem do banco de dados
1 mes
2
Desenvolvimento do módulo do paciente (agendamento e fila de espera)
1 mes
3
Desenvolvimento do painel do profissional e da realocação automática
2 semanas
4
Integração dos módulos e implementação de lembretes
2 semanas
5
Testes de usabilidade e ajustes
1 mes
6
Entrega final e documentação
1 mes

Tecnologias (opcional neste momento)
Frontend: React (mobile-first), interface simples e direta
Backend: Node.js ou PHP, com API para gerenciar agenda e fila
Banco de dados: PostgreSQL ou MySQL (relacional, adequado para regras de fila e integridade de dados)
Notificações: e-mail (ex: serviço SMTP gratuito) como base; WhatsApp como extensão opcional
Hospedagem: Vercel/Render (frontend e backend) para ambiente de desenvolvimento e demonstração

