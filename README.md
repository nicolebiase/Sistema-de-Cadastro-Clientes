# 📋 Sistema de Cadastro de Clientes

## 🎯 Objetivo
Este projeto tem como objetivo aplicar conceitos básicos de **lógica de programação** e **banco de dados** para criar um sistema simples de cadastro de clientes.

## 🛠️ Tecnologias utilizadas
- Linguagem: Python
- Banco de Dados: SQLite
- Versionamento: Git/GitHub

## 🚀 Funcionalidades
- Adicionar novos clientes
- Consultar clientes cadastrados
- Atualizar informações
- Excluir cadastros

## 📌 Fonte de inspiração
Baseado em estudos da faculdade e exemplos abertos disponíveis no GitHub.

# Sistema simples de cadastro de clientes

clientes = []

def adicionar_cliente(nome, email):
    clientes.append({"nome": nome, "email": email})
    print(f"{nome} adicionado com sucesso!")

def listar_clientes():
    for c in clientes:
        print(f"Nome: {c['nome']}, Email: {c['email']}")

# Testando
adicionar_cliente("Nicole", "nicole@email.com")
listar_clientes()
