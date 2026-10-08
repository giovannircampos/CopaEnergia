# 📅 Agendamento de Sala de Reunião — Sala Sustentabilidade (Copa Energia)

> Aplicação web responsiva e em tempo real para gestão, consulta e auditoria de agendamentos de salas de reunião corporativas na **Copa Energia**.

---

## 💡 Sobre o Projeto

O projeto nasceu com o objetivo de solucionar gargalos comuns na gestão de espaços colaborativos, como sobreposição de horários, reservas "fantasma" e falta de visibilidade da ocupação da sala.

Embora tenha sido idealizado para atender inicialmente a uma estrutura de centro operativo, a arquitetura foi desenhada com foco em **escalabilidade**. O sistema está pronto para ser replicado em unidades maiores, filiais com alta demanda ou na Sede corporativa.

---

## 🚀 Principais Funcionalidades

- ⚡ **Sincronização em Tempo Real:** Atualizações instantâneas de disponibilidade utilizando o **Firebase Realtime Database**.
- 🔔 **Notificações do Sistema:** Alertas nativos no navegador/mobile avisando o colaborador 5 minutos antes do fim da reunião (com botão *toggle* de controle).
- 🛡️ **Prevenção de Conflitos:** Algoritmo de validação que impede agendamentos em duplicado no mesmo intervalo de tempo para o mesmo perfil.
- 🔐 **Auditoria e Segurança:** Registro detalhado de cancelamentos com exigência de PIN corporativo de 4 dígitos e justificativa.
- 📆 **Integração com Agendas:** Criação direta de eventos no **Microsoft Teams / Outlook** e download de arquivo de lembrete `.ics`.
- 📊 **Métricas de Ocupação:** Indicador visual da taxa percentual de uso da sala ao longo do dia.
- 📱 **Interface Responsiva & Dark Mode:** Design intuitivo com suporte a modo escuro e navegação otimizada para dispositivos móveis (*Thumb Zone*).

---

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estruturação semântica da aplicação e modais.
- **CSS3 / Tailwind CSS:** Estilização moderna, responsiva e suporte a tema escuro via classes utilitárias.
- **JavaScript (ES6+):** Lógica de negócios, manipulação de datas/horários, Web Notifications API e integração com APIs nativas.
- **Firebase Realtime Database:** Banco de dados NoSQL em nuvem para sincronização de dados sem latência.
- **Lucide Icons:** Biblioteca de ícones vetoriais leves.

---

## 👤 Autor

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/giovanni-rocha-51485031a/)

**Giovanni Rocha**  
*Dev Front-end Jr | React | HTML | CSS | JavaScript | UI/UX*

## 📂 Estrutura do Repositório

```text
├── index.html        # Single Page Application (HTML, Tailwind CSS, JS e lógica do Firebase)
└── README.md         # Documentação do projeto

