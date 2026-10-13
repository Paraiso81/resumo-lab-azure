# Modelos de Serviço em Nuvem: IaaS, PaaS e SaaS na Azure

Na computação em nuvem, os serviços são divididos em três categorias principais. Elas definem o nível de responsabilidade e gerenciamento que você tem em comparação ao provedor da nuvem (Microsoft Azure).

## 1. IaaS (Infrastructure as a Service - Infraestrutura como Serviço)
É o modelo mais básico e flexível. Você aluga a infraestrutura de TI (servidores, máquinas virtuais, armazenamento e redes) sob demanda. É o mais próximo de ter um servidor físico, mas sem precisar comprar o hardware.
* **O que você gerencia:** Sistema operacional, aplicativos, dados e configurações de rede virtual.
* **O que a Azure gerencia:** Hardware físico, energia e resfriamento do Datacenter.
* **Exemplos na Azure:** *Azure Virtual Machines* (Máquinas Virtuais) e *Azure Storage*.

## 2. PaaS (Platform as a Service - Plataforma como Serviço)
Fornece um ambiente completo (plataforma) para criar, testar, hospedar e gerenciar aplicativos. É focado no desenvolvedor, removendo a necessidade de se preocupar com a infraestrutura subjacente, como atualizações de sistema operacional ou manutenção de servidores de banco de dados.
* **O que você gerencia:** O código do seu aplicativo e os dados da aplicação.
* **O que a Azure gerencia:** Sistema operacional, hardware, rede física e as ferramentas de banco de dados/runtime.
* **Exemplos na Azure:** *Azure App Service* e *Azure SQL Database*.

## 3. SaaS (Software as a Service - Software como Serviço)
É a entrega do aplicativo de software completo e pronto para uso através da internet. O provedor hospeda e gerencia tudo, e o usuário final apenas consome o serviço, geralmente através de um navegador web ou aplicativo.
* **O que você gerencia:** Apenas as permissões de acesso da sua conta e os dados que você insere no sistema.
* **O que a Azure/Microsoft gerencia:** Tudo (hardware, sistema operacional, atualizações do aplicativo e infraestrutura).
* **Exemplos:** *Microsoft 365* (Outlook, Teams, Excel online), *Dynamics 365*.
