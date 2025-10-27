### ☁️ **Microsoft Azure – Visão Geral (Entrega 1)**

O **Microsoft Azure** é uma plataforma de **computação em nuvem** que oferece diversos serviços, como armazenamento, bancos de dados, redes, inteligência artificial e hospedagem de aplicações. Ela permite que empresas e desenvolvedores criem, implementem e gerenciem soluções de TI de forma escalável e segura pela internet.

---

### 🏢 **Modelos de Nuvem**

* **Nuvem Pública:**
  Os recursos (servidores, armazenamento, etc.) são compartilhados entre vários clientes e gerenciados por um provedor (ex: Azure, AWS, Google Cloud).
  💡 *Mais econômica e escalável.*

* **Nuvem Privada:**
  A infraestrutura é exclusiva de uma organização. Pode ser hospedada localmente ou em um datacenter dedicado.
  💡 *Mais controle e segurança, porém custo mais alto.*

* **Nuvem Híbrida:**
  Combina recursos da nuvem pública e privada, permitindo mover dados e aplicativos entre elas conforme a necessidade.
  💡 *Mais flexível e ideal para quem busca equilíbrio entre custo e controle.*

---

### 💰 **Modelos de Custo**

* **CAPEX (Capital Expenditure):**
  Investimento em **infraestrutura física** — servidores, redes, energia, manutenção etc.
  💡 *Usado em ambientes locais (on-premise).*

* **OPEX (Operational Expenditure):**
  Pagamento por **uso de recursos**, como ocorre na nuvem (ex: pagar apenas pelo que consumir na Azure).
  💡 *Reduz custo inicial e aumenta a agilidade financeira.*

---

### ✅ **Resumo Final**

> A **Azure** adota principalmente o modelo **OPEX** e oferece soluções de **nuvem pública, privada e híbrida**, permitindo que empresas escolham o modelo que melhor equilibra **custo, segurança e flexibilidade**.

---


### ⚙️ **Pilares da Computação em Nuvem (Entrega 2)**

* **Disponibilidade:**
  É o tempo em que o serviço está ativo e funcionando. Quanto maior a disponibilidade (por exemplo, 99,99%), menor o tempo de falha permitido.

* **Escalabilidade:**
  Capacidade de **aumentar ou diminuir recursos** conforme a demanda — por exemplo, mais servidores em horários de pico.

* **Confiabilidade:**
  Garante que o sistema funcione de forma **consistente** e possa se recuperar rapidamente de falhas.

* **Segurança:**
  Protege dados e sistemas contra acessos não autorizados, com criptografia e controle de identidade.

* **Gerenciabilidade:**
  Facilidade para **monitorar, atualizar e automatizar** os serviços da nuvem.

* **Desempenho:**
  Capacidade de responder **rápido** às solicitações dos usuários e manter estabilidade.

---

### ⏱️ **Níveis de Disponibilidade (SLA da Azure)**

| **Disponibilidade (SLA)** | **Tempo máximo de inatividade por dia** | **Por semana** | **Por mês**   | **Por ano**          |
| ------------------------- | --------------------------------------- | -------------- | ------------- | -------------------- |
| **99%**                   | 14 min 24 seg                           | 1h 40min       | 7h 18min      | **3 dias 15h 39min** |
| **99,9%**                 | 1 min 26 seg                            | 10 min 4 seg   | 43 min 49 seg | **8h 45min 56s**     |
| **99,99%**                | 8,6 seg                                 | 1 min          | 4 min 23 seg  | **52 min 35s**       |
| **99,999%**               | 0,86 seg                                | 6 seg          | 26 seg        | **5 min 15s**        |

💡 *Quanto mais “9’s” no SLA, menor o tempo que o serviço pode ficar fora do ar no ano.*

---

### ✅ **Resumo Final**

> A **Azure** se baseia em pilares como **disponibilidade, escalabilidade, segurança e confiabilidade** para manter seus serviços estáveis.
> Seus níveis de **SLA** mostram o compromisso da Microsoft em manter os sistemas **sempre ativos**, com falhas que podem variar de **horas por ano (99%)** a **apenas minutos (99,999%)**.

---

### ☁️ **Modelos de Serviço na Nuvem (Entrega 3)**

A Azure oferece diferentes **níveis de serviço**, que variam conforme o quanto o **cliente gerencia** e o quanto a **Microsoft gerencia**.

---

### 🖥️ **IaaS – Infrastructure as a Service (Infraestrutura como Serviço)**

* Fornece **recursos básicos de TI**, como máquinas virtuais, redes e armazenamento.
* O usuário é responsável por instalar e gerenciar o sistema operacional e os aplicativos.
* 💡 *É como alugar um servidor pronto para configurar do seu jeito.*
* **Exemplo na Azure:** *Azure Virtual Machines, Azure Storage, Azure Virtual Network.*

---

### ⚙️ **PaaS – Platform as a Service (Plataforma como Serviço)**

* Oferece um ambiente completo para **criar, testar e implantar aplicações** sem se preocupar com a infraestrutura.
* A Microsoft cuida dos servidores, do sistema e das atualizações.
* 💡 *Ideal para desenvolvedores que querem focar apenas no código.*
* **Exemplo na Azure:** *Azure App Service, Azure SQL Database.*

---

### 💻 **SaaS – Software as a Service (Software como Serviço)**

* Fornece **aplicativos prontos** acessados via internet (sem necessidade de instalação).
* O provedor gerencia tudo: infraestrutura, plataforma e o próprio software.
* 💡 *É só usar — igual ao Outlook, Teams ou Office 365.*
* **Exemplo na Azure:** *Microsoft 365, Dynamics 365.*

---

### ✅ **Resumo Rápido**

| Modelo   | Gerenciado pelo cliente          | Gerenciado pela Microsoft   | Exemplo                |
| -------- | -------------------------------- | --------------------------- | ---------------------- |
| **IaaS** | Sistema operacional, aplicativos | Hardware e virtualização    | Azure Virtual Machines |
| **PaaS** | Aplicação e dados                | Infraestrutura e plataforma | Azure App Service      |
| **SaaS** | Apenas uso do app                | Todo o restante             | Microsoft 365          |
