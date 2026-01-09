# 🧠 AI Medical Triage Assistant

> ⚠️ O deploy da soluçäo no N8N está atualmente fora do ar.

Um assistente de triagem médica automatizado baseado em IA, criado para simular conversas entre pacientes e profissionais da saúde, com foco em orientar o atendimento inicial.

| Participantes |
| --- |
| Pedro Motta |
| Bernardo Rohlfs |
| Hitalo Silveira |
| Eric Jardim |
| Vitor Lion |

---

## 📚 Base de Dados

Utilizamos a base de dados pública disponível no Kaggle para treinar o modelo via **fine-tuning**:

🔗 [Doctor-Patient Conversation Dataset](https://www.kaggle.com/datasets/azmayensabil/doctor-patient-conversation)

---

## ⚙️ Tecnologias Utilizadas

- **n8n** – Utilizado para orquestrar os fluxos e integrar com a IA via Webhooks
- **HTML, CSS e JavaScript Vanilla** – Aplicação frontend simples e leve
- **GitHub Pages** – Hospedagem gratuita do cliente

---

## 🚀 Acesse o projeto

Você pode interagir com o assistente diretamente por aqui:

🌐 [Demo ao vivo](https://berohlfs.github.io/AI-medical-triage-assistant/)

![Demo - Imagem](./demo.png) ⚠️ 

---

## 🛠️ Como funciona

1. O usuário envia uma mensagem via interface web simples.
2. A mensagem é enviada para um **Webhook do n8n**, que processa e encaminha para o modelo treinado.
3. O n8n retorna uma resposta baseada no histórico de diálogos médico-paciente.
4. A resposta é exibida ao usuário em tempo real.

---

## 💡 Objetivo

O projeto tem como objetivo explorar o uso de IA generativa para triagem inicial de sintomas, **não substituindo** um diagnóstico médico, mas oferecendo uma interface de apoio e orientação para usuários com dúvidas iniciais de saúde.

---

## ⚠️ Aviso

> **Este projeto é apenas para fins educacionais e de demonstração.**
> Não deve ser utilizado como substituto para aconselhamento médico profissional, diagnóstico ou tratamento.
