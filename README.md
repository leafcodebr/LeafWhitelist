# 💜 LeafWhitelist
* Versões testadas: **1.8**.

## Dependencia
É necessário o plugin [LeafCore](https://github.com/leafcodebr/LeafCore/releases/tag/Downloads) para o funcionamento.

## Configuração
* Lista de Bypass.
* Lista de Whitelist.
* Mensagem de expulsão.

## Permissões
Permissão necessária para o comando: leafwhitelist.whitelist

## Comandos
### Comando /whitelist:
* /whitelist (on:false) - Ativar ou desativar whitelist.
* /whitelist listar - Lista todos os  jogadores da whitelist.
* /whitelist mensagem - Mostra a mensagem de kick da whitelist.
* /whitelist add (jogador) - Adicionar um jogador na whitelist.
* /whitelist remove (jogador) - Remover um jogador da whitelist.
* /whitelist setmessage (mensagem) - Definir a mensagem da whitelist.

## Configuração
```yml
Whitelist:

  # Defina se a whitelist está ligada ou desligada, true para ligada e false para desligada.
  status: false

  # Defina a mensagem que irá aparecer pro jogador quando ele for kickado pela whitelist.
  kickMessage: "O servidor está em whitelist"

  # Aqui você pode botar as pessoas que podem entrar na whitelist forçada.
  bypass:
    - "Vaaaaz"

  # Lista de jogadores presentes na whitelist.
  lista: []
```
