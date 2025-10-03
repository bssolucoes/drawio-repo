# 📦 Guia de Versionamento

Este repositório segue o padrão **Versionamento Semântico (SemVer)**.

---

## 📌 Formato
```
MAJOR.MINOR.PATCH
```

### Exemplos
- `1.0.0`
- `1.1.0`
- `1.1.1`

---

## 📌 Regras

- **MAJOR (X.0.0)** → Mudanças grandes ou incompatíveis  
  Ex.: reorganização completa das bibliotecas, alteração estrutural

- **MINOR (0.X.0)** → Adição de novas funcionalidades sem quebrar compatibilidade  
  Ex.: adicionar uma nova biblioteca XML ou diagrama

- **PATCH (0.0.X)** → Correções pequenas ou ajustes  
  Ex.: corrigir nome de item em uma biblioteca, ajustar detalhes em um diagrama

---

## 📌 Fluxo sugerido

1. Atualize o arquivo `CHANGELOG.md` com a nova versão.
2. Faça commit:
   ```bash
   docs(changelog): registra versão 1.0.1
   ```
   > Descrição: Inclui ajustes no diagrama `teste-draw-io.drawio`
3. Atualize também este `VERSIONING.md` com a nova versão.
4. Crie uma **tag de versão**:
   ```bash
   git tag -a v1.0.1 -m "Versão 1.0.1 - atualiza teste-draw-io.drawio"
   git push origin v1.0.1
   ```
5. No GitHub, a tag aparecerá em **Releases**.

---

## 📌 Exemplo prático

- Criou repo → `1.0.0`  
- Atualizou `teste-draw-io.drawio` → `1.0.1`  
- Adicionou `monitores.xml` → `1.1.0`  
- Corrigiu erro em `processadores.xml` → `1.1.1`  
- Reorganizou toda a estrutura → `2.0.0`  

---

**Autor:** Biel Souza – BS Soluções Técnicas Audiovisuais  
