# 🎵 Player de Mídia Local

![Vanilla JS](https://img.shields.io/badge/JavaScript-Vanilla-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-Estrutura-blue)
![CSS3](https://img.shields.io/badge/CSS3-Estilização-red)
![License](https://img.shields.io/badge/License-MIT-green)

Um player de mídia simples, moderno e elegante construído com **HTML, CSS e JavaScript puros**. Permite que os usuários carreguem e reproduzam seus próprios arquivos de áudio e vídeo diretamente no navegador, **sem necessidade de upload ou conexão com servidor**. Tudo acontece localmente no seu dispositivo.

➡️ [ACESSE O PLAYER AQUI!](https://jonjonesbr.github.io/Player_Midia_Local/)

![Demonstração do Player de Mídia Local](https://raw.githubusercontent.com/JonJonesBR/Player_Midia_Local/refs/heads/main/Image1.png)
---

## ✨ Funcionalidades

- **Reprodução Local**: Carregue e reproduza arquivos de áudio e vídeo diretamente do seu computador.
- **Playlist Dinâmica**: Adicione múltiplos arquivos para criar uma playlist personalizada.
- **Controles Completos**: Play, pause, parar, avançar, retroceder e mudo com interface intuitiva.
- **Controle Preciso**: 
  - Barra de progresso (*seek bar*) para navegar pelo tempo da mídia.
  - Controle de volume com barra deslizante.
- **Interface Responsiva**: Funciona perfeitamente em desktops, tablets e smartphones.
- **Feedback Visual**: Indicadores claros do tempo de reprodução, mídia atual e estado dos controles.
- **Zero Dependências**: Feito apenas com tecnologias nativas do navegador — sem frameworks, bibliotecas ou pacotes externos.

---

## 🚀 Como Usar

Este projeto é autocontido em um único arquivo, tornando-o extremamente fácil de usar:

1. 🔽 **Baixe o Código**  
   Clone este repositório ou baixe apenas o arquivo `index.html`:
   ```bash
   git clone https://github.com/JonJonesBR/Player_Midia_Local.git
   ```

2. 🌐 **Abra no Navegador**  
   Basta abrir o arquivo `index.html` em qualquer navegador moderno (Chrome, Firefox, Edge, Safari, etc.).

3. 📁 **Carregue suas Mídias**  
   - Clique em **"Carregar Arquivos de Mídia"**.
   - Selecione um ou mais arquivos de áudio (`MP3`, `WAV`, `OGG`) ou vídeo (`MP4`, `WEBM`, `OGV`).

4. ▶️ **Reproduza e Controle**  
   - Os arquivos aparecerão na playlist à direita.
   - Clique em qualquer item para iniciar a reprodução.
   - Use os controles na parte inferior para gerenciar a reprodução.

> ⚠️ **Nota**: Como o player funciona localmente, os arquivos **não são enviados para nenhum servidor**. Tudo permanece no seu navegador.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica, elementos `<audio>` e `<video>`, e input de arquivos.
- **CSS3**: Estilização moderna com variáveis CSS para fácil personalização de tema, layout responsivo com CSS Grid e animações suaves.
- **JavaScript (ES6+)**: Lógica encapsulada em uma classe `MediaPlayer`, manipulação do DOM, eventos de mídia e gerenciamento de playlist.

---

## 📂 Estrutura do Projeto

A simplicidade é um dos pilares deste projeto. Todo o código está em um único arquivo:

```
index.html
├── <style>     → Estilos CSS (design, responsividade, temas)
├── <body>      → Estrutura da interface (player, controles, playlist)
└── <script>    → Lógica JavaScript (classe MediaPlayer, eventos, manipulação de mídia)
```

> ✅ Ideal para estudo, aprendizado ou como base para extensões.

---

## 🎨 Personalização

Você pode facilmente personalizar o tema alterando as **variáveis CSS** no topo da seção `<style>`:

```css
:root {
  --cor-primaria: #4a90e2;
  --cor-fundo: #121212;
  --cor-texto: #ffffff;
  /* ... */
}
```

Mude cores, fontes ou espaçamentos para adaptar ao seu estilo.

---

## 📁 Contribuição

Contribuições são bem-vindas! Se você quiser melhorar o player, adicionar novas funcionalidades ou corrigir bugs:

1. Faça um fork do repositório
2. Crie uma branch (`git checkout -b recurso/nova-funcionalidade`)
3. Faça commit das suas alterações (`git commit -m 'Adiciona nova funcionalidade'`)
4. Dê push à branch (`git push origin recurso/nova-funcionalidade`)
5. Abra um Pull Request

💡 **Ideias para melhorias**:
- Suporte a teclas de atalho (ex: barra de espaço para play/pause)
- Arrastar e soltar arquivos
- Salvar playlist no `localStorage`
- Modo escuro/claro com toggle

---

## 📄 Licença

Este projeto está licenciado sob a **Licença MIT** – veja o arquivo [LICENSE](LICENSE) para detalhes.

---

## 🙌 Agradecimentos

Obrigado por usar, contribuir ou apenas dar uma olhada!  
Se este projeto foi útil para você, não se esqueça de dar uma ⭐ no repositório!

Feito com ❤️ por JonJonesBR
