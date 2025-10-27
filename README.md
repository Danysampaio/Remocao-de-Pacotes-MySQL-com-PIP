# Remocao-de-Pacotes-MySQL-com-PIP

## Contexto
Neste cenário, como desenvolvedores Python estamos trabalhando em um projeto de **folha de pagamento** para uma multinacional.  
Durante o processo, foi solicitado pelo arquiteto de soluções que fossem **removidas instruções MySQL legadas**, utilizando o **PIP** — o gerenciador de pacotes do Python.

---

## Objetivo
Implementar a instrução em **PIP** responsável por **remover o pacote `mysqlclient`**, localizado na biblioteca padrão `lib/python`.

---

## Instrução Utilizada

```bash
pip uninstall mysqlclient
