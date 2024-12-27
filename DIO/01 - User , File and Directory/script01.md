# 📜 Script de Criação de Estrutura de Usuários, Diretórios e Permissões

## 🎯 Descrição do Projeto

Este projeto tem como objetivo automatizar o processo de criação e configuração de diretórios, grupos e usuários em um ambiente Linux, utilizando um script em Bash. Ele assegura uma estrutura organizada de permissões e restrições de acesso, de acordo com as diretrizes estabelecidas.

1. **Excluir diretórios, arquivos, grupos e usuários criados no desenvolvimento do curso:**

   - Garantir que todos os recursos criados previamente sejam removidos antes do novo provisionamento.

2. **Criar um Bash Script para o Provisionamento:**

   - Todo o processo de provisionamento deve ser automatizado em um arquivo `.sh`.

3. **Configuração do Dono dos Diretórios:**

   - O dono de todos os diretórios criados será o usuário `root`.

4. **Permissões para Diretório Público:**

   - Todos os usuários terão permissão total (leitura, escrita e execução) no diretório `/publico`.

5. **Permissões Específicas por Grupo:**

   - Os usuários de cada grupo terão permissão total dentro do diretório correspondente ao seu departamento:
     - **GRP_ADM:** Permissão total no diretório `/adm`.
     - **GRP_VEN:** Permissão total no diretório `/ven`.
     - **GRP_SEC:** Permissão total no diretório `/sec`.

6. **Restrições de Permissões:**

   - Os usuários não terão permissão de leitura, escrita e execução em diretórios de departamentos que eles não pertencem.

7. **Upload do Script para o GitHub:**
   - Após finalizar o script de automação, suba o arquivo para a sua conta no GitHub.

## Estrutura de Diretórios, Grupos e Usuários

| **DIRETÓRIOS**                 |                             |                 |                 |
| ------------------------------ | --------------------------- | --------------- | --------------- |
| `/publico`                     | `/adm`                      | `/ven`          | `/sec`          |
| ------------------------------ | --------------------------- | --------------- | --------------- |
| **GRUPOS**                     | **USUÁRIOS**                |                 |                 |
| GRP_ADM                        | carlos, maria, joao\_       |                 |                 |
| GRP_VEN                        | debora, sebastiana, roberto |                 |                 |
| GRP_SEC                        | josefina, amanda, rogerio   |                 |                 |

## 🛠️ Resolução
