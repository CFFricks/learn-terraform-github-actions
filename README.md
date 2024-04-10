# Automate Terraform with GitHub Actions

This repo is a companion repo to the [Automate Terraform with GitHub Actions tutorial](https://developer.hashicorp.com/terraform/tutorials/automation/github-actions).


# Ponderada

## Resumo

Este projeto feito para a ponderada, demonstra como automatizar o provisionamento de infraestrutura utilizando o Terraform, integrado com GitHub Actions, dentro do contexto do Terraform Cloud. O objetivo é criar e configurar automaticamente um servidor web acessível publicamente, aplicando conceitos de infraestrutura como código (IaC) em um workflow de CI/CD. A automação por meio dessas ferramentas não só reforça as melhores práticas de configuração, como também promove uma colaboração eficaz e automatiza todo o fluxo de trabalho do Terraform.

## Tecnologias Utilizadas

- **Terraform**:
Terraform é uma ferramenta que permite aos usuários definir e provisionar infraestrutura através de um código de configuração declarativo. O Terraform gera um plano de execução que descreve o que ele fará para alcançar o estado desejado, e depois executa os planos para construir a infraestrutura. Como uma ferramenta de IaC, o Terraform permite a versão, reutilização e compartilhamento de infraestruturas, tornando-o ideal para ambientes de produção complexos e escaláveis.
- **GitHub Actions**:
GitHub Actions é uma funcionalidade de CI/CD que permite aos desenvolvedores automatizar seus pipelines de software diretamente no GitHub. Com Actions, é possível compilar, testar e implantar código, tudo a partir de repositórios GitHub. Este serviço suporta uma variedade de operações, possibilitando a execução de workflows em eventos específicos, como push, pull requests ou agendamentos.


## Conceitos Aprendidos

### 1. Integração do Terraform com o GitHub Actions

GitHub Actions é uma ferramenta de automação que permite a criação de workflows personalizados para automação de builds, testes e deployments diretamente de repositórios GitHub. Integrar o Terraform com o GitHub Actions facilita a implementação contínua de infraestrutura como código, permitindo atualizações eficientes e minimizando erros manuais.

### 2. Uso do Terraform Cloud para Gerenciamento de Estado e Colaboração

Terraform Cloud proporciona um ambiente colaborativo para o gerenciamento do estado do Terraform e controle de acesso a credenciais. Este recurso é crucial para equipes que trabalham em infraestruturas complexas, pois permite gerenciamento e atualizações seguras e convenientes.

### 3. Workflow de CI/CD Customizável com Terraform Cloud e GitHub Actions

Aprendemos a configurar um workflow de CI/CD que utiliza a API do Terraform Cloud para executar operações de Terraform de forma programática. Este workflow inclui a criação de planos especulativos para cada commit em uma branch de pull request e a aplicação de configurações na branch principal.

## Imagens

![WhatsApp Image 2024-04-10 at 12 07 28_d62474a9](https://github.com/CFFricks/learn-terraform-github-actions/assets/99102201/93126298-4636-45d1-a234-04cbe3d5d394)
![WhatsApp Image 2024-04-10 at 12 07 52_73c9970b](https://github.com/CFFricks/learn-terraform-github-actions/assets/99102201/9e44448f-9f4d-44e8-8009-da4df1fd4b02)
