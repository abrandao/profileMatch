# ProfileMatch
Match executive profiles


## Some useful commands

-- build the image
  **docker build -t rails-toolbox -f Dockerfile.rails .**

-- Building the project
  **docker compose up --build**

  -- Creating volumes
  **docker volume create --name app-postgres**
  **docker volume create --name app-redis**

-- Database Inicialization:
  **docker­ compose run app rake db:reset**
  **docker­ compose run app rake db:migrate**

-- Docker article reference: 
  **https://semaphoreci.com/community/tutorials/dockerizing-a-ruby-on-rails-application**