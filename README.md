# TaskFlow
**Projeto Final - Programação em Python**  
**Equipe:** Matheus Bertorini + Matheus Alves
**Data:** Novembro 2025

---

## Descrição do Projeto
Sistema de gerenciamento de tarefas com:
- Criação, edição, conclusão e exclusão de tarefas
- Persistência em arquivos JSON (`tarefas.json` e `tarefas_arquivadas.json`)
- Arquivamento automático de tarefas concluídas
- Validação de entrada com `try/except`
- Relatórios completos (ativas, arquivadas, prioridades)

---

## Arquivos do Projeto
| Arquivo | Descrição |
|--------|----------|
| `main.py` | Código principal com menu interativo |
| `tarefas.json` | Tarefas ativas (com prioridade em texto: urgente, alta, média, baixa) |
| `tarefas_arquivadas.json` | Tarefas concluídas e arquivadas |
| `README.md` | Este documento |

---

## Como Executar
1. Ter **Python 3** instalado
2. Abrir o terminal na pasta do projeto
3. Executar:
   ```bash
   python main.py
