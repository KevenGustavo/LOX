# Projeto Interpretador Lox (Compiladores)
Este repositório contém o código-fonte de um interpretador para a linguagem Lox, desenvolvido como parte da disciplina de Compiladores.

O projeto foi reestruturado para seguir as boas práticas de projetos Java modernos, utilizando **Apache Maven** para gerenciamento de build e dependências.

## Integrantes
- Arthur Sampaio Pereira - arthurswntg2000
- Keven Gustavo Dos Santos Gomes - Keven.Gustavo.DSG

## 📋 Pré-requisitos

Para compilar e executar este projeto, você precisará ter os seguintes softwares instalados em sua máquina:

* **Java (JDK 17** ou superior)
* **Apache Maven**

## ⚙️ Como Compilar

Este projeto é gerenciado pelo Maven, portanto, não é necessário compilar arquivos manualmente ou depender de configurações de IDE.

1.  Clone este repositório:
    ```bash
    git clone [URL-DO-SEU-REPOSITORIO]
    cd [NOME-DO-SEU-REPOSITORIO]
    ```

2.  Execute o comando de build do Maven na raiz do projeto (onde o arquivo `pom.xml` está localizado):
    ```bash
    mvn clean install
    ```
* `clean`: Remove builds anteriores (limpa a pasta `target/`).
* `install`: Compila o código-fonte, executa testes (se houver) e empacota o projeto em um arquivo `.jar`.

Se o build for bem-sucedido, você verá uma pasta `target/` criada na raiz do projeto.

## ▶️ Como Executar

Após a compilação bem-sucedida, você pode executar o interpretador de duas maneiras:

### 1. Usando o Plugin do Maven (Recomendado)

Este comando executa a classe principal (`interpretador.Lox`) definida no `pom.xml`:

```bash
mvn exec:java
```