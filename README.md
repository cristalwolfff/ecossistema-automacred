### 🏦 Automacred: Arquitetura de Crédito Digital Automatizado
*(Powered by n8n, Supabase, WhatsApp Cloud API & Banco Facta)*

![n8n](https://img.shields.io/badge/Orquestração-n8n-FF6666?style=for-the-badge&logo=n8n&logoColor=white)
![Supabase](https://img.shields.io/badge/Database_&_Cofre-Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![WhatsApp API](https://img.shields.io/badge/Mensageria-WhatsApp_Cloud_API-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)
![APIs](https://img.shields.io/badge/Motor_de_Decisão-API_Bancária-007ACC?style=for-the-badge)

**"Um ecossistema de automação complexo criado para conectar bancos de dados, sistemas de pagamento e CRMs sem intervenção humana."**   *Status: 🚀 Serviço B2B Ativo & Homologado.*

![Card Automacred](automacred_card_site_cristalwolf_800x450_prop16-9.png)

------------------------------------------------------------------------

## **💡 Visão Estratégica do Projeto**

O **Automacred** é um ecossistema de automação avançada de crédito digital orquestrado via n8n. O projeto foi desenhado para gerenciar a comunicação e o fluxo de dados em tempo real entre o cliente final, o banco de dados e o motor de decisão bancária, garantindo agilidade e segurança em simulações de crédito consignado para trabalhadores CLT.

Esta solução substitui processos manuais e conexões frágeis por uma infraestrutura robusta de governança de dados, focada na estabilidade da operação mesmo diante de oscilações de APIs externas.

---

## **🛑 O Desafio (A Dor do Negócio)**

* ❌ **Custos Invisíveis e Desperdício:** Falta de otimização no fluxo gerava altos custos de requisição nas APIs de consulta de crédito.  
* ❌ **Instabilidade de Integrações:** Quedas ou oscilações no sistema bancário faziam com que o fluxo quebrasse e o cliente ficasse sem resposta no meio do atendimento.  
* ❌ **Fraudes e Duplicidade:** Ausência de controle rigoroso permitia a utilização de telefones duplicados vinculados a CPFs distintos, comprometendo a integridade da base.  
* ❌ **Triagem Manual:** Perda de tempo processando leads desqualificados (Não-CLT) no CRM e no sistema financeiro.

---

## **🚀 A Solução (A Paz)**

Desenvolvi uma arquitetura de integração robusta e segura que viabiliza o fluxo de crédito de ponta a ponta. A "Força de Trabalho Digital" atende o lead B2C de forma empática no WhatsApp, realiza a qualificação (CLT), consulta os limites pré-aprovados diretamente no banco e atualiza o funil de vendas, tudo orquestrado com tratamentos rigorosos contra falhas de sistema.

---

## **🛠️ Stack Tecnológico & Decisões de Arquitetura**

| Tecnologia | Papel na Arquitetura | Decisão de Engenharia |
| :---- | :---- | :---- |
| **n8n** | Orquestração & Lógica | Plataforma principal para desenvolvimento do workflow avançado, conectando todas as pontas de forma síncrona. |
| **Supabase** | Banco de Dados & Estado | Gerenciamento de estado e armazenamento relacional focado em governança e roteamento seguro das mensagens. |
| **WhatsApp Cloud API** | Interface de Mensageria | API oficial da Meta para garantir a estabilidade da comunicação B2C e conformidade com políticas de privacidade. |
| **API Facta** | Motor de Decisão Bancária | Consulta direta online para devolução exata de limites, parcelas e taxas pré-aprovadas em tempo real. |
| **AtenderBem** | CRM / Funil de Vendas | Plataforma de atendimento omnichannel para centralizar leads qualificados e gerenciar o processo de venda. |

---

## **⚙️ Engenharia & Principais Funcionalidades**

### **1\. Tratamento de Exceções Avançado (Error Handling)**

* **Loops de Retentativa:** Sistema programado para lidar com quedas e oscilações do sistema bancário, criando filas de espera automáticas para garantir que o cliente nunca fique sem resposta.  
* **Prevenção de Quebras:** Intervenções de engenharia sob medida para garantir a fluidez ininterrupta da operação.

### **2\. Governança e Segurança de Dados**

* **Travas Antifraude:** Bloqueio sistêmico para impedir a utilização de telefones duplicados atrelados a CPFs diferentes, protegendo a integridade da consulta.  
* **Integridade Síncrona:** Garantia de que os dados do cliente fluam do WhatsApp para o Supabase sem perdas durante o roteamento.

### **3\. Otimização de Custos e Triagem Inteligente**

* **Esteira de Consultas Otimizada:** Construção lógica desenhada especificamente para mitigar os custos de requisição das APIs.  
* **Filtro Automático de Qualificação:** Regras de negócio implementadas para realizar o *reset* ou a desqualificação automática de leads Não-CLT tanto no banco de dados quanto no CRM, limpando o funil de vendas.

---

## **🏆 Impacto & Resultados de Negócio**

* **Operação Estável e Resiliente:** O tratamento de erros garantiu uma simulação de crédito ininterrupta, protegendo as vendas das oscilações de infraestrutura de terceiros.  
* **Redução de Custos de API:** O desenvolvimento de uma esteira inteligente otimizou o consumo de requisições.  
* **Processamento Rápido e Seguro:** A consulta síncrona ao motor do banco devolve limites reais para o cliente instantaneamente, com atendimento processual e empático.

---

##### 🤝 Vamos Transformar a sua Operação
Estou disponível para consultoria freelance, arquitetura de sistemas e implementação técnica. Se você tem um gargalo custando tempo, dinheiro ou clientes, vamos construir uma **Força de Trabalho Digital** para resolvê-lo.

**Pronto para automatizar? Fale diretamente comigo:**

[![WhatsApp](https://img.shields.io/badge/WhatsApp-Vamos_Conversar-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/5534999602073?text=Ol%C3%A1%21+Gostaria+de+mais+informa%C3%A7%C3%B5es) 
[![Workana](https://img.shields.io/badge/Workana-Me_Contrate-0096D6?style=for-the-badge&logoColor=white)](https://www.workana.com/freelancer/f09407642ce3ac82e2dceeba95ef3509)
[![Upwork](https://img.shields.io/badge/Upwork-Me_Contrate-14a800?style=for-the-badge&logo=upwork&logoColor=white)](https://www.upwork.com/freelancers/~01e86eb238637e8561?mp_source=share)

*"Eu programo com o contexto de uma Diretora e a curiosidade de uma Maker."*


