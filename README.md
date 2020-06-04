# :rocket: Next Level Week - Ecoleta :recycle:

## Proposal:

Create an application to help people find collect points of recyclable materials near.

## :fire: Running

Clone the repository:

```sh
 git clone git@github.com:LordMendes/NLW-01.git
```

### :computer: Backend

Open the terminal in 'backend' folder and run:

```sh
npm install
```

To run the server run:

```sh
npm start
```

To run the migrations run:
```sh
npm run knex:migrate
npm run knex:seed
```
#### :orange_book: REST API

##### :triangular_flag_on_post: Points

Points are the collect points of the recyclable items.

Point object example:
```JSON
{
    "name":"Market Name",
    "email":"market@market.com",
    "whatsapp":"9999999999",
    "latitude": 46.982398,
    "longitude": -64.652346,
    "city": "São Paulo",
    "uf": "SP",
		"items": [
			1,
			2,
			6
		]
  }
```
#### Point Routes:
| Entity | Request | Type | Route       | Param       |
|--------|---------|------|-------------|-------------|
| Point  | GET     | none | /points/:id | Route Param |
| Point  | GET     | none | /points     | Query       |
| Point  | POST    | JSON | /point      | Body        |

#### :sake: Items

Items are created as seeds:

#### Items Routes:


| Entity | Request | Type | Route  | Param |
|--------|---------|------|--------|-------|
| Items  | GET     | none | /items | none  |

Return of ``` /items ``` request:

```JSON
  {
    "id": 1,
    "title": "Lâmpadas",
    "image_url": "http://localhost:3333/uploads/lampadas.svg"
  },
  {
    "id": 2,
    "title": "Pilhas e baterias",
    "image_url": "http://localhost:3333/uploads/baterias.svg"
  },
  {
    "id": 3,
    "title": "Papéis e Papelão",
    "image_url": "http://localhost:3333/uploads/papeis-papelao.svg"
  },
  {
    "id": 4,
    "title": "Resíduos Eletrônicos",
    "image_url": "http://localhost:3333/uploads/eletronicos.svg"
  },
  {
    "id": 5,
    "title": "Resíduos Orgânicos",
    "image_url": "http://localhost:3333/uploads/organicos.svg"
  },
  {
    "id": 6,
    "title": "Óleo de cozinha",
    "image_url": "http://localhost:3333/uploads/oleo.svg"
  }
```

## Frontend 

# Under Construction
# :construction:


