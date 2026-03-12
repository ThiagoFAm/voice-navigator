
# 🎤 Voice Navigator

Assistente de acessibilidade baseado em comandos de voz para controle do computador e navegação na internet.

## 📖 Sobre o Projeto

O **Voice Accessibility Assistant** é um software desenvolvido em Python que permite controlar o computador utilizando **comandos de voz**.  

O objetivo principal é **aumentar a acessibilidade digital**, permitindo que pessoas com mobilidade reduzida, deficiência visual ou dificuldades motoras utilizem o computador de forma mais independente.

O sistema interpreta comandos de voz e executa ações no sistema operacional ou no navegador.

---

## 🎯 Objetivos

- Permitir controle do computador por voz
- Facilitar navegação na internet sem uso de mouse ou teclado
- Criar uma ferramenta acessível para usuários com limitações físicas
- Explorar tecnologias de automação e reconhecimento de voz em Python

---

## 👥 Público-Alvo

Este projeto foi pensado especialmente para:

- Pessoas com mobilidade reduzida
- Pessoas com deficiência visual
- Usuários com dificuldades motoras
- Idosos com dificuldade no uso tradicional do computador
- Usuários que desejam interação por voz

---

## ⚙️ Tecnologias Utilizadas

- **Python**
- **speech_recognition** – reconhecimento de voz
- **PyAudio** – captura de áudio do microfone
- **PyAutoGUI** – controle do sistema operacional
- **Playwright** – automação de navegador
- **pyttsx3** – feedback por voz

---

## 🧠 Como Funciona

O fluxo básico do sistema é:

Usuário fala
↓
Captura do microfone
↓
Reconhecimento de voz
↓
Interpretação do comando
↓
Execução da ação


As ações podem incluir:

- Abrir aplicativos
- Abrir sites
- Pesquisar no Google
- Navegar em páginas web
- Executar comandos no sistema

---

## 🗂 Estrutura do Projeto

voice-navigator/

main.py

speech/
listener.py
tts.py

commands/
interpreter.py
command_registry.py

controllers/
system_controller.py
browser_controller.py

utils/
logger.py


---

## 🚀 Funcionalidades Planejadas

- Reconhecimento de comandos de voz
- Abertura de aplicativos
- Automação de navegador
- Pesquisa por voz
- Feedback sonoro
- Sistema modular para novos comandos

---

## 🔮 Melhorias Futuras

- Interpretação de linguagem natural
- Integração com visão computacional
- Sistema de plugins para novos comandos
- Interface gráfica
- Modo acessibilidade para deficientes visuais

---

## 🤝 Contribuição

Contribuições são bem-vindas!

Você pode contribuir com:

- novos comandos de voz
- melhorias de acessibilidade
- melhorias na arquitetura do projeto

---

## 📄 Licença

Este projeto está sob a licença MIT.





