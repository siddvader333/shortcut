# README

The following are dependencies/steps you may have to take in order to develop on this project.

* Ruby Installation

    Please download Ruby+Devkit 2.7.2-1 (x64) from the following link:  https://rubyinstaller.org/downloads/

    Verify your download by running the command ```ruby -v```

* Rails Installation

    Please install rails once your ruby installation is complete by running the command ```gem install rails```

    Verify the installation by runing the command ```rails --version```

* PostgreSQL Installation

    Please install postgres (Windows x86-64) from the following link : https://www.enterprisedb.com/downloads/postgres-postgresql-downloads

    Add postgres to your computers path/System env variables: C:\Program Files\PostgreSQL\13\bin

    Verify this installation by running the command ```psql -V```

* Run the Server

    You can run the server by running the command ```rails server```

    If this doesn't work, you most likely have to install bundler using ```gem install bundler``` and running the command ```bundler install``` and then rerunning the rails server command. 