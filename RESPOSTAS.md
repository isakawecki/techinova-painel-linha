# Respostas do LAB 01

Nome: Isabella Macedo Kawecki
Dupla (M2 em diante): Ricardo Ongari Rodrigues

---

## M2 - Quem quebrou o painel

**Hash curto do commit que introduziu o erro:** 01ef93b 
**Autor:** Tarcisio Melo  

**Data:**  2026-06-15

**Linha alterada (antes e depois):**

```
antes: return (leitura - 32) * 5 / 9;
depois: return leitura * 9 / 5 + 32;
```

---

## M3 - O segredo vazado

**O que voce esperava ver no `git status` e o que apareceu:**

    O que eu esperava:
     Eu esperava ver o arquivo .gitignore criado.

    O que apareceu:
    Untracked files:
      (use "git add <file>..." to include in what will be committed)
        .gitignore


**Depois do push, alguem que clonar o repositorio ainda consegue ler a chave?
Responda em duas linhas, explicando o motivo:**
    Sim, pois o arquivo de credenciais já estava publicado, e o .gitignore não deleta arquivos já publicados. Com o "git rm --cached config/credenciais.env" ele para de rastrar o arquivo.
---

## M4 - Colisao

**O que significavam os marcadores que apareceram dentro do arquivo:**

- `<<<<<<<` :
- `=======` :
- `>>>>>>>` :

**Qual pedaco veio de quem, e qual titulo voces decidiram manter:**

---

## Casa - Incidente na linha 3

**Hash do commit que quebrou o painel:**

**Hash do commit de revert:**

**Por que `git revert` e nao `git reset` neste caso:**
