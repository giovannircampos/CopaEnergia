# 🏢 Agendamento de Sala de Reunião — Copa Energia (SJC)

> Aplicação web leve, responsiva e em tempo real para gestão e agendamento da **Sala Sustentabilidade** na unidade da Copa Energia em São José dos Campos.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/giovanni-rocha-51485031a/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
[![Firebase](https://img.shields.io/badge/Firebase_Realtime_DB-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com/)

---

## 📌 Sobre o Projeto

Este projeto foi desenvolvido para resolver conflitos de horários e otimizar a utilização do espaço colaborativo da **Sala Sustentabilidade**. Com uma interface moderna e intuitiva, a aplicação permite que os colaboradores consultem a ocupação em tempo real, reservem blocos de horário e gerenciem os seus compromissos corporativos sem complicações.

---

## ✨ Principais Funcionalidades

### 🗓️ Visualização de Agendamentos
- **Visão Diária & Semanal:** Alternância simples entre a agenda do dia e a grelha completa da semana (Segunda a Sexta).
- **Destaque do Dia Atual:** Marcação visual automática da coluna "Hoje" na visão semanal.
- **Diferenciação por Cores:**
  - 🟢 **Verde (Você):** Compromissos agendados pelo utilizador logado.
  - 🟠 **Laranja (Copa):** Compromissos agendados por outros colaboradores.
  - ⚪ **Livre:** Espaços disponíveis para reserva rápida com um único clique.
- **Indicador de Ocupação:** Barra em tempo real que calcula a percentagem de ocupação do dia.

### ⚡ Agendamento e Regras de Negócio
- **Agendamento Rápido:** Clique direto em qualquer célula "Livre" para abrir o formulário pré-preenchido.
- **Validação Anti-Conflito:** Impede a sobreposição de horários e bloqueia agendamentos simultâneos para o mesmo colaborador.
- **Atalhos de Data:** Botões para navegação rápida entre "Hoje" e "Amanhã".
- **Filtros Personalizados:**
  - **Filtro "Minhas":** Esmaece as reuniões de terceiros para destacar apenas os seus compromissos.
  - **Filtro "Livres":** Exibe apenas horários vagos.

### 🔔 Notificações & Integrações
- **Notificação Automática do Navegador:** Alerta nativo de encerramento emitido 5 minutos antes do fim da reunião.
- **Exportação para Agenda:** Integração direta para adicionar a reunião ao **Outlook / Microsoft Teams** ou descarregar o ficheiro `.ics`.
- **Modo Escuro / Claro:** Suporte a tema escuro ajustável com persistência em `localStorage`.

### 🛡️ Segurança & Auditoria
- **Autenticação por PIN:** Requer um PIN corporativo de 4 dígitos para autorizar cancelamentos.
- **Log de Auditoria:** Registos gravados no Firebase com o motivo do cancelamento e quem executou a ação.

---

## 🛠️ Tecnologias Utilizadas

- **Frontend:** HTML5, Tailwind CSS (via CDN) e Vanilla JavaScript (ES6+).
- **Ícones:** Lucide Icons.
- **Backend & Database:** Firebase Realtime Database.
- **Estilização & Tipografia:** Google Fonts (*Montserrat*).

---

## 👤 Autor

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/giovanni-rocha-51485031a/)

**Giovanni Rocha**  
*Dev Front-end Jr | React | HTML | CSS | JavaScript | UI/UX*

