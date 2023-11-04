# Podpolye Backend

The repo contains all Microservices related to [Podpolye][podpolye_website].

## Microservices Overview
| Microservice name          | Folder name                | Description                                                                                                                                                                                                                                                                                                                                  |
| -------------------------- | -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Telegram Announcements** | `./telergram_annoucements` | REST API with endpoints to retrieve all Event Annoucements messages from [Podpolye's Telegram Channel][podpolye_telegram_channel]. Uses [Golang](https://go.dev/) + [Echo](https://echo.labstack.com/) as a REST API server and on of Golang specific [Telegram Bot API Libraries][telegram-bot_golang_client] to intercat with Telegram Api |
| **-**                      | -                          | -                                                                                                                                                                                                                                                                                                                                            |

[podpolye_website]: https://podpolye.org
[podpolye_telegram_channel]: https://t.me/de_profundis_clamavi
[telegram-bot_golang_client]: https://core.telegram.org/bots/samples#go