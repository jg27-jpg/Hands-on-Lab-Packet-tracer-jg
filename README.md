#  Packet Tracer Labs

Repositório com a documentação dos laboratórios práticos que venho desenvolvendo no **Cisco Packet Tracer**, como parte dos meus estudos em **Redes de Computadores** (Instituto Infnet) e da trilha **Cisco Networking Academy**.

O objetivo aqui é registrar cada lab com contexto, topologia, configurações e aprendizados — tanto para fixar o conteúdo quanto para servir de portfólio técnico.

---

##  Sobre

- **Curso:** Redes de Computadores — Instituto Infnet
- **Trilha complementar:** Cisco Networking Academy
- **Foco:** Fundamentos de redes, roteamento, switching e (futuramente) segurança de redes
- **Objetivo de carreira:** SOC Tier 1 Analyst

---

## 📚 Labs — Cisco Networking Academy (Network Basics)

A tabela abaixo segue a ordem dos módulos do curso **Network Basics**. Cada
linha representa um Packet Tracer feito dentro daquele módulo, com link
direto para a pasta com a documentação completa (topologia, comandos e
o que foi aprendido).

| Módulo | Packet Tracer / Lab | Tópicos | Status |
|--------|----------------------|---------|--------|
| 1 — DHCP4 | PRINTS NO DIA 15 DE AGOSTO| configuração de DHCP4 | ✅ Concluído |
| 2 — Basic Switch and End Device Configuration | [Configuração Básica de Switch](./lab02-config-basica-switch) | Configuração inicial, portas de acesso | ⏳ Planejado |
| 3 — Protocols and Models | *(a definir)* | Encapsulamento, TCP/UDP | ⏳ Planejado |
| 4 — Physical Layer | *(a definir)* | Cabeamento, mídias de transmissão | ⏳ Planejado |
| 5 — Number Systems | *(a definir)* | Binário, hexadecimal | ⏳ Planejado |
| 6 — Data Link Layer | *(a definir)* | Frames, switching | ⏳ Planejado |
| 7 — Ethernet Switching | *(a definir)* | VLANs, tabela MAC | ⏳ Planejado |
| 8 — Network Layer | [Roteamento Estático](./lab08-roteamento-estatico) | Rotas estáticas, sub-redes | ⏳ Planejado |
| 9 — Address Resolution | *(a definir)* | ARP, ND | ⏳ Planejado |
| ... | *(continuar conforme avança no curso)* | | |

>  Os nomes/números dos módulos acima são um ponto de partida — ajuste
> conforme a ordem exata que aparece no seu curso, e vá substituindo
> "a definir" pelo link real assim que o lab for criado.

---

## 🗂️ Estrutura de cada lab

Cada pasta de lab segue o mesmo padrão:

```
labXX-nome-do-lab/
├── README.md          → objetivo, topologia, comandos e resultados
├── topologia.png       → print da rede montada no Packet Tracer
└── configs/             → arquivos de configuração exportados (quando aplicável)
```

---

## 🛠️ Ferramentas utilizadas

- Cisco Packet Tracer
- Cisco Networking Academy (material teórico de apoio)

---

## 📈 Próximos passos

- [ ] Adicionar labs de VLSM e sub-redes
- [ ] Adicionar labs de OSPF
- [ ] Adicionar labs de segurança básica (port security, ACLs avançadas)

---

*Repositório em construção — novos labs são adicionados conforme avanço no curso.*








DHCP4 CONFIGURAÇÃO

![Segue prints da configuração dhcp4](topologiadhcp41.png)
