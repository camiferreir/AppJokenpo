# README - App Jokenpô

## 📱 Sobre o Projeto

O **App Jokenpô** é uma aplicação Android desenvolvida em Java baseada no clássico jogo Pedra, Papel e Tesoura.

O jogador escolhe uma opção e o aplicativo gera uma escolha aleatória automaticamente, exibindo o resultado da partida na tela.

---

## 🎮 Funcionalidades

* Escolha entre:

  * Pedra
  * Papel
  * Tesoura

* Resultado automático:

  * Vitória
  * Derrota
  * Empate

* Exibição da escolha do aplicativo através de imagens

* Sistema de placar:

  * Pontuação do jogador
  * Pontuação do aplicativo

* Botão para reiniciar o jogo

---

## 🛠️ Tecnologias Utilizadas

* Java
* Android Studio
* XML
* ConstraintLayout / LinearLayout

---

## 📂 Estrutura do Projeto

### Layout (`activity_main.xml`)

O layout contém:

* `TextView` → título e resultado
* `ImageView` → mostra a escolha do aplicativo
* `Buttons` → Pedra, Papel, Tesoura e Reiniciar
* `TextView` → placar do jogo

---

## 🖼️ Imagens Utilizadas

Adicionar na pasta:

```plaintext
res/drawable
```

As seguintes imagens:

```plaintext
padrao.png
pedra.png
papel.png
tesoura.png
```

---

## 💻 Lógica do Aplicativo

O aplicativo:

1. Recebe a escolha do jogador
2. Gera uma escolha aleatória para o app
3. Compara os resultados
4. Exibe o vencedor
5. Atualiza o placar automaticamente

---

## 📌 Regras do Jogo

* Pedra vence Tesoura
* Tesoura vence Papel
* Papel vence Pedra

---

## 🚀 Funcionalidades Extras

### ✅ Placar

O jogo mantém a pontuação do jogador e do aplicativo.

### ✅ Reiniciar Jogo

O botão “Reiniciar” zera o placar e limpa a rodada atual.

---

## 👨‍💻 Autor

Projeto desenvolvido para fins de aprendizado em Desenvolvimento Mobile Android.
