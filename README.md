# Proxy em container realizando redirecionamentos dentro da mesma Docker Network
Exemplo simples do funcionamento de um proxy reverso Nginx em Container Docker, que realiza redirecionamentos para serviços que estão estruturados no mesmo docker-compose.yaml. Alcançabilidade do proxy aos serviços é garantida pela mesma docker network compartilhada entre os containers.

Para bom funcionamento é necessário um DNS estático configurado, redirecionando as urls para o IP da instância que roda o docker daemon.
