# Lab 02 - Configurando uma instância de Banco de Dados na Azure

Neste laboratório, explorei os principais modelos de serviços em nuvem e realizei a criação de máquinas virtuais e bancos de dados no **Microsoft Azure**.

## 🌐 Modelos de Serviços em Nuvem

Aprendi sobre os diferentes modelos de entrega de serviços na nuvem:

- **IaaS (Infrastructure as a Service)**: infraestrutura sob responsabilidade do usuário (máquinas virtuais, redes, etc.).
- **PaaS (Platform as a Service)**: plataforma fornecida pela nuvem, com menos responsabilidades para o usuário.
- **SaaS (Software as a Service)**: software completo, onde toda a infraestrutura e manutenção ficam sob responsabilidade do provedor.

---

## ⚙️ Criação de Máquina Virtual (MV)

Durante a criação de uma máquina virtual no Azure, a instrutora **Valéria Baptista** chamou a atenção para pontos importantes:

- A escolha do **sistema operacional** é feita no campo **Imagem**.
- Inicialmente foi selecionado: `Windows Server 2019 DC x64 Gen1`.
  - Uma **mensagem de alerta em vermelho** apareceu relacionada ao custo estimado.
  - Essa mensagem foi usada apenas para fins didáticos.
- Em seguida, foi selecionado `Windows Server 2019 DC x64 Gen1 Gen 2`, e o alerta sumiu.

> **Nota:** Na minha conta do Azure, a opção inicial não estava mais disponível.

**Imagem ilustrativa será inserida aqui.**

Outros pontos abordados:

- O modelo de cobrança é **"pay as you go"** (pague conforme o uso).
- Ao selecionar a imagem da MV, **toda a configuração e manutenção passam a ser minha responsabilidade**.
- É possível adicionar **discos extras (HDs)** além do que vem por padrão.
- É necessário configurar:
  - Redes virtuais e endereçamento IP.
  - Se a MV estará ou não exposta à internet.
- Na aba de gerenciamento:
  - Ativação de proteção.
  - Opções de conexão.
  - Desligamento automático.
  - Outros recursos avançados.

> **Insight:** Percebi que **criar uma VM não é uma tarefa simples** e mesmo quem prefere usar scripts ou código deve se familiarizar com a interface do portal.

---

## 🗄️ Criação de Banco de Dados SQL

Também realizei a criação de um banco de dados SQL no Azure:

1. Foi definido um **nome aleatório** para o banco de dados.
2. Foi necessário **criar um servidor**, pois ainda não existia.
3. Durante a criação do servidor:
   - Foi escolhida a autenticação via **Microsoft Entra**.
   - Foi solicitado o modelo de **redundância**, ligado ao **SLA (acordo de nível de serviço)**.
   - Notei que a opção de “Redundância de armazenamento de backup” **não estava visível na minha conta**, diferente do que a instrutora demonstrou.

**Imagens ilustrativas serão inseridas aqui.**

Com base nas configurações feitas, o Azure já apresentou uma **estimativa de custo mensal** do SQL Database.

---

## 💰 Cálculo de Custos

Foi comentado sobre o uso da **calculadora do Azure**, que permite prever os custos com base nos recursos selecionados.

---

## 🧠 Conclusão

- O nível de responsabilidade na nuvem está diretamente ligado ao modelo de serviço:
  - **IaaS** → maior responsabilidade do usuário.
  - **PaaS** → responsabilidades divididas.
  - **SaaS** → menor esforço do usuário.
- Quanto mais controle eu tenho, **mais trabalho técnico eu preciso realizar** — e vice-versa.

---

**Resumo:** Este laboratório foi essencial para compreender o ecossistema de serviços em nuvem do Azure e como configurar recursos com responsabilidade, segurança e foco em custo-benefício.
