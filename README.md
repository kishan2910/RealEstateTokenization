# Real Estate Tokenization
 
Backend 

# How to run in local
1. Change file name of ``resources/application.properties.ex`` to ``resources/application.properties``.
2. Change the Application Properties (E.g. username/password of DB) present in ``resources/application.properties``  according to your local mysql-server.
3. Change mysql database information to ``config/DatabaseConfig.java`` file. 
4. After starting application, go to http://localhost:8443/api/swagger-ui.html/

Frontend

1. Open new terminal and Go to frontend directory: run following command: cd frontend
2. Install dependencies present in package.json file: run following command: npm install
3. Run the frontend using following command: npm run serve