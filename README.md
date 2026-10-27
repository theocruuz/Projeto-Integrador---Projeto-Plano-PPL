# Projeto-Integrador---Projeto-Plano-PPL
Projeto integrador dos alunos: Emily Beatriz, Leonardo Gil, Luis Fernando, Mayra Madalena, Thayne Estela e Théo Vítor
Nome da Equipe: Projeto Plano
Turma: Mecatrônica 3BV
Professor Técnico: Arlindo Ricarte

## Integrantes e áreas de atuação

| Leonardo | Piloto e calibração | Testes de dirigibilidade, calibração e operação |
| Luís Fernando e Beatriz | Chassi, direção, transmissão e montagem |
| Thayne | Projeto e documentação | Arquitetura, desenhos, organização da documentação |
| Théo | Eletrônica e integração elétrica | Alimentação, drivers, motores, sensores e conexões |
| Mayra | Software e controle | Comunicação, controle, sensores e automação |

# Soluções encontradas

## 1. Objetivo do projeto

Desenvolver um veículo terrestre em pequena escala para participação na Competição de Carrinhos do Projeto Integrador. O veículo deverá percorrer a pista definida pela organização, respeitando os requisitos do regulamento e utilizando a interface de controle disponibilizada.
## 2. Conceito da solução

Descrever, de forma objetiva, a solução escolhida pela equipe.

Exemplo:

- arquitetura de tração: diferencial com dois motores;
- direção: volante disponibilizado pelos orientadores.___________________;
- controlador principal: ____________________;
- driver de motores: ____________________;
- câmera embarcada: celular____________________;
- estratégia de alimentação: ____________________;
- sensores adicionais, se houver: ____________________;
- recursos de automação, se houver: ____________________.

---

## 3. Arquitetura geral



### Subsistemas

- **Mecânica:** Chassi terceirizado.
- **Eletrônica:** Circuito PWM.
- **Software:** Código integrado no ESP.
- **Comunicação:** via Wifi.
- **Alimentação:** Baterias.

---

## 4. Estado atual do desenvolvimento
Carro andando de forma independente via Bluetooth.

### Concluído

- [X] Definição da arquitetura geral
- [ ] Projeto mecânico inicial
- [ ] Diagrama elétrico inicial
- [ ] Comunicação com o sistema da organização
- [X] Controle dos motores em bancada
- [X] Integração eletroeletrônica
- [X] Teste do veículo em movimento
- [ ] Integração da câmera
- [ ] Outros: ____________________

### Em desenvolvimento

Otimização do carro.

---

## 5. Planejamento

O planejamento semanal da equipe está disponível em:

[`PLANEJAMENTO.md`](PLANEJAMENTO.md)

O registro semanal de atividades está disponível em:

[`PROGRESSO.md`](PROGRESSO.md)

---

## 6. Documentação técnica

Organizar a documentação técnica, preferencialmente, nas seguintes pastas:

```text
docs/
├── arquitetura/
├── mecanica/
├── eletronica/
├── software/
└── testes/
```

### Documentos disponíveis

- Arquitetura geral: ____________________
- Projeto mecânico: ____________________
- Diagrama elétrico: ____________________
- Documentação do software: ____________________
- Lista de materiais: ____________________
- Registros de testes: ____________________

---

## 7. Materiais e componentes

ESP 32
Ponte H
Baterias.

---

## 8. Comunicação com a organização

## 9. Testes realizados

Registrar os testes relevantes do projeto. Para registros mais detalhados, utilizar `docs/testes/`.

| Data | Teste | Resultado | Próxima ação |
|---|---|---|---|
| __/__/2026 | ____________________ | ____________________ | ____________________ |

---

## 10. Observações

Registrar aqui informações importantes que não se encaixem nas demais seções.
