# 🚀 Desafio DIO: Primeira Stack com AWS CloudFormation

Este repositório documenta minha experiência prática ao implementar uma stack na AWS utilizando o serviço CloudFormation, como parte do laboratório da DIO.

---

## 🎯 Objetivo do Desafio

- Aplicar os conceitos aprendidos sobre infraestrutura como código (IaC)
- Criar recursos reais na AWS usando um template YAML
- Documentar o processo técnico de forma clara e organizada
- Utilizar o GitHub como ferramenta de compartilhamento técnico

---

## 📁 Estrutura do Repositório


- `README.md`: documentação completa do projeto
- `template.yaml`: arquivo que define os recursos da stack
- `images/`: pasta com capturas de tela da execução e da stack criada

---

## 🛠️ Recursos Criados com CloudFormation

A stack foi criada com sucesso a partir do arquivo `template.yaml`, que define os seguintes recursos:

### 🔹 Bucket S3

- Nome: `meu-bucket-dio-cloudformation`
- Finalidade: armazenamento de arquivos e dados estáticos

### 🔹 Função Lambda

- Nome: `minha-funcao-dio`
- Runtime: Python 3.9
- Código inline simples que retorna uma mensagem de sucesso

### 🔹 Role IAM

- Nome: `minha-role-lambda-dio`
- Permissões: política gerenciada `AWSLambdaBasicExecutionRole`
- Finalidade: permitir que a função Lambda seja executada com segurança

---

## 📸 Capturas de Tela

As imagens da execução da stack e da visualização no console da AWS estão disponíveis na pasta `/images`.

- `stack-criada.png`: visualização da stack no console
- `criacao-em-progresso.png`: detalhes da execução
- `execucao-sucesso.png`: confirmação de que os recursos foram criados corretamente

---

## 📚 Aprendizados

Durante este desafio, aprendi:

- Como estruturar um template YAML para CloudFormation
- A diferença entre recursos, parâmetros e permissões
- Como validar e subir uma stack via console da AWS
- A importância da documentação clara para projetos técnicos

---

## ✅ Conclusão

Desafio concluído com sucesso! A prática reforçou minha compreensão sobre infraestrutura como código e me preparou para projetos mais avançados com AWS.

---

## 🔗 Link do Projeto

Este repositório está disponível publicamente em:  
[https://github.com/carolinegrau/desafioDIO-cloudformation](https://github.com/carolinegrau/desafioDIO-cloudformation)

