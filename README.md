# Spotify Radio 

## Preview

<img src="./prints/demo.png" />

## Checklist Features

- Web API
    - [ ] Deve atingir 100% de cobertura de código em testes
    - [ ] Deve ter testes de integração validando todas as rotas da API
    - [ ] Deve entregar arquivos estáticos como Node.js Stream
    - [ ] Deve entregar arquivos de música como Node.js Stream
    - [ ] Dado um usuário desconectado, não deve quebrar a API
    - [ ] Mesmo que vários comandos sejam desparados ao mesmo tempo, não deve quebrar a API
    - [ ] Caso aconteça um erro inesperado, a API deve continuar funcionando
    - [ ] O projeto precisa ser executado em ambientes Linux, Mac e Windows

- Web App 
    - Client
        - [ ] Deve reproduzir a transmissão
        - [ ] Não deve pausar se algum efeito for adicionado
    - Controller
        - [ ] Deve atingir 100% de cobertura de código em testes
        - [ ] Deve poder iniciar ou parar uma transmissão 
        - [ ] Deve enviar comandos para adicionar audio efeitos à uma transmissão

### Créditos aos áudios usados

#### Transmissão 
- [English Conversation](https://youtu.be/ytmMipczEI8)

#### Efeitos
- [Applause](https://youtu.be/mMn_aYpzpG0)
- [Applause Audience](https://youtu.be/3IC76o_lhFw)
- [Boo](https://youtu.be/rYAQN11a2Dc)
- [Fart](https://youtu.be/4PnUfYhbDDM)
- [Laugh](https://youtu.be/TZ90IUrMNCo)
## FAQ 
- `NODE_OPTIONS` não é um comando reconhecido pelo sistema, o que fazer?
    - Se você estiver no Windows, a forma de criar variáveis de ambiente é diferente. Você deve usar a palavra `set` antes do comando. 
    - Ex: `    "test": "set NODE_OPTIONS=--experimental-vm-modules && npx jest --runInBand",`

- Rodei `npm test` mas nada acontece, o que fazer?
    - Verifique a versão do seu Node.js. Estamos usando na versão 17. Entre no [site do node.js](https://nodejs.org) e baixe a versão mais recente.
