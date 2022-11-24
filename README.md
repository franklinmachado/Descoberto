# Descoberto

![Logo App Descoberto](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhOIX28KFUbhYIzj1LNaOeODE3b5kELRMTNbafvx63agJ_vXjDx4I4EDY6ymQ2UW5Cl68G28OV1GpZ388SZP_fJeXx-dp1uakX__HkJHM6PitzkH2ctjlOb9-J97aKkMq1JAnMtPlctCc04eVXWdpJB-o7mVw7p9ssUZxwEgiAtrByMN909a1kSDQqxRg/s320/Descoberto%20logo.png)

### Sobre

Um aplicativo para obter cupons de desconto em lojas e esses cupons de desconto posteriormente podem ser convertidos em VOUCHERS para compras em lojas conveniadas.

---

## Funcionalidades

- [x] Cadastro facil.
- [x] Cupons de desconto liberados pelas lojas.
- [x] Conversão dos cupons em VOUCHERS.
- [x] Compras com o voucher.
- [x] Primeiro acesso gera cupom.
- [x] Jogo (roleta diária) - prêmios de cupons, pontos.
- [x] Login diário por 7 dias junta pontos para um cupom.
- [x] Indicação gera cupom.
- [x] Seguir em redes sociais gera cupom.
- [x] Comentar nas redes sociais ganha ponto.
- [x] Compartilhar cupons 3 dias antes de expirarem com outros usuários para ganhar pontos.
- [x] Níveis de pontuação.

---

## Product Backlog

| ID  | História                         | Sprint |
| --- | -------------------------------- | ------ |
| 1   | Cadastro Básico de Usuários      | #SP1   |
| 2   | Cadastro Completo de Usuários    | #SP1   |
| 3   | Cupons de desconto               | #SP1   |
| 4   | VOUCHERS                         | #SP1   |
| 5   | Jogos                            | #SP2   |
| 6   | Acesso diário para cupons extras | #SP2   |

---

## Critérios de Aceitação

| #         | Feature Jogo                                                 |
| --------- | ------------------------------------------------------------ |
| Ação      | Usuário quer mais cupons e de forma rápida.                  |
| Processo  | Roda a roleta diariamente e/ou por "n" tentativas.           |
| Resultado | Recebe cupons ou pontos para serem trocados para um voucher. |

| #         | Feature Acesso diário                                                           |
| --------- | ------------------------------------------------------------------------------- |
| Ação      | Usuário usa o aplicativo diariamente para marcar presença e juntar mais cupons. |
| Processo  | Fazer check-in diário no aplicativo.                                            |
| Resultado | Obter pontos para serem trocados por cupons.                                    |

---

## Features menores

| Feature                       | Partes                                                                                               |
| ----------------------------- | ---------------------------------------------------------------------------------------------------- |
| Cadastro Básico de Usuários   | E-mail, senha, confirmação de senha, verificação de e-mail, captcha, cupom de primeiro acesso.       |
| Cadastro Completo de Usuários | Nome completo, data de nascimento, cpf, endereço, telefone, sexo.                                    |
| Cupons de desconto            | Validar cupons, acumulador de cupons, expiração dos cupons, controle de cupons usados, notificações. |
| Vouchers                      | Troca de cupons por vouchers, expiração de voucher, controle de voucher usados, notificações.|
| Jogos                         | Roleta, clique do usuário, resultado do sorteio, notificações.                                       |
| Acesso diário                 | Calendário para check-in, acumulador de pontuação, notificações.                                     |

---

## User Story

| User Points Stories                                |           |
| -------------------------------------------------- | --------- |
| Projeto : Descoberto, App de desconto do adalberto |
| Historias                                          | pontuação |
| Cadastro Básico de Usuários                        | 8         |
| Cadastro Completo de Usuários                      | 13        |
| Cupons de desconto                                 | 21        |
| VOUCHERS                                           | 34        |
| Jogos                                              | 89        |
| Acesso diário para cupons extras                   | 55        |
| total                                              | 144       |

---

## Backlog Refinement (User Story)

| Story #5      | Jogo                                                                          |
| ------------- | ----------------------------------------------------------------------------- |
| Descritivo    | Eu como usuário quero ganhar pontos ou cupons de maneira simples e divertida. |
| Justificativa |                                                                               |
| Solução       |                                                                               |

| Story #6      | Acesso diário                                                                                                                                                                                                                                                                            |
| ------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descritivo    | Eu como usuário quero juntar pontos todos os dias para trocar por cupons.                                                                                                                                                                                                                |
| Justificativa | Estimular o usuário a acessar o app todos os dias.                                                                                                                                                                                                                                       |
| Solução       | <ul><li>Abrir calendário todo dia no primeiro acesso do usuário.</li><li>Usuário seleciona data atual.</li><li>Acumula pontos na conta do usuário.</li><li>Zerar pontuação por não acesso contínuo por 7 dias ao app.</li><li>Ao fim de 7 dias, usuário pode trocar por cupom.</li></ul> |
