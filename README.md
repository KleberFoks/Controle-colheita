# Sistema de Controle de Perdas na Colheita - Python

Este projeto tem como objetivo o controle de perdas na colheita de cana-de-açúcar, com o desenvolvimento de um sistema em Python. A solução permite o cadastro das colheitas, cálculo de produtividade e perdas, e a exportação dos dados para arquivos `JSON` e `TXT`, além de integração com um banco de dados Oracle.

## 💡 Contexto

A perda de produtividade durante a colheita é uma das grandes dores no setor do agronegócio. Com este projeto, buscamos oferecer uma ferramenta prática para registrar, calcular e acompanhar os índices de perda por talhão, promovendo maior controle e eficiência.

## ✅ Funcionalidades

- Cadastro de colheitas (talhão, área, total colhido, perda).
- Cálculo da produtividade (t/ha) e da perda percentual.
- Salvamento dos dados em arquivos `JSON` e `TXT`.
- Exportação dos dados para um banco de dados Oracle.

## 🛠️ Tecnologias utilizadas

- **Python 3.x**
- **Biblioteca `oracledb`** para conexão com Oracle
- **JSON** e **TXT** para armazenamento local
- **Oracle Database** (remoto)

## ▶️ Como rodar o projeto

1. Clone o repositório para sua máquina local:

   ```bash
   git clone https://github.com/SEU_USUARIO/controle-colheita-python.git
Acesse a pasta do projeto:

bash
Copiar
Editar
cd controle-colheita-python
Instale a dependência:

bash
Copiar
Editar
pip install oracledb
Execute o programa:

bash
Copiar
Editar
python controle-colheita-python.py
📁 Estrutura dos arquivos
controle-colheita-python.py → Script principal do sistema

colheita.json → Dados salvos em formato JSON

colheita.txt → Dados salvos em formato texto

README.md → Explicação do projeto

📌 Observações
Os dados de acesso ao banco Oracle (usuário, senha e DSN) devem ser configurados corretamente no código.

O sistema trata entradas inválidas e impede valores negativos.

👨‍💻 Autor
Kleber Foks
RM: 562225
Projeto desenvolvido como parte da disciplina de Python na FIAP - 2º Mês.

“O campo não espera — controle, registre e produza com inteligência.”
