# MegaStore

# Sistema de Busca Otimizado para Catálogo de Produtos - MegaStore

## Descrição
Este projeto implementa um motor de busca e recomendação para o catálogo da MegaStore, utilizando **tabelas hash** para indexação rápida (O(1) esperado) e **grafos** para sugerir produtos relacionados. A solução é escrita em Rust, garantindo segurança, desempenho e escalabilidade.

## Tecnologias utilizadas
- **Rust 2021** (linguagem principal)
- Biblioteca padrão (`std::collections::HashMap`, `HashSet`)
- Testes: `cargo test`
- Geração de dados sintéticos: `rand` (apenas em testes)
