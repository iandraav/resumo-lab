# 📖 Resumo do Laboratório: [Inserir Nome do Lab, ex: Criando uma Máquina Virtual no Azure]

Este repositório contém o resumo do que aprendi durante o laboratório prático do bootcamp **Microsoft 50 Anos - Computação em Nuvem com Azure** da DIO.

---

### 🎯 Objetivo do Laboratório
O objetivo deste laboratório foi [Descreva em uma ou duas frases o propósito do lab. Ex: aprender a provisionar, configurar e acessar uma Máquina Virtual (VM) na plataforma Microsoft Azure, compreendendo os passos fundamentais para a criação de recursos de IaaS (Infraestrutura como Serviço).]

---

### 🔧 Ferramentas e Tecnologias Utilizadas
* **Microsoft Azure:** Plataforma de nuvem utilizada para criar e gerenciar os recursos.
* **Azure Portal:** Interface web para gerenciamento dos serviços do Azure.
* **Máquinas Virtuais (VMs):** Serviço de IaaS para provisionamento de servidores virtuais.
* **Rede Virtual (VNet) e Grupo de Segurança de Rede (NSG):** Para configuração de rede e segurança da VM.
* **[Adicionar outra tecnologia, se aplicável, ex: Banco de Dados SQL do Azure]**

---

### 🧠 Passo a Passo e Principais Aprendizados

Durante a execução do laboratório, segui os seguintes passos e obtive os aprendizados correspondentes:

#### 1. Criação do Recurso no Portal Azure
* **O que fiz:** Acessei o portal do Azure, utilizei a opção "Criar um recurso" e selecionei "Máquina Virtual". Preenchi os detalhes necessários como nome da VM, região, imagem (sistema operacional), tamanho e credenciais de administrador.
* **Principal aprendizado:** Entendi a importância de cada parâmetro de configuração. A escolha da **região** impacta a latência para os usuários, e o **tamanho** da VM define a performance e o custo. Aprendi a diferença entre autenticação por senha e por chave SSH, sendo a última mais segura.

#### 2. Configuração de Rede e Segurança
* **O que fiz:** Configurei a Rede Virtual (VNet) e o Grupo de Segurança de Rede (NSG). No NSG, adicionei uma regra de entrada para permitir o tráfego na porta necessária para o acesso remoto (Porta 3389 para RDP/Windows ou Porta 22 para SSH/Linux).
* **Principal aprendizado:** A segurança na nuvem é fundamental e proativa. Compreendi que, por padrão, o acesso externo é bloqueado e precisa ser liberado explicitamente através de regras de firewall no NSG. Isso é um pilar do modelo de "confiança zero" (Zero Trust).

#### 3. Conexão e Validação da Máquina Virtual
* **O que fiz:** Após o provisionamento da VM, copiei o endereço de IP público e utilizei um cliente de acesso remoto (Área de Trabalho Remota para Windows / Terminal para Linux) para me conectar à máquina.
* **Principal aprendiado:** Consegui validar na prática o conceito de IaaS. A partir do momento da conexão, eu tinha um servidor funcional na nuvem, pronto para que eu pudesse instalar software e executar aplicações, assim como faria em uma máquina local, mas com toda a flexibilidade da nuvem.

---

### ✅ Conclusão
Este laboratório foi essencial para solidificar os conceitos teóricos de computação em nuvem. A experiência prática de criar e gerenciar um recurso real no Azure me deu confiança para explorar outros serviços e entender como a nuvem pode resolver problemas de negócio, oferecendo escalabilidade, flexibilidade e uma gestão de custos mais eficiente em comparação com o modelo on-premise.

---

**Desenvolvido por:**
* **[Seu Nome Completo]**
* **LinkedIn:** [Link para o seu perfil no LinkedIn]
* **Perfil DIO:** [Link para o seu perfil na DIO]
