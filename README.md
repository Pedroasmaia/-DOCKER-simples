# Aprenda DOCKER e contêineres de maneira simples e rápida

- **Instrutor:** [Denilson Bonatti](https://www.linkedin.com/in/denilson-bonatti-54a14529/)
- **Plataforma:** [Udemy](https://www.udemy.com/course/aprenda-docker-simples-e-rapido/)

- [x] Modulo 1 | Introdução e laboratório de estudos.
- [] Modulo 2 | Criação e edição de contêineres.
- [] Modulo 3 | Criação e edição de imagens.
- [] Modulo 4 | Docker Compose.
- [] Modulo 5 | Docker Machine.
- [] Modulo 6 | Docker Swarm.
- [] Modulo 7 | Teste de Carga e Load Balance.

## Modulo 1 | Introdução e laboratório de estudos

### O que é Docker?

- Docker é uma tecnologia de *conteinerização* para criação e uso de *containers* Linux.
- Com ele é possível lidar com *containers* como se fossem *Vms* modulares e leves.
- Tem maior flexibilidade para criar, implantar, copiar ou migrar *containers* de ambientes, otimizando as aplicações.

### O Que é um *container* Linux

- Um *container* Linux  é um conjunto de processos organizados isoladamente do sistema.
- Os arquivos necessários para executar esses processos são fornecidos por uma imagem diferente.
- São estáveis e de fácil migração entre ambientes.

    | "Emulação de um ambiente sem a necessidade de um servidor"

#### Virtualização x Container

- A virtualização permite executar vários sistemas operacionais em um único hardware.
- Os Containers utilizam o mesmo *kernel* (núcleo) do sistema operacional e isolam os processos da aplicação do restante do sistema.
- Consultar Imagem [Conteiner_X_VM.png.](./1-O%20Que%20e%20Docker/Container_X_Vm.png)

Como vemos na imagem em na **Virtualização** caso seja necessário replicar o ambiente o gasto de recuso do hardware seria replicado também, já com o uso de **Containers** se consegue gerir melhor esses recursos de forma que empregamos somente o necessário e utilizara menos armazenamento pois a imagem vira do **Container**.

- Possibilidade de usar ambientes em nuvem, consultar imagem [Container_em_nuvem.png](./1-O%20Que%20e%20Docker/Container_em_nuvem.png)

#### Função do Container no mercado atual?

- Tornando possível o desmembramento de Grandes aplicações em *Microsserviços*
- No microsserviço podemos escalar somente o necessário
