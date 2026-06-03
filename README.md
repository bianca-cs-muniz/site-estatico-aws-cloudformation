# Site Estático com AWS CloudFormation

Infraestrutura automatizada na AWS para hospedar um site estático em bucket S3, usando CloudFormation como IaC.

---

## Arquitetura

- Amazon S3 — armazenamento e entrega dos arquivos do site
- AWS CloudFormation — provisionamento e configuração da infraestrutura

---

## O que foi implementado

- Criação automática do bucket S3
- Configuração de hospedagem estática
- Policy de acesso público
- Output com a URL do site gerada pela stack

---

## Tecnologias

- AWS CloudFormation
- Amazon S3
- HTML / CSS / JavaScript

---

## Como executar

1. Acesse o AWS CloudFormation e crie uma nova stack
2. Faça upload do arquivo `infraestrutura.yaml`
3. Aguarde a criação dos recursos
4. A URL do site estará disponível na aba **Outputs**
5. Faça upload do `index.html` diretamente no bucket S3 criado

---

## Aprendizados

Esse projeto foi uma boa oportunidade pra entender na prática como funciona IaC — desde a definição dos recursos no YAML até o gerenciamento de permissões e políticas no S3. A parte de configurar o acesso público corretamente foi onde ficou mais claro como as policies funcionam.