# Sambodhi Coin
- [DB Schema](https://drawsql.app/teams/technoculture/diagrams/sambodhicoin)

## Probable components and stack
- **Firmware**: ESP32 + Arduino? Nrf9160 + ZephyrRTOS? [-> Om Prakash]
- **Server** for ingesting transactions from Edge Nodes: FastAPI on AWS Lambda? (Using a docker image?) [-> Tanisha(Intern, Sep. 22)?]
- **Database**: Postgres on Supabase?
- A low code **admin panel**: Appsmith? Superblocks?
