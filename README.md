# Static Api Hots

Hola! está es un api estática de [Heroes of the Storm](https://heroesofthestorm.com/)

## Idiomas disponibles

- Español

Pronto agregaré nuevos idiomas y los heroes de forma individual.

## Endpoints

### Heroes
GET [https://sergioazoc.github.io/api-hots/v1/es/heroes.json](https://sergioazoc.github.io/api-hots/v1/es/heroes.json).

#### Data

| Name  | Type |
| ----- | ----- |
| name  | String |
| title  | String |
| role  | Object [name: String, description: String, slug: String] |
| shortDescription  | String |
| description  | String |
| difficulty  | String |
| circleIcon  | String (url_image) |
| cardPortrait  | String (url_image) |
| franchise  | String |
| slug  | String |
| trait  | Object [name: String, description: String, displayText: String, cooldown: String, slug: String, icon: String (url_image)] |
| abilities  | Object [name: String, description: String, displayText: String, vital: String, cooldown: String, slug: String, icon: String (url_image)] |
| heroicAbilities  | Object [name: String, description: String, displayText: String, cooldown: String, slug: String, icon: String (url_image)] |
| expandedRole  | Object [name: String, description: String, slug: String] |
| stats  | Object [damage: Number, utility: Number, survivability: Number, complexity: Number] |