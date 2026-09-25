# 4Clojure Practice - Start Here! 🚀

## Setup Rápido

### 1. Abra um Terminal

```bash
cd /Users/myzk/my4clojure
clj -A:dev
```

Você verá algo como:
```
Clojure 1.12.0
user=> 
```

### 2. Carregue seus arquivos de solução

```clojure
(require '[elementary-solutions :as es])
(require '[easy-solutions :as e])
(require '[medium-solutions :as m])
(require '[hard-solutions :as h])
```

### 3. Comece a resolver!

## Workflow Prático

### Passo 1: Escolha um exercício

Visite: **https://4clojure.oxal.org/** ou **https://www.4clojure.com**

Comece pelos **elementary** (problemas 1-20 são básicos).

### Passo 2: Resolva no seu arquivo

Abra `src/clj/elementary_solutions.clj` e adicione sua solução:

```clojure
(defn P1 []
  "Nothing but the Truth"
  true)

(defn P2 []
  "Simple Math"
  (+ 2 4))
```

### Passo 3: Teste no REPL

No seu terminal com o REPL aberto:

```clojure
; Reload the file (ou use Ctrl+Shift+P em VSCode e escolha "Reload Window")
(require '[elementary-solutions :as es] :reload)

; Test seu exercício
(es/P1)
; => true

(es/P2)
; => 6
```

### Passo 4: Repita!

Cada novo exercício:
1. Resolvido no arquivo apropriado
2. Testado no REPL
3. Commit quando terminar: `git commit -am "P1 P2 solved"`

## 📝 Exercícios por Dificuldade

### Elementary (Comece aqui!)
1. Nothing but the Truth
2. Simple Math
3. Strings
4. Lists
5. conj on lists
6. Vectors
7. conj on vectors
8. Sets
9. conj on sets
10. Maps
... e mais

### Easy
19. Last Element
20. Penultimate Element
21. Nth Element
22. Count a Sequence
... e mais

### Medium & Hard
Depois que dominar easy, avance para estes.

## 🎯 Dicas

1. **Comece simples**: Elementary e Easy não são tão fáceis quanto parecem
2. **Leia a documentação**: `clojure.core` documentação é sua melhor amiga
3. **Use o REPL**: Teste suas ideias ali antes de adicionar ao arquivo
4. **Compare soluções**: No site 4clojure você vê outras soluções - aprenda com elas!

## 🔄 Cycle de Trabalho

```
1. Abra Terminal → clj -A:dev
2. Site 4clojure → Escolha exercício
3. Abra arquivo → Escreva solução
4. REPL → Teste
5. Git → Commit quando pronto
6. Repeat!
```

## 📂 Arquivos Seus

- `src/clj/elementary_solutions.clj` - Elementary nível
- `src/clj/easy_solutions.clj` - Easy nível
- `src/clj/medium_solutions.clj` - Medium nível
- `src/clj/hard_solutions.clj` - Hard nível

---

**Vamos começar! Abra o terminal e rode `clj -A:dev` agora! 🎉**
