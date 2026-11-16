# Vezzo

**Plataforma web para busca, agendamento e gerenciamento de consultas entre pacientes e profissionais autônomos da área da saúde.**

## Sobre o projeto

O Vezzo é uma aplicação web responsiva que busca facilitar a organização dos agendamentos e a comunicação entre pacientes e profissionais autônomos da área da saúde. A plataforma reúne, em um único ambiente, a busca por profissionais, a consulta de horários disponíveis e o gerenciamento das consultas.

O sistema considera as necessidades dos dois perfis de usuário: pacientes, que podem localizar profissionais e organizar seus agendamentos, e profissionais, que podem administrar suas agendas e acompanhar as solicitações de atendimento.

A aplicação é acessada pelo navegador, em computadores e dispositivos móveis, sem necessidade de instalação.

## Problema

Profissionais autônomos da área da saúde precisam conciliar os atendimentos com tarefas administrativas, como organizar horários, confirmar consultas, lidar com cancelamentos e realizar remarcações. Quando essas atividades são feitas por diferentes canais, o processo pode consumir tempo e dificultar a atualização das informações.

Os pacientes também podem encontrar dificuldades para localizar profissionais, identificar horários compatíveis e acompanhar seus agendamentos. Além disso, cancelamentos e ausências podem deixar horários vagos que poderiam ser oferecidos a pessoas interessadas.

## Objetivo

Desenvolver uma plataforma digital integrada que facilite a busca, o agendamento e o gerenciamento de consultas, considerando as necessidades de pacientes e profissionais autônomos da área da saúde.

## Público-alvo

- **Pacientes:** pessoas que desejam buscar profissionais, consultar disponibilidades e organizar seus agendamentos.
- **Profissionais:** profissionais autônomos da área da saúde, como psicólogos, fisioterapeutas, nutricionistas e fonoaudiólogos, que administram seus próprios atendimentos.

O escopo do projeto é voltado a profissionais autônomos, não à gestão de clínicas.

## Funcionalidades previstas

### Área do paciente

- Cadastro, autenticação e gerenciamento de perfil.
- Busca e consulta de profissionais.
- Visualização de especialidades, modalidades e horários disponíveis.
- Agendamento, confirmação, cancelamento e remarcação de consultas.
- Entrada e acompanhamento em lista de espera.
- Solicitação de antecipação de consulta por encaixe.
- Recebimento de notificações e lembretes.
- Consulta do histórico de agendamentos.

### Área do profissional

- Cadastro, autenticação e gerenciamento de perfil profissional.
- Configuração de especialidades e modalidades de atendimento.
- Gerenciamento de agendas e horários disponíveis.
- Organização de agendas particulares e por convênio.
- Bloqueio de horários e acompanhamento dos agendamentos.
- Gerenciamento da lista de espera e das ofertas de encaixe.
- Configuração de prazos, prioridades e lembretes.
- Registro de comparecimento, ausência e anotações privadas do atendimento.

### Lista de espera e encaixe

A plataforma prevê recursos para aproveitar horários liberados por cancelamentos ou alterações na agenda. Quando uma vaga é disponibilizada, o sistema pode identificar pacientes elegíveis na lista de espera e enviar uma oferta. O paciente tem um prazo para aceitar; se a oferta expirar ou for recusada, o processo pode seguir para o próximo paciente elegível, conforme as regras definidas para a agenda.

## Tecnologias e ferramentas

| Área | Tecnologia |
| --- | --- |
| Interface | HTML5, CSS3 e JavaScript |
| Banco de dados | PostgreSQL |
| Autenticação e serviços de banco de dados | Supabase |
| Prototipação e design de interface | Figma |
| Controle de versão e hospedagem do código | Git e GitHub |

## Documentação do projeto

A documentação detalhada está organizada em [docs/wiki](docs/wiki/):

- [Visão geral](docs/wiki/Home.md)
- [Fluxo de usuários](docs/wiki/Fluxo-de-Usuarios.md)
- [Diagramas de casos de uso](docs/wiki/Casos-de-Uso.md)
- [Fluxos de eventos e diagramas de atividades](docs/wiki/Fluxo-de-Eventos.md)
- [Banco de dados e MER](docs/wiki/Banco-de-Dados-MER.md)
- [Tecnologias e arquitetura](docs/wiki/Tecnologias-e-Arquitetura.md)
- [Diagrama de classes](docs/wiki/Diagrama-de-Classes.md)
- [Protótipo e funcionalidades](docs/wiki/Prototipo-e-Funcionalidades.md)

As imagens dos diagramas extraídos do documento Vezzo_cap2.pdf devem ficar em `docs/imagens/`. O pacote de imagens acompanha a documentação para inclusão nessa pasta.

## Organização do desenvolvimento

O Vezzo está sendo desenvolvido como um Produto Mínimo Viável (MVP). As funcionalidades descritas neste README representam o escopo e os requisitos documentados do projeto; a disponibilidade de cada recurso deve ser conferida na versão atual da aplicação.

## Equipe

- Brenno Rodrigues
- Mariana Vieira
- Lucas Viana

## Repositório

[GitHub — Vezzo_AulaDanilo](https://github.com/fatecrl-ite004/Vezzo_AulaDanilo)
