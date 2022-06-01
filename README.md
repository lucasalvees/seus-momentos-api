# Seus Momentos API
## Como rodar a aplicação
No terminal, clone o projeto:
```
git clone https://github.com/lucasalvees/seus-momentos-api.git
```
Instale as dependências:
```
npm install
```
Gere uma nova ```APP_KEY``` e copie ela:
```
node ace generate:key
```
Crie um arquivo ```.env```:
```PORT=3333
HOST=0.0.0.0
NODE_ENV=development
APP_KEY= "cole a key gerada aqui"
DRIVE_DISK=local
DB_CONNECTION=sqlite
```
Rode as migrations:
```
node ace migration:run
```
Execute a aplicação:
```
node ace serve 
```
##
Link para o repositório do Seus Momentos:
 [Seus Momentos](https://github.com/lucasalvees/seus-momentos)