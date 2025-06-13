# desafio-azure-vm-dio
Repositório criado como parte do laboratório prático para consolidar os conhecimentos adquiridos sobre máquinas virtuais (VMs) no Microsoft Azure.

# Desafio DIO: Máquinas Virtuais no Azure

## 🧠 Objetivo
Demonstrar a criação e configuração de uma máquina virtual no Azure como parte do desafio da DIO.

## 🛠️ Passos Realizados
1. Criação do grupo de recursos
2. Definição da imagem e tamanho da VM
3. Configuração da conta de administrador
4. Abertura de portas no NSG (RDP, HTTP, etc)

- ## 💡 Aprendizados
- **Gerenciamento de recursos no Azure:** No início, eu não tinha dimensão da importância de organizar corretamente os grupos de recursos. Com a criação da minha primeira máquina virtual (VM), compreendi como essa organização impacta diretamente na clareza, escalabilidade e facilidade de administração dos recursos ao longo do tempo. Uma estrutura bem definida evita confusões e facilita futuras implementações.
- **Configuração de rede e portas:** Configuração de rede e portas: Aprendi que abrir apenas as portas estritamente necessárias é essencial para garantir a segurança da aplicação. A criação e o ajuste das regras no Network Security Group (NSG) me mostraram como controlar o tráfego de entrada e saída de forma eficaz, reduzindo significativamente o risco de vulnerabilidades.
- Gerenciamento de recursos no Azure: 

## 🚧 Desafios Superados
- **Erro ao conectar via RDP:** No início, eu não conseguia acessar minha VM pelo Remote Desktop. Depois de revisar a configuração do NSG, percebi que a porta 3389 não estava devidamente aberta. Ajustei as regras de entrada e finalmente consegui estabelecer a conexão!

## 🖼️ Capturas de Tela
As imagens estão na pasta `/images`.

## 📎 Recursos
- Documentação oficial: [Criar VM no Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal)
