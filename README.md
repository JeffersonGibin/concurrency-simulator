# Concurrency Simulator

## Descrição 

Api com algum recurso simulado para simular um cenário de concorrência.

## Requisitos

### Funcionais

| ID       | Descrição                                                                 |
|----------|---------------------------------------------------------------------------|
| RF-001   | deve receber um post e criar um regístro de pagamento                     |
| RF-002   | enviar push notifications com o status do pagamento                        |

### Não funcionais

| ID       | Descrição                                                                 |
|----------|---------------------------------------------------------------------------|
| RNF-001  | processar em menos de 100 ms                                              |
| RNF-002  | precisa ser feito em Golang                                               |
| RNF-003  | simular um ambiente de microsserviços                                     |
| RNF-004  | usar postgres como banco de dados SQL, e dynamo NoSQL                     |
| RNF-005  | usar kafka como sistema de filas                                          |
| RNF-006  | ter um sistema de tracking e observabilidade                              |
| RNF-007  | utilizar event sourcing                                                   |

## ADR
- [1 - Project Start](./docs/ADRs/1%20-%20Project%20Start.md)
- [2 - Monolith Start](./docs/ADRs/2%20-%20Monolith%20Start.md)

## High Level Architecture

- [High Level Architecture Link](https://miro.com/welcomeonboard/Ymx1M214YVEyTHpNU3BFYmVHSXV0bEVNeDhvWU10allDUjJ1Smc4eGlOcjljbEZBRldETFJrbFd1WGRZUUtVMlhRTW54Ujd5UEtEQ3BsbVFxcGo4R1lmd0xrMTVwc0ljUkQ2OU9lU2x6T2Y3RUtZczJpZGQzTStuY0l2TGZ6L0chZQ==?share_link_id=599870259324)

![image](https://github.com/user-attachments/assets/d80b429b-4e51-4925-aeb7-c75e736809ee)
![image](https://github.com/user-attachments/assets/3ac40e56-e256-4a2c-9a48-1557cd8f9e33)



