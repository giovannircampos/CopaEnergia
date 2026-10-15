# 🏢 Agendamento de Sala de Reunião — Copa Energia

> Aplicação web leve, responsiva e em tempo real para gestão e agendamento da **Sala Sustentabilidade** na unidade da Copa Energia.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/giovanni-rocha-51485031a/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
[![Firebase](https://img.shields.io/badge/Firebase_Realtime_DB-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com/)

---

📅 Sistema de Agendamento de Sala de Reunião — Sala Sustentabilidade
Uma aplicação web progressiva (PWA), moderna e em tempo real desenvolvida para otimizar o fluxo de agendamentos e a gestão da Sala Sustentabilidade na unidade da Copa Energia.

O sistema foi concebido para resolver conflitos de horários, automatizar a libertação de salas por falta de comparência e proporcionar uma experiência simples e fluida tanto no Computador como no Telemóvel.

💡 Sobre o Projeto
Em ambientes corporativos com elevado fluxo de reuniões, o uso ineficiente de salas de reunião (como reservas abandonadas ou sobreposição de horários) gera perda de produtividade.

Este projeto oferece uma solução centralizada, conectada em tempo real ao Firebase Realtime Database, permitindo que os colaboradores consultem disponibilidades, agendem slots de 30 minutos, realizem check-in presencial e sincronizem os seus compromissos diretamente com o Microsoft Teams, Outlook ou calendários nativos via ficheiro .ics.

✨ Funcionalidades Principais
⏱️ Gestão Inteligente de Horários
Visão Diária e Semanal: Consulta rápida do mapa de ocupação da sala por dia ou ao longo de toda a semana.

Grades Dinâmicas: Slots estruturados de 30 minutos (das 08:00 às 18:00).

Barra de Ocupação: Indicador visual em tempo real do percentual de uso da sala na data selecionada.

🛡️ Validação & Autenticação Corporativa
Perfil Integrado: Identificação com Nome, Setor, E-mail Corporativo (@copaenergia.com.br) e PIN de segurança de 4 dígitos.

Ações Autenticadas: Cancelamentos e alterações exigem a validação do PIN do titular, garantindo a integridade dos dados.

Normalização de E-mail: Garantia de sincronização perfeita entre diferentes dispositivos (PC e telemóvel) independentemente da formatação de maiúsculas/minúsculas.

🔄 Automação & Check-in
Check-in Obrigatório: Botão para confirmar a presença no início da reunião.

Libertação Automática (Auto-Cancel): Algoritmo que cancela automaticamente a reserva se o check-in não for realizado dentro de 10 minutos após o início do horário reservado.

Prorrogação Rápida (+30m): Permite estender reuniões em andamento com um clique, caso o horário seguinte esteja livre.

🔁 Agendamento Recorrente & Integrações
Suporte a Recorrência: Opção de repetir reservas por 2, 3 ou 4 semanas consecutivas.

Integração com Teams / Outlook: Gerador automático de links para adicionar a reunião ao calendário corporativo.

Exportação .ics: Download direto de convite de calendário compatível com qualquer dispositivo.

📊 Auditoria & Transparência
Histórico de Alterações: Painel de auditoria que regista todos os cancelamentos, indicando o responsável, o motivo e o horário da ação.

Sinalizador de Conexão: Indicador em tempo real do estado da conexão com a base de dados (Online/Offline).

📱 Experiência do Utilizador (UI/UX)
Modo Escuro (Dark Mode): Suporte nativo a temas Claro e Escuro.

Interface Responsiva: Design otimizado para dispositivos móveis com barra de navegação inferior fixa.

PWA (Progressive Web App): Pode ser instalado diretamente no telemóvel ou computador como uma aplicação nativa.

Alertas Personalizados: Notificações e janelas modais integradas ao design do sistema (sem depender de pop-ups nativas do navegador).

🛠️ Tecnologias Utilizadas
Frontend: HTML5, JavaScript (ES6+)

Estilização: Tailwind CSS (com suporte nativo a Dark Mode)

Ícones: Lucide Icons

Base de Dados em Tempo Real: Firebase Realtime Database

PWA / Offline: Service Worker, Manifest JSON

Tipografia: Google Fonts (Montserrat)

---

## 👤 Autor

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/giovanni-rocha-51485031a/)

**Giovanni Rocha**  
*Dev Front-end Jr | React | HTML | CSS | JavaScript | UI/UX*

