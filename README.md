# ✦ Caça-Estrelas

Um mini game de navegador com visual cósmico, feito para iniciantes praticarem **HTML, CSS e JavaScript**.

## 🎮 Como jogar
1. Clique em **Começar a jogar**.
2. Clique nas estrelas que aparecem na área do jogo.
3. Estrelas amarelas valem 1 ponto; estrelas especiais azuladas valem 3 pontos.
4. Faça o máximo de pontos antes de o tempo acabar (30 segundos).
5. Seu recorde fica salvo no navegador usado, graças ao `localStorage`.

## ▶️ Rodar no computador
1. Baixe ou extraia os arquivos deste projeto.
2. Abra `index.html` no navegador.
3. Pronto! Não é necessário instalar nada.

## ☁️ Publicar e testar pelo GitHub Pages
1. Entre em [github.com](https://github.com/) e faça login.
2. Crie um repositório novo, por exemplo `caca-estrelas`.
3. Extraia o ZIP no seu computador ou celular.
4. Envie **os arquivos e pastas de dentro** do ZIP para a raiz do repositório. O arquivo `index.html` precisa ficar na raiz.
5. No repositório, abra **Settings → Pages**.
6. Em **Build and deployment**, escolha **Deploy from a branch**.
7. Selecione a branch `main` e a pasta `/(root)`, depois clique em **Save**.
8. Aguarde alguns minutos. O GitHub mostrará o endereço publicado na página de configurações do Pages.

> Se você estiver usando apenas o celular, pode criar o repositório pelo navegador e usar **Add file → Upload files** para enviar os arquivos extraídos. Se o GitHub não permitir extrair o ZIP diretamente, extraia-o primeiro no gerenciador de arquivos do aparelho.

## 📁 Estrutura
```text
caca-estrelas/
├── index.html   # estrutura da página
├── style.css    # cores, layout e animações
├── script.js    # regras e funcionamento do jogo
└── README.md    # instruções do projeto
```

## 🧩 O que você pode modificar
- `GAME_DURATION` em `script.js`: duração da partida.
- `moveTarget()`: frequência e pontuação das estrelas especiais.
- Variáveis CSS no início de `style.css`: cores principais.
- Textos e títulos em `index.html`: personalize o jogo.

## 🛠️ Tecnologias
- HTML5
- CSS3
- JavaScript puro (sem bibliotecas)
- `localStorage` para salvar o recorde

## 📄 Licença
Este projeto é livre para estudar, modificar e usar como exercício pessoal.
