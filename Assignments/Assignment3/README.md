Assignment - 3: In this assignment, you will create a RESTful API using Express.js and integrate it with MongoDB to perform CRUD operations on a database.

Steps to use the above code

1. Download the above code files and open that folder in VS Code.
2. Open the terminal and navigate to the folder where all the above code files are saved.
3. Run the following command so that all the necessary dependencies are installed into the folder:
npm install

4. After all the dependencies are installed, open a new terminal and run the following command so that MongoDB will be started in the backend:
mongod

5. Return back to the first terminal and run the following command to start the application:
nodemon run start

6. Open your Postman workspace, select the HTTP request as GET and paste this url: http://localhost:9000/books and click "Send"(This will retrieve all the data stored in the database.)
![image](https://github.com/BharathiDhereddy/20JG1A4216_Bharathi/assets/92772141/566cd332-1e1a-4df9-a10f-390bf0f3b824)

7. To post new data to the database, change the HTTP request to POST and add data in the JSON format
   ![image](https://github.com/BharathiDhereddy/20JG1A4216_Bharathi/assets/92772141/159c61a3-619a-4595-8817-cd5b46b6ad28)

  
8. Then click "Send". The data is inserted into the database and you will get the following response
![image](https://github.com/BharathiDhereddy/20JG1A4216_Bharathi/assets/92772141/69e3058b-82e7-444e-8a2c-0a5234025822)


9. To check if the data is really inserted or not, change into GET and click "Send" again.
![image](https://github.com/BharathiDhereddy/20JG1A4216_Bharathi/assets/92772141/aef81927-b142-4f1b-8197-047a672b8495)


10. To modify existing data in the database, change into PATCH and modify the url and click "Send".
![image](https://github.com/BharathiDhereddy/20JG1A4216_Bharathi/assets/92772141/7819d3d6-ff34-4de3-b940-e306f9ac1bd4)


11. After the data is modified, you will get the following output:
![image](https://github.com/BharathiDhereddy/20JG1A4216_Bharathi/assets/92772141/ed083141-423e-4a97-ba70-dbdf50e19dc0)


12. To delete a particular data, change into DELETE, modify the url and click "Send".
![image](https://github.com/BharathiDhereddy/20JG1A4216_Bharathi/assets/92772141/8f374198-5f18-453a-bde7-1b6ca0f47bf8)

