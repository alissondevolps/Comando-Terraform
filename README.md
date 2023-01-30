# Comandos-Terraform
- terraform init ---> Inicia o processo instalando o provider e gera um arquivo oculto com as infomações
- terraform plan ---> Mostra que será adicionado a infomações de um aquivo 'ex: local.tf'
- terraform apply ---> mostra o que será executado no arquivo, caso confirme com 'yes' as ações serão feitas
- terraform apply --auto-approve ---> Executa o arquivo sem passar o yes
- terraform destroy ---> Vai destruir tudo que estive criado no provider



# OBSERVAÇÃO
- {}terraform.tfstate ---> É um arquivo criado no momento que é feito um terraform apply. Nesse arquivo fica as infomações atuais do provider. Quando é feito qualquer alteração é criado outro arquivo com nome 'terraform.tfstate.backup que ficam salvo as alterações anteriores.

# Links documentações

- https://www.terraform.io/
- https://registry.terraform.io/
- https://registry.terraform.io/browse/providers
- https://registry.terraform.io/browse/modules
- https://registry.terraform.io/providers/hashicorp/aws/latest/docs ---> provider AWS
- https://developer.hashicorp.com/terraform/downloads?product_intent=terraform
- https://developer.hashicorp.com/terraform/language/values/variables
- https://docs.aws.amazon.com/eks/latest/userguide/install-aws-iam-authenticator.html ---> Instalar para ter acesso ao cluster criado na AWS
