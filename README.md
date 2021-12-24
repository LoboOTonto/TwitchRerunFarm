# TwitchRerunFarm

Um programa para farmar pontos em lives na twitch. você pode farmar em varias lives ao mesmo tempo, com baixo consumo de rede e de cpu, alem de poder usar vários usuários ao mesmo tempo.

## Configuração

Edite o arquivo Users.Json com seu Usuário e seu AuthToken, pode usar vários usuários. Para pegar o AuthToken de sua conta use esse website https://twitchapps.com/tmi/

```bash
[
	{

		"username": "LoboOTonto",
		"token": "oauth:na8sg96kmwbj7i2gbkzy9gyg2ltvyy"
    
	},
    {

		"username": "ExampleUserName2",
		"token": "ExampleAuthToken3"
    
	}
]
```

## Canais

Edite o arquivo Channels.json com os canais que você quer farmar.

```{
  "Channels": [
    "gaules",
    "kotcka",
	"baiano"
  ]
}
```
