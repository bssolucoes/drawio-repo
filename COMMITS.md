# 📘 Guia de Mensagens de Commit

Este guia define como escrever mensagens de commit padronizadas, seguindo o padrão **Conventional Commits**.

---

## 📌 Estrutura básica
```
<tipo>(escopo opcional): descrição curta
```

### Exemplos
- `feat(bibliotecas): adiciona biblioteca de processadores`
- `fix(diagramas): corrige fluxo de vídeo`
- `docs: atualiza README com novos links`
- `chore: adiciona arquivo .gitignore`

---

## 📌 Tipos de commit

- **feat** → quando adiciona algo novo  
- **fix** → quando corrige um erro  
- **docs** → mudanças em documentação (README, CHANGELOG, etc.)  
- **chore** → manutenção (sem impacto direto para usuário final)  
- **refactor** → reorganização interna (sem alterar funcionalidade)  
- **style** → ajustes de formatação ou nomes (sem impacto funcional)  
- **test** → inclusão ou alteração de testes  

---

## 📌 Boas práticas

1. Mensagens **curtas e diretas** (máx. 72 caracteres).  
2. Usar **português** para consistência.  
3. Relacionar commits ao `CHANGELOG.md` quando relevante.  

---

## 📌 Exemplo de fluxo com changelog

### Commit
```
feat(bibliotecas): adiciona biblioteca de monitores
```

### Changelog
```markdown
## [1.0.1] - 2025-10-04
### Adicionado
- Nova biblioteca `monitores.xml` (commit: abc1234)
```

---

**Autor:** Biel Souza – BS Soluções Técnicas Audiovisuais  
