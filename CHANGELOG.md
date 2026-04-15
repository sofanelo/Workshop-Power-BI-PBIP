# Changelog

## 2026-04-14 — Criação do Dashboard de Vendas e Produtos

### Página 1 — Visuals adicionados

#### 4 Cards (KPIs)
| Visual | Medida | Posição |
|--------|--------|---------|
| Receita Bruta | `_Medidas[Receita Bruta]` | x:20 y:20 |
| Total Vendas | `_Medidas[Total Vendas]` | x:335 y:20 |
| Margem Bruta % | `_Medidas[Margem Bruta %]` | x:650 y:20 |
| Total Produtos Vendidos | `_Medidas[Total Produtos Vendidos]` | x:965 y:20 |

#### 4 Gráficos (layout 2x2)
| Visual | Tipo | Categoria | Valor | Posição |
|--------|------|-----------|-------|---------|
| Receita por Categoria | Coluna agrupada | `dProdutos[Categoria]` | Receita Bruta | x:20 y:160 |
| Receita por Mês | Linha | `dCalendario[MesAbreviado]` | Receita Bruta | x:650 y:160 |
| Receita por Forma de Pagamento | Rosca (donut) | `fVendas[FormaPagamento]` | Receita Bruta | x:20 y:440 |
| Receita por Produto | Barra | `dProdutos[NomeProduto]` | Receita Bruta | x:650 y:440 |

### Validação
- Relatório validado com **0 erros** (23 arquivos verificados)
