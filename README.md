# Project 1: Search – Pacman (CS 188 Spring 2025)
  https://inst.eecs.berkeley.edu/~cs188/sp25/projects/proj1/

## Visão Geral
Este projeto implementa algoritmos de **busca clássica em Inteligência Artificial** aplicados ao jogo Pacman.  
O agente é capaz de encontrar caminhos em labirintos, visitar múltiplos objetivos e coletar comida de forma eficiente, usando tanto busca não informada quanto informada.

### Técnicas implementadas
- **Busca não informada:** Depth-First Search (DFS), Breadth-First Search (BFS), Uniform Cost Search (UCS)  
- **Busca informada:** A* Search com heurísticas consistentes  
- **Problemas compostos:** Corners Problem e Eating All The Dots (heurísticas próprias)  

---

## Estrutura do Projeto

### Arquivos implementados
- `search.py` → Implementação de DFS, BFS, UCS e A*  
- `searchAgents.py` → Agentes que usam os algoritmos de busca + heurísticas personalizadas  

### Arquivos de suporte
- `pacman.py` → Motor do jogo  
- `game.py` → Estruturas de estados e regras do ambiente  
- `util.py` → Estruturas de dados (pilha, fila, fila de prioridade)  
- Outros: `graphicsDisplay.py`, `textDisplay.py`, `autograder.py`, `test_cases/` etc.  

---

## Questões Resolvidas

| Questão | Implementação |
|---------|---------------|
| Q1 | Depth-First Search (DFS) |
| Q2 | Breadth-First Search (BFS) |
| Q3 | Uniform Cost Search (UCS) |
| Q4 | A* Search |
| Q5 | Corners Problem |
| Q6 | Heurística para Corners |
| Q7 | Eating All The Dots |
| Q8 | Suboptimal Search |

---

## **Resultados Obtidos**
Passaram em 100% dos testes do autograder.
