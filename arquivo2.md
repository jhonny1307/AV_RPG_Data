# Documento de Teste Completo

## Texto

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

---

## Citação

> "Qualquer parser de Markdown parece simples...
>
> ...até você implementar um."
>
> — Programador cansado

---

## Lista mista

1. Primeiro
    - Item A
    - Item B
        - Item B.1
        - Item B.2
2. Segundo
3. Terceiro

---

## Código

```cpp
#include <iostream>

class Pessoa {
public:
    std::string nome;

    Pessoa(std::string n) : nome(n) {}

    void falar() {
        std::cout << "Olá, " << nome << "!\n";
    }
};

int main() {
    Pessoa p("Jhonny");
    p.falar();
}
```

---

## HTML embutido

<details>
<summary>Clique para expandir</summary>

Texto escondido.

- Funciona em alguns renderizadores.
- Em outros, explode silenciosamente.

</details>

---

## Tabela

| Linguagem | Popularidade | Nota |
|-----------|-------------:|------:|
| Python | ⭐⭐⭐⭐⭐ | 10 |
| Java | ⭐⭐⭐ | 7 |
| Rust | ⭐⭐⭐⭐ | 9 |
| C++ | ⭐⭐⭐⭐ | 💀 |

---

Fim do documento.
