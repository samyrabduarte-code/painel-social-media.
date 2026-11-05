# Painel do Social Media

Painel diário para organizar a produção de conteúdo das contas do escritório:
Luiz Guedes (mentor), João e Diego (sócios), Guedes & Cruz, Leonardo (escritório),
Leonardo Mentor e Murilo.

## O que ele faz

- Monta os posts do dia automaticamente, conforme a frequência de cada conta
  (mínimo e máximo por dia; posts acima do mínimo aparecem como **Opcional**).
- Cada post passa pelas etapas do seu formato:
  - Carrossel / Estático: Pauta → Copy → Arte → Postado
  - Reels: Pauta → Copy (roteiro + legenda) → Vídeo → Arte (capa) → Postado
  - Stories: Pauta → Arte → Postado
- **Por etapa**: quadro com as colunas Falta pauta, Falta copy, Falta arte/vídeo,
  Pronto p/ postar e Postado.
- **Por conta**: cada cliente com seus posts e quantos já saíram no dia.
- **Próximo passo**: sugere a próxima tarefa pelo horário de postagem.
- Pendências do dia anterior podem ser trazidas para hoje com um clique.
- Em **Contas e frequência** você edita nomes, cores, posts por dia e formatos.

## Como abrir

O sistema é um único arquivo, `index.html`. Ele funciona de três jeitos:

1. **GitHub Pages** (endereço na internet): veja abaixo como ligar.
2. **No computador**: baixe o `index.html` e abra no navegador.
3. **No Claude**: a versão publicada no Claude salva o progresso na sua conta.

## Ligar o GitHub Pages

1. No repositório, vá em **Settings → Pages**.
2. Em **Source**, escolha **Deploy from a branch**.
3. Em **Branch**, escolha `main` e a pasta `/ (root)` e clique em **Save**.
4. Em um ou dois minutos o painel fica disponível no endereço mostrado nessa mesma página.

## Onde os dados ficam salvos

Fora do Claude, o progresso fica salvo **só no navegador em que você usar**
(localStorage). Outro computador ou o celular não veem as mesmas marcações, e
limpar os dados do navegador apaga o progresso. Nenhum dado de post é enviado
para o GitHub: o repositório guarda apenas o sistema.
