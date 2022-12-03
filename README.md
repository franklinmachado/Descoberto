# App Descoberto

![Logo App Descoberto](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiyp9l0FtsFHVmpKdKAjmVEQofOPQecSYnBtkuiVlslBUC-z7azSJRPeRZQQVBGscCLO8ACf2wekbPM4-_-zK8I5IJfKWimQIDMgrMwNWgb-OcFL5iBuBnfRDbI-jpPe86Cqnyg3K99N_1JEia7Cn0AWIVmyzk0Jgj0P1sF1K97cU3j9pXsACrdD7h60Q/s320/descoberto%20(2).jpg)

### Sobre

Um aplicativo para obter cupons de desconto em lojas e esses cupons de desconto posteriormente podem ser convertidos em VOUCHERS para compras em lojas conveniadas.

---

## Funcionalidades

- [x] Cadastro facil.
- [x] Botão de ajuda/tutorial.
- [x] Cupons de desconto liberados pelas lojas.
- [x] Conversão dos cupons em VOUCHERS.
- [x] Compras com o voucher.
- [x] Primeiro acesso gera cupom.
- [x] Jogo (roleta diária) - prêmios de cupons, pontos.
- [x] Login diário por 7 dias consecutivos dá um cupom.
- [x] Indicação gera cupom.
- [x] Seguir em redes sociais gera pontos.
- [x] Comentar nas redes sociais ganha pontos.
- [x] Compartilhar cupons 3 dias antes de expirarem com outros usuários para ganhar pontos.
- [x] Ao avaliar produtos comprados de lojas parcerias ganha pontos. 
- [x] Níveis de pontuação para quem tiver ranking.
- [x] Sobre o app.
- [x] FAQ. 

---

## Product Backlog

| ID  | História                         | Prioridade | Sprint |
| --- | -------------------------------- | -----------| ------ |
| 1   | Cadastro Básico de Usuários      | Alta       | #SP1   |
| 2   | Cadastro Completo de Usuários    | Alta       | #SP1   |
| 3   | Cupons de desconto               | Alta       | #SP1   |
| 4   | VOUCHERS                         | Alta       | #SP1   |
| 5   | Jogos                            | Baixa      | #SP2   |
| 6   | Acesso diário para cupons extras | Média      | #SP2   |
| 7   | Faq                              | Baixa      | #SP3   |

---

## Critérios de Aceitação

| #         | Feature Jogo                                                 |
| --------- | ------------------------------------------------------------ |
| Ação      | Usuário quer mais cupons e de forma rápida.                  |
| Processo  | Roda a roleta diariamente e/ou por "n" tentativas.           |
| Resultado | Pode ganhar cupons ou pontos cada vez que jogar.             |

| #         | Feature Acesso diário                                                           |
| --------- | ------------------------------------------------------------------------------- |
| Ação      | Usuário usa o aplicativo diariamente para marcar presença e acumular acessos.   |
| Processo  | Fazer check-in diário no aplicativo com o calendário.                           |
| Resultado | Ganhar um cupom por 7 logins diários consecutivos.                              |

---

## Features menores

| Feature                       | Partes                                                                                               |
| ----------------------------- | ---------------------------------------------------------------------------------------------------- |
| Cadastro Básico de Usuários   | E-mail, senha, confirmação de senha, verificação de e-mail, captcha, cupom de primeiro acesso.       |
| Cadastro Completo de Usuários | Nome completo, data de nascimento, cpf, endereço, telefone, sexo.                                    |
| Cupons de desconto            | Validar pontos e cupons, trocar pontos por cupons, acumulador de cupons, data de expiração dos cupons, histórico de cupons, troca de cupons a expirar, notificações.|
| Vouchers                      | Troca de cupons por vouchers, data de expiração de voucher, histórico de vouchers, notificações.     |
| Jogos                         | Roleta, clique do usuário, resultado do sorteio, notificações.                                       |
| Acesso diário                 | Calendário para check-in, acumulador de pontuação, notificações.                                     |

---

## User Story

| User Points Stories                                |           |
| -------------------------------------------------- | --------- |
| Projeto : Descoberto, App de desconto do Adalberto |
| `Histórias`                                        |`Pontuação`|
| Cadastro Básico de Usuários                        | 8         |
| Cadastro Completo de Usuários                      | 13        |
| Cupons de desconto                                 | 55        |
| VOUCHERS                                           | 55        |
| Jogos                                              | 89        |
| Acesso diário para cupons extras                   | 13        |
| total                                              | 233       |

---

## Backlog Refinement (User Story)

| Story #5      | Jogo                                                                          |
| ------------- | ----------------------------------------------------------------------------- |
| Descritivo    | Eu como usuário quero ganhar pontos ou cupons de maneira simples e divertida. |
| Justificativa | Motivar o usúario por meio do jogo a acessar o app e ganhar pontos ou cupons  |
| Solução |  <ul><li>Usuário acessa o app para jogar</li><li>Clica no botão para girar a roleta. </li><li>Contabiliza pontos ou cupom na conta do usuário se ele ganhar</li><li>Bloqueia as jogadas por um tempo.</li></ul>|

| Story #6      | Acesso diário                                                                                                                   |
| --- | --- |
| Descritivo    | Eu como usuário quero ganhar benefícios por logar diariamente. |
| Justificativa | Estimular o usuário a acessar o app todos os dias.             |
| Solução       | <ul><li>O acesso diário só contabilizará quando usuário abrir o calendário.</li><li>Zera os acessos se não acessar por um dia.</li><li>Ao fim de 7 dias consecutivos, usuário ganha cupom.</li>|
