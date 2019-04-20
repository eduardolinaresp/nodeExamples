# 1. Inicializar Proyecto

## 1-1. Clonar este proyecto

    https://github.com/eduardolinaresp/nodeExamples.git

#  1.2 iniciar contenedor

    docker-compose up -d

    docker build -t node_image . 

    docker run --rm -d -v ${PWD}:/Home/myapp -p 8000:8000  --name node_container -i node_image


    docker exec -i -t node_container sh


--INSTALL DEPENDENCIES
npm install

-- RUN TESTS
npm run test