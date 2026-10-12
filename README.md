# algoritmos-e-estrutura-de-dados-
\# Sistema de Geração de QR Code em Lote



Projeto desenvolvido para a disciplina de \*\*Algoritmos e Estruturas de Dados I\*\* (Engenharia de Software).



\## Descrição do Projeto

O sistema demonstra a aplicação prática de duas estruturas de dados lineares fundamentais através da manipulação de apontadores/referências na linguagem Python:

1\. \*\*Fila Encadeada (FIFO):\*\* Gere os pedidos de criação de QR Codes na ordem de chegada.

2\. \*\*Pilha Encadeada (LIFO):\*\* Mantém o histórico de gerações recentes, permitindo reverter/desfazer (\*Undo\*) a última operação criada e eliminar o respetivo ficheiro.



\## Estrutura do Projeto

\- `src/no.py`: Classe fundamental `Node` com apontador `proximo`.

\- `src/fila.py`: TAD Fila com operações $O(1)$ (`enfileirar`, `desenfileirar`, `frente`).

\- `src/pilha.py`: TAD Pilha com operações $O(1)$ (`push`, `pop`, `topo`).

\- `src/gerenciador.py`: Orquestração entre as estruturas de dados e a geração de imagem (`qrcode`).

\- `tests/`: Bateria de testes unitários com o módulo `unittest`.

\- `main.py`: Interface de linha de comando (CLI) interativa.



\## Requisitos e Instalação

\- Python 3.10+

\- Dependências:

&#x20; ```bash

&#x20; py -m pip install qrcode pillow

