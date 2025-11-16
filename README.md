# Projeto Interpretador Lox (Compiladores)
Este repositório contém o código-fonte de um interpretador para a linguagem Lox, desenvolvido como parte da disciplina de Compiladores.

O projeto foi reestruturado para seguir as boas práticas de projetos Java modernos, utilizando **Apache Maven** para gerenciamento de build e dependências.

## 👥 Integrantes
- Arthur Sampaio Pereira - arthurswntg2000
- Keven Gustavo Dos Santos Gomes - Keven.Gustavo.DSG

## 📋 Pré-requisitos

Para compilar e executar este projeto, você precisará ter os seguintes softwares instalados em sua máquina:

* **Java (JDK 17** ou superior)
* **Apache Maven**

# ⚙️ Compilando e Empacotando (Build)

Este projeto é gerenciado pelo Maven, o que simplifica o processo de build.

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/KevenGustavo/LOX.git
    cd LOX
    ```

2.  **Execute o build do Maven:**
    Na raiz do projeto (onde o arquivo `pom.xml` está localizado), execute:
    ```bash
    mvn clean install
    ```
    * `clean`: Remove builds anteriores (limpa a pasta `target/`).
    * `install`: Compila o código, executa testes e empacota o projeto em um arquivo `.jar` executável dentro da pasta `target/`.

---

## ▶️ Executando o Interpretador

Após o build bem-sucedido, você pode executar o interpretador de duas maneiras principais:

### 1. Modo Interativo (REPL)

Inicia um console "Read-Eval-Print-Loop" para testar comandos Lox linha por linha.

**Opção A: Usando o Plugin do Maven**
```bash
mvn exec:java
```

**Opção B: Usando o .jar empacotado**
```bash
java -jar target/lox.jar
```
