Desafio Back-end PicPay

Este projeto é uma API RESTful de plataforma de pagamentos que permite transferências entre usuários e lojistas. A aplicação foi desenvolvida com foco em boas práticas de arquitetura, como separação de camadas, SOLID, e utilização de transações seguras.

🚀 Funcionalidades

Cadastro de usuários comuns e lojistas com validação de CPF/CNPJ e e-mail únicos

Transferência de valores entre usuários

Consulta a serviço externo para autorização de transferências

Notificação de pagamento via serviço externo

🔧 Tecnologias Utilizadas

Java com Spring Boot para o back-end

Banco de Dados Relacional



📚 Regras de Negócio

Usuários podem enviar dinheiro para lojistas e outros usuários

Lojistas apenas recebem transferências

Validação de saldo antes da transferência

Consultas externas para autorização e notificação

Transações reversíveis em caso de falha

📄 Endpoints

POST /transfer

{
  "value": 100.0,
  "payer": 4,
  "payee": 15
}

Realiza uma transferência de valor entre dois usuários.

🛠️ Como Rodar o Projeto

Clone o repositório

Configure o banco de dados

Execute a aplicação com mvn spring-boot:run

📋 Considerações Finais

Este projeto foi desenvolvido para demonstrar habilidades em back-end, arquitetura limpa e boas práticas de desenvolvimento. A API inclui validações de segurança, transações consistentes e uma estrutura escalável.
