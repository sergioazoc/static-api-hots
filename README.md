# Static Api Hots

Hi! this is a static api from [Heroes of the Storm](https://heroesofthestorm.com/)

## Available languages

- Spanish
- English

Soon add individual Heros.

## Endpoints

### Heroes V1

#### Spanish
GET [https://sergioazoc.github.io/static-api-hots/v1/es/heroes.json](https://sergioazoc.github.io/static-api-hots/v1/es/heroes.json).

#### English
GET [https://sergioazoc.github.io/static-api-hots/v1/en/heroes.json](https://sergioazoc.github.io/static-api-hots/v1/en/heroes.json).

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