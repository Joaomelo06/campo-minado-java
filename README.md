# 💣 Campo Minado em Java (Console)

Um jogo clássico de Campo Minado desenvolvido inteiramente em **Java** para ser jogado via terminal/console. Este projeto foi construído com foco em **Orientação a Objetos (POO)**, tratamento de exceções e **Testes Unitários**.

## 💻 Sobre o Projeto

O objetivo deste projeto foi recriar a lógica complexa do Campo Minado (abertura de campos em cadeia, verificação de vizinhança, sistema de vitória/derrota) aplicando conceitos sólidos de engenharia de software, garantindo que as regras de negócio estivessem totalmente isoladas da interface do usuário.

### ⚙️ Funcionalidades
- Geração dinâmica do tabuleiro.
- Abertura de campos vizinhos vazios de forma recursiva.
- Marcação de minas com bandeiras.
- Sistema de vitória e derrota (Explosão).
- Tratamento de erros para entradas inválidas.

---

## 🛠️ Tecnologias Utilizadas

- **Java (JDK 11+)**: Linguagem principal do projeto.
- **JUnit 5**: Framework utilizado para a criação de testes unitários.
- **Streams API & Lambdas**: Para manipulação eficiente e funcional das listas de vizinhos e campos.

---

## 🧪 Testes e Qualidade de Código

Um dos grandes focos deste projeto foi a garantia de qualidade através de **Testes Unitários**. 
Foram desenvolvidos testes rigorosos para cobrir os mais diversos cenários:
- Validação de distância entre vizinhos (Diagonais e Adjacentes).
- Comportamento de abertura de campos seguros e minados.
- Testes de exceções customizadas (ex: `ExplosaoException`).
- **Cobertura de Código**: Alta cobertura das regras de negócio validadas com ferramentas de coverage (como o EclEmma/JaCoCo).

---

## 🚀 Como Executar o Jogo

### Pré-requisitos
Você precisará ter o [Java JDK](https://www.oracle.com/br/java/technologies/javase-downloads.html) instalado na sua máquina.

### Passo a Passo

1. Clone este repositório:
   ```bash
   git clone [https://github.com/Joaomelo06/campo-minado-java.git](https://github.com/Joaomelo06/campo-minado-java.git)
