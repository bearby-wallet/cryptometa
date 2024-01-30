# cryptometa-

> Public repository used by Bearby wallet to display token information and compute score

### Specification

| Param               | Type     | Required   | Points  | Notes                                                     |
| ------------------- | -------- | ---------- | ------- | --------------------------------------------------------- |
| name                | `String` | `true`     |         |                                                           |
| description         | `String` | `false`    |         | A brief description of the project                        |
| symbol              | `String` | `true`     |         |                                                           |
| web                 | `String` | `false`    | 5       | Websites should use https                                 |
| decimals            | `Number` | `false`    |         |                                                           |
| supply              | `Number` | `false`    |         |                                                           |
| email               | `String` | `false`    |         | Email of the team                                         |
| whitepaper          | `String` | `false`    | 10      | Whitepaper. Not 3 paragraphs you put in a PDF just for that purpose |
| holders             | `Bool`   | `false`    | 10      | Only specify if more than 1000 holders without airdrops   |
| publicTeam          | `Bool`   | `false`    | 20      | Teams members with public verifiable profiles with history (preferably more than 1 one Linkedin) |
| product             | `Bool`   | `false`    | 30      | Usable product on mainnet with decent activity/users + clear token utility + token activity |
| links.research      | `String` | `false`    | 10      | Either binance research, TokenData or the like            |
| links.github        | `String` | `false`    | 10      | Org or account **with repos related to the project**, not an empty one with just the cryptometa fork for example |
| links.linkedin      | `String` | `false`    | 10      | Should have 1 or 2 members public on the page             |
| links.x             | `String` | `false`    | 5       |                                                           |
| links.coinmarketcap | `String` | `false`    |         |                                                           |
| links.coingecko     | `String` | `false`    |         |                                                           |
| links.medium        | `String` | `false`    |         |                                                           |
| links.blog          | `String` | `false`    |         |                                                           |
| links.telegram      | `String` | `false`    |         |                                                           |
| links.discord       | `String` | `false`    |         |                                                           |
| links.facebook      | `String` | `false`    |         |                                                           |
| links.reddit        | `String` | `false`    |         |                                                           |
| links.youtube       | `String` | `false`    |         |                                                           |
| links.instagram     | `String` | `false`    |         |                                                           |

Upon disagreements as to which property a token has/deserves, remember that we
ultimately have the final say in order to protect people as much as we can.
