# 🎵 Minhas Músicas – Projeto Java  
### Herança, Encapsulamento e Polimorfismo em uma Aplicação de Áudio

Este projeto implementa um pequeno sistema de gerenciamento de músicas e podcasts utilizando conceitos fundamentais da **Programação Orientada a Objetos (POO)** em Java.  

A aplicação simula reproduções, curtidas e uma lista personalizada de conteúdos favoritos, trabalhando com herança, encapsulamento e polimorfismo.

---

## 📌 Sobre o Projeto

O sistema possui uma superclasse **Audio**, da qual derivam:

- **Musica**
- **Podcast**

Além disso, existe a classe:

- **MinhasPreferidas**, responsável por analisar e exibir quais áudios são considerados favoritos do usuário.

A classe `Principal` demonstra o funcionamento das classes simulando reproduções, curtidas e a seleção de preferidos.

---

## 🏛️ Estrutura de Pastas

src/
├── br/com/minhasmusicas/modelos/
│ ├── Audio.java
│ ├── Musica.java
│ ├── Podcast.java
│ └── MinhasPreferidas.java
│
└── br/com/minhasmusicas/principal/
└── Principal.java


---

## 🧠 O que o Código Faz?

### ▶️ Classe `Principal`

A classe principal demonstra a criação e manipulação dos objetos:

- **Criação de uma música**
  - Título: “Favorita”
  - Cantor: Yunk Vino
  - Reproduzida 1000 vezes
  - Curtida 50 vezes

- **Criação de um podcast**
  - Título: “podpah de verão”
  - Apresentadores: Igão e Mítico
  - Reproduzido 200 vezes
  - Curtido 400 vezes

- **Ambos são enviados para a classe `MinhasPreferidas`**, que analisa quais são os mais populares.

---

## 🧩 Conceitos de POO Aplicados

- **Herança:**  
  As classes `Musica` e `Podcast` herdam atributos e métodos de `Audio`.

- **Encapsulamento:**  
  Atributos protegidos e acesso controlado via getters, setters e métodos como `curte()` e `reproduz()`.

- **Polimorfismo:**  
  A classe `MinhasPreferidas` aceita objetos genéricos do tipo `Audio`, funcionando para qualquer derivado.

- **Abstração:**  
  A lógica comum entre diferentes tipos de áudio está isolada na superclasse.

---
Projeto disponível para fins educacionais e de estudo.

