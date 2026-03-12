# 🎤 Voice Navigator

Assistente de acessibilidade baseado em comandos de voz para **navegação na internet**.

---

# 📖 Sobre o Projeto

O **Voice Navigator** é um software desenvolvido em **Python** que permite navegar na internet utilizando **comandos de voz**.

O objetivo principal é **aumentar a acessibilidade digital**, permitindo que pessoas com mobilidade reduzida, deficiência visual ou dificuldades motoras naveguem na web sem a necessidade de utilizar teclado ou mouse.

O sistema interpreta comandos de voz e executa ações diretamente no navegador.

---

# 🎯 Objetivos

- Permitir navegação na internet por voz  
- Facilitar acesso a sites sem uso de mouse ou teclado  
- Criar uma ferramenta acessível para usuários com limitações físicas  
- Explorar tecnologias de automação de navegador e reconhecimento de voz  

---

# 👥 Público-Alvo

Este projeto foi pensado especialmente para:

- Pessoas com mobilidade reduzida
- Pessoas com deficiência visual
- Usuários com dificuldades motoras
- Idosos com dificuldade no uso tradicional do computador
- Usuários que desejam interação por voz

---

# ⚙️ Tecnologias Utilizadas

- **Python**
- **speech_recognition** – reconhecimento de voz
- **PyAudio** – captura de áudio do microfone
- **Playwright** – automação de navegador
- **pyttsx3** – feedback por voz

---

# 🧠 Como Funciona

O fluxo básico do sistema é:

Usuário fala
↓
Captura de áudio
↓
Reconhecimento de voz
↓
Interpretação do comando
↓
Execução da ação no navegador


Exemplos de ações possíveis:

- Abrir sites
- Pesquisar no Google
- Navegar em páginas web
- Rolar páginas
- Clicar em elementos

---

# 🗂 Estrutura do Projeto

voice-navigator/

main.py

speech/
├── listener.py
└── tts.py

commands/
├── interpreter.py
└── command_registry.py

controllers/
└── browser_controller.py

utils/
└── logger.py


---

# 🚀 Funcionalidades Planejadas

- Reconhecimento de comandos de voz
- Abertura de sites
- Pesquisa por voz
- Navegação em páginas
- Rolagem de páginas
- Feedback sonoro
- Sistema modular para novos comandos

---

# 📊 Requisitos do Sistema

## Requisitos Funcionais

Os requisitos funcionais descrevem **o que o sistema deve fazer**.

### RF01 – Captura de áudio

O sistema deve capturar áudio do microfone do usuário.

### RF02 – Reconhecimento de voz

O sistema deve converter áudio capturado em texto utilizando uma biblioteca de reconhecimento de voz.

### RF03 – Interpretação de comandos

O sistema deve identificar comandos válidos a partir do texto reconhecido.

Exemplos:

"abrir google"
"abrir youtube"
"pesquisar python"


### RF04 – Abertura de sites

O sistema deve permitir abrir páginas web através de comandos de voz.

### RF05 – Pesquisa por voz

O sistema deve permitir realizar pesquisas na internet utilizando comandos de voz.

### RF06 – Navegação em páginas

O sistema deve permitir navegar dentro de páginas web através de comandos de voz.

Exemplos:

- rolar página
- clicar em links
- voltar página

### RF07 – Feedback ao usuário

O sistema deve fornecer retorno ao usuário informando que o comando foi executado.

Exemplo:

"Abrindo Google"


### RF08 – Tratamento de comandos inválidos

O sistema deve informar quando um comando não for reconhecido.

Exemplo:

"Comando não reconhecido"


---

# ⚙️ Requisitos Não Funcionais

Os requisitos não funcionais descrevem **como o sistema deve funcionar**.

### RNF01 – Usabilidade

O sistema deve permitir interação apenas por voz.

### RNF02 – Performance

O sistema deve responder aos comandos em até **2 segundos**.

### RNF03 – Confiabilidade

O sistema deve tratar erros de reconhecimento de voz sem interromper a execução.

### RNF04 – Escalabilidade

Novos comandos devem poder ser adicionados facilmente ao sistema.

### RNF05 – Portabilidade

O sistema deve funcionar em:

- Windows
- Linux

### RNF06 – Manutenibilidade

O código deve ser organizado em módulos para facilitar manutenção e evolução do sistema.

---

# ⚠️ Restrições do Sistema

O sistema possui algumas limitações técnicas:

- dependência de microfone para captura de áudio
- dependência de bibliotecas externas para reconhecimento de voz
- dependência de automação do navegador

---

# 🔮 Melhorias Futuras

Possíveis evoluções do sistema incluem:

- interpretação de linguagem natural
- leitura de conteúdo de páginas web
- descrição automática de elementos da página
- sistema de plugins para novos comandos
- interface gráfica de configuração

---

# 🤝 Contribuição

Contribuições são bem-vindas!

Você pode contribuir com:

- novos comandos de voz
- melhorias de acessibilidade
- melhorias na arquitetura do projeto

---

# 📄 Licença

Este projeto está sob a licença **MIT**.
