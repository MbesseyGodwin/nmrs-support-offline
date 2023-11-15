# Project Name: NMRS-SUPPORT-OFFLINE

Requirements for running Application
1. node
2. npm
3. vs code
4. mysql 
5. openmrs database
6. A computer

This project is divided into two main parts: `backend` and `nmrs-support`.

## Backend

1. Open a terminal and navigate to the `backend` directory:

    ```bash
    cd backend
    ```

2. Install the necessary dependencies:

    ```bash
    npm install
    ```

3. Start the backend server:

    ```bash
    npm start
    ```

   **NOTE:** The application works for only the openmrs database at the facility level. The backend can connect to any openmrs db; the default database is openmrs.
   The backend server should now be running at [http://localhost:5000](http://localhost:5000).

## nmrs-support

1. Open a terminal and navigate to the `nmrs-support` directory:

    ```bash
    cd nmrs-support
    ```

2. Install the necessary dependencies:

    ```bash
    npm install
    ```

3. Start the nmrs-support application:

    ```bash
    npm start
    ```

   The nmrs-support application should now be running at [http://localhost:3000](http://localhost:3000).

## Additional Notes

[Include any additional notes or troubleshooting tips here.]

Now, you can access the backend server and nmrs-support application by visiting the provided URLs. 
Make sure to replace `your_port` with the actual port number used by the applications.

**OWNER:** CARITAS HEALTH INFORMATICS.
**DATE CREATED:** JANUARY 2023.
