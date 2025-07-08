# PyTapoAware

Automação inteligente em Python para controle de lâmpadas Tapo baseada em eventos de presença via webhook.

## 📋 Descrição

**PyTapoAware** é um sistema leve e modular que acende automaticamente uma lâmpada inteligente Tapo (modelo L530 ou similares) quando recebe uma notificação externa (por exemplo, detecção de movimento de uma câmera ICSee ou aplicativo Automate).  
A automação verifica se:

- É período noturno (configurável)
- A lâmpada está acessível (online)
- A lâmpada já está ligada

Só após essas verificações, o sistema aciona a lâmpada via API.

---

## ⚙️ Funcionalidades

- ✅ Recebe eventos HTTP via Flask
- ✅ Liga automaticamente a lâmpada Tapo se for noite
- ✅ Verifica se a lâmpada já está ligada
- ✅ Suporte a reconexão (retry)
- ✅ Registro de eventos em `logs/log.txt`
- ✅ Código modular, limpo e expansível

---

## 📦 Estrutura do Projeto

