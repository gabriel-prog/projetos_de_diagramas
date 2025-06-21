# Sistema Hospitalar – Diagrama ER (Entidade-Relacionamento)

Este projeto contém o **diagrama Entidade-Relacionamento (ERD)** do **Sistema Hospitalar**.

---

## 📂 Arquivos nesta pasta:

- sistema_hospitalar.dot → Código fonte do diagrama lingagem DOT (feito com Graphviz)
- sistema_hospitalar.png → Imagem gerada do diagrama

---

## 🛠️ Como visualizar o diagrama:

1. **Se quiser abrir o código DOT (.dot):
   - Use uma IDE ou editor de texto como VS Code ou Notepad++.
   - Ou abra com um editor online de Graphviz:  
   👉 [https://dreampuf.github.io/GraphvizOnline/](https://dreampuf.github.io/GraphvizOnline/)

2. Se quiser gerar a imagem (PNG) a partir do `.dot`:
   - Tenha o "Graphviz" instalado no seu computador.
   - Rode o comando:

```bash
dot -Tpng sistema_hospitalar.dot -o sistema_hospitalar.png
