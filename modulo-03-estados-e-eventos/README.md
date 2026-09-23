# Módulo 03 — Estados e Eventos

## Foco
1. State é a memória que dispara uma nova renderização.
2. `onClick={fn}` (passa a função) e não `onClick={fn()}` (executa na renderização).
3. Imutabilidade: nunca `push` nem alterar objeto direto; criar novo com spread, `map` ou `filter`.
4. Updater function: se o novo valor depende do anterior, `setX(prev => ...)`.
5. Regra de ouro: se dá para calcular, não vira estado.

## Exercícios
- [ ] Galeria de fotos com modal (fechar com `Esc`, `role="dialog"`, `aria-modal="true"`, `alt` descritivo)
- [ ] Quiz (guardar só índice da pergunta e respostas; pontuação é calculada)
- [ ] **Refazer o quiz do zero, sem assistir à aula**

## Perguntas de entrevista
1. Por que não posso usar `lista.push(item)` e depois `setLista(lista)`?
   - Resposta:
2. Qual a diferença entre `setCount(count + 1)` e `setCount(c => c + 1)`?
   - Resposta:
3. No quiz, o que guardei em estado e o que calculei? Por quê?
   - Resposta:
