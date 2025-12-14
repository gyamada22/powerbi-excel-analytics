# 🧮 Módulo 2 - Fórmulas, Lógica e Busca Avançada

## ✅ Status: CONCLUÍDO (13/12/2025)
- **Foco:** Lógica, análise e busca de dados
- **Nível:** Intermediário → Avançado
- **Progresso:** 100%

## 📚 Conteúdo Aprendido
| Bloco | Tema | Principais Funções | Status |
|------|------|-------------------|--------|
| 1 | Lógica Condicional | SE, E, OU, DATA | ✅ |
| 2 | Contagem Condicional | CONT.SES | ✅ |
| 3 | Agregações Condicionais | SOMASES, MÉDIASES | ✅ |
| 4 | Buscas Clássicas | PROCV, PROCH | ✅ |
| 5 | Buscas Modernas | PROCX | ✅ |
| 6 | Busca Avançada | ÍNDICE, CORRESP | ✅ |
| 7 | Referências Dinâmicas | DESLOC, INDIRETO | ✅ |
| 8 | Funções Avançadas | SOMARPRODUTO | ✅ |

## 💡 Destaques do Módulo

### 🔁 **Funções Lógicas**
- Criação de regras de negócio com `SE()`
- Combinação de múltiplas condições com `E()` e `OU()`
- Comparação correta de datas usando `DATA()`
- Uso de curingas:
  - `*Analista*` → contém texto (equivalente ao `%` do SQL)

**Exemplo prático:**
```excel
=SE(OU(B2<DATA(2010;12;31);D2<>"ES";C2="Terceiro");"Sim";"Não")
