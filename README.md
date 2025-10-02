# 🧪 Teste de Caixa Branca em Python

Este repositório contém um exemplo prático de **teste de caixa branca** utilizando a linguagem **Python**, desenvolvido e executado no ambiente [Replit](https://replit.com/languages/python3).  

O objetivo foi validar a função `maximo(a, b)` através de casos de teste que cobrem todas as instruções possíveis do código.  

---

## 📌 Objetivo da Atividade
- Criar a função `maximo()` em Python que compara dois números inteiros.  
- Aplicar **testes de caixa branca** cobrindo os cenários:
  1. Quando `a < b`  
  2. Quando `a > b`  
  3. Quando `a == b`  
- Validar os resultados esperados e documentar em relatório.

---

## 📝 Código Principal (`main.py`)

```python
def maximo(a, b):
    if a > b:
        return print("O número {} é o maior".format(a))
    else:
        return print("O número {} é o maior".format(b))

✅ Resultados Esperados
# -------------------------
# Casos de teste
# -------------------------

# Caso 1: a < b
print("Caso 1: a < b")
maximo(10, 20)  # Esperado: O número 20 é o maior

# Caso 2: a > b
print("\nCaso 2: a > b")
maximo(30, 15)  # Esperado: O número 30 é o maior

# Caso 3: a = b
print("\nCaso 3: a = b")
maximo(25, 25)  # Esperado: O número 25 é o maior

| Caso | Entradas (a, b) | Saída Esperada        |
| ---- | --------------- | --------------------- |
| 1    | 10, 20          | O número 20 é o maior |
| 2    | 30, 15          | O número 30 é o maior |
| 3    | 25, 25          | O número 25 é o maior |

🔧 Como Executar

1 - Clone este repositório:

git clone https://github.com/SEU-USUARIO/Teste_Caixa_Branca.git


2 - Entre na pasta do projeto:

cd Teste_Caixa_Branca


3 - Execute o código com Python:

python main.py

📚 Aprendizado

Aplicação prática de teste de caixa branca.

Uso da técnica de cobertura de código.

Execução no Replit para testes rápidos e validação.

✍️ Autor: Rerisson Henrique Rodrigues da Silva
📅 Data: Outubro/2025
