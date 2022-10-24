## testando k6 e grafana reports

### Para rodar o grafana via docker primeiro instale i docker, depois execute os comandos
docker-compose up -d influxdb grafana

### Para rodar o teste:
docker-compose run k6 run //scripts//teste.js

### Para visualizar o grafico em tempo real:
http://localhost:3000/d/k6/k6-load-testing-results
