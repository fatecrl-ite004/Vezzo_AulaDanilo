# Tecnologias e arquitetura

Esta página reúne as tecnologias e ferramentas descritas no projeto Vezzo.

## Tecnologias

| Camada/uso | Tecnologia | Finalidade |
| --- | --- | --- |
| Interface | HTML5 | Estruturação das páginas |
| Estilo | CSS3 | Apresentação e responsividade |
| Interatividade | JavaScript | Comportamentos da interface |
| Banco de dados | PostgreSQL | Persistência dos dados relacionais |
| Autenticação e serviços de dados | Supabase | Autenticação e integração com o banco |
| Prototipação | Figma | Wireframes e protótipos das interfaces |
| Versionamento | Git | Controle de versões |
| Repositório | GitHub | Armazenamento do código e documentação |

## Plataforma

O Vezzo é uma aplicação web acessada pelo navegador, em computadores e dispositivos móveis. A interface é projetada para se adaptar aos diferentes tamanhos de tela, sem exigir instalação como aplicativo.

## Organização conceitual

- **Camada de apresentação:** interfaces utilizadas por pacientes e profissionais.
- **Camada de negócio:** regras de cadastro, busca, agendamento, gerenciamento de agendas, lista de espera e encaixes.
- **Camada de dados:** armazenamento e relacionamento das informações no PostgreSQL, com serviços do Supabase.

## Diagrama de arquitetura

Inserir aqui o diagrama de arquitetura, caso esteja disponível na documentação ou tenha sido elaborado pela equipe.

![Espaço reservado para o diagrama de arquitetura](../imagens/arquitetura-vezzo.png)
