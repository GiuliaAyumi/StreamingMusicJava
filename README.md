# 🎧 Sistema de Streaming de Áudio - Aplicação Java

Este repositório contém a implementação de um simulador de plataforma de músicas via console. O projeto foi desenvolvido em Java com o propósito de treinar e consolidar os pilares da Programação Orientada a Objetos (POO) em cenários práticos.

## 📌 Metas Alcançadas
- [x] Construção de contratos via interfaces (`Baixavel` e `Reproduzivel`).
- [x] Padronização e organização de diretórios (`br.com.streaming.*`).
- [x] Aplicação funcional via terminal (CLI) sem interface gráfica.
- [x] Foco em Clean Code, separando a regra de negócio da interação com o usuário.
- [x] Utilização clara dos 4 pilares da POO: Encapsulamento, Herança, Abstração e Polimorfismo.

## 🏗️ Arquitetura do Sistema
O projeto foi separado por responsabilidades utilizando a seguinte estrutura de pacotes:
* `br.com.streaming.modelo`: Agrupa as classes que representam os dados do sistema (ex: Música, Playlist, Usuários).
* `br.com.streaming.servico`: Concentra as interfaces de contrato e a lógica de geração de recomendações.
* `br.com.streaming.util`: Classes auxiliares para formatação de dados e validação de entradas do teclado.
* `br.com.streaming.principal`: Ponto de partida do sistema e menus de interação direta com o usuário.

## 🚀 Guia de Execução
1. Faça o clone deste repositório na sua máquina.
2. Certifique-se de compilar os arquivos dentro do diretório `src/br/com/streaming`.
3. Inicie o sistema rodando a classe `StreamingMusica` que está dentro do pacote `principal`.
