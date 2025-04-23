## Resumo da Aula de Laboratório - Microsoft Azure
Este projeto foi desenvolvido com base nos conceitos aprendidos durante uma aula de laboratório sobre o Microsoft Azure, uma plataforma de computação em nuvem que oferece diversos serviços para o desenvolvimento, implantação e gerenciamento de aplicativos. A aula abordou os conceitos fundamentais do Azure e as formas de interação com seus recursos principais.

Durante a aula, exploramos as ferramentas de acesso ao Azure, começando pelo Azure Portal, uma interface gráfica intuitiva para criação e gestão de recursos como máquinas virtuais, redes e bancos de dados. Também utilizamos o Azure CLI e o Azure PowerShell para automação de tarefas e configurações avançadas através de linha de comando.

Focamos na criação e configuração de Máquinas Virtuais usando o Azure Virtual Machines, gerenciamento de dados com o Azure Storage e hospedagem de aplicativos web utilizando o Azure App Services. A aula também abordou a configuração de Redes Virtuais para garantir a segurança e a conectividade entre os recursos na nuvem.

Este projeto é uma base inicial para explorar as capacidades do Microsoft Azure, com o objetivo de entender como utilizar esses recursos para criar soluções escaláveis e seguras na nuvem.

# Desafio: Criação e Configuração de uma Máquina Virtual no Microsoft Azure

## 💡 Objetivo

Este repositório foi criado como parte de um desafio prático proposto na plataforma DIO. O objetivo principal é praticar o processo de criação e configuração de uma máquina virtual (VM) na plataforma Microsoft Azure, além de documentar toda a experiência com resumos, anotações e dicas úteis. Este material serve como apoio para estudos e futuras implementações na nuvem.

## 🎯 Objetivos de Aprendizagem

- Aplicar os conceitos aprendidos em um ambiente prático real;
- Documentar processos técnicos de forma clara, objetiva e estruturada;
- Utilizar o GitHub como ferramenta de versionamento e compartilhamento de conhecimento técnico.

## 🛠️ Etapas Realizadas

### 1. Acesso ao Azure
A primeira etapa foi acessar o [Azure Portal](https://portal.azure.com/) e se familiarizar com sua interface. Utilizamos a conta educacional para acessar os recursos gratuitos disponíveis na plataforma.

### 2. Criação da Máquina Virtual
- Navegação até **"Máquinas Virtuais"** e seleção da opção **"Criar"**.
- Definição de parâmetros como:
  - Nome da VM
  - Região
  - Imagem do SO (Windows)
  - Tipo e tamanho da máquina
  - Nome de usuário e senha para acesso remoto
- Configuração das regras de rede e firewall (liberação da porta 3389 para RDP).

### 3. Configurações de Rede e Armazenamento
- Criação e associação de uma **Rede Virtual (VNet)**;
- Definição de regras básicas de segurança;
- Uso do **Disco Gerenciado** para armazenamento.

### 4. Validação e Acesso
- Após a criação da VM, realizamos o teste de acesso via **Área de Trabalho Remota (RDP)**;
- Validação da conectividade e operação correta do sistema.

## 🧾 Documentação Incluída

- `README.md`: este arquivo, contendo um resumo completo da atividade;
- `/images`: pasta com capturas de tela do processo (opcional, se utilizadas);
- Anotações e dicas sobre os serviços utilizados no Azure.

## 📚 Recursos Úteis

- [Documentação Oficial: Criar uma VM no Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal)
- [GitHub Markdown Guide](https://www.markdownguide.org/basic-syntax/)
- [Formação GitHub Certification - GitBook](https://dio.me)

## ✅ Conclusão

Este laboratório proporcionou uma introdução prática ao uso da nuvem com o Microsoft Azure. A criação da máquina virtual e o gerenciamento de seus recursos demonstraram como é possível iniciar soluções escaláveis e profissionais com poucos passos. A documentação no GitHub reforça o aprendizado, serve como material de consulta futura e como portfólio técnico.

---

📌 **Dica**: Explore também o uso do Azure CLI e do PowerShell para automatizar processos e criar recursos via linha de comando.


