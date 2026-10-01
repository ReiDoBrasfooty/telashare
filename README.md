# 📺 TelaShare

Compartilhamento de tela com os amigos direto no navegador, estilo Discord.

- Crie uma sala e mande o link para os amigos
- Qualquer pessoa na sala pode compartilhar a tela (no computador)
- Várias telas ao mesmo tempo, clique para ampliar
- Chat da sala

Feito com WebRTC + [PeerJS](https://peerjs.com/). Não precisa de servidor próprio: basta hospedar
os arquivos (`index.html` e `peerjs.min.js`) em qualquer site `https`, como o GitHub Pages.

## Servidor TURN

Se alguém não conseguir conectar (redes diferentes, 4G, firewall), configure um servidor TURN
em `SERVIDORES_ICE` no `index.html`. Dá para criar um grátis em https://www.metered.ca/stun-turn.
