# terraform_ecs_fargate_example

## Requisitos
```
AWS CLI with user configured by default
TERRAFORM (v0.11.2)
```

## Comandos Terraform
```
terraform init

terraform plan

terraform apply

*Esses comandos devem ser executados na raiz do projeto
```

## Comando para obter dns do alb
```
terraform output alb_dns_name
```

## Informações adicionais
```
Esse projeto utiliza um repositório do github de uma api simples em java caso queira utilizar outro projeto
alterar as referências nos arquivos do modulo de code_pipeline

Gerar um token do github e exportar como variavel de ambiente no seu sistema operacional
[GITHUB TOKEN](https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/)
```