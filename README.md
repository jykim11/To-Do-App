# To-DO Web Application

# Introduction

Users of the application will be able to login and sign-up using a username/email and password, or through different authentications such as Google Authentication and Github Authentication. The purpose of the authenticator was to implement a two-factor authentication that helps verify user identities before granting them access to our website. It provides extra layer of security to only grant authorized users to the website.  
The responsive task management app consists of creating tasks, deleting tasks, and searching for a specific task that the user wants to find. There are additional features and components when creating a new task in order to aid utilization of the application. The users can add when the task date is due with an integrated calendar, set a priority of the specific task, and set a reminder so they can be aware of when the task will be due.  
The lists below includes instructions and contributors to the project.

## Deliverables

This github repository contains the code for a simple task management web application. The package will take the form of a **node/react package**, with several dependencies needed to be installed in order to properly run the website. The following script command is needed in order to run the website:

## Project Documentation

Documentation regarding our project's structure and design can be found [here](./docs/README.md)

### To run the application locally:

_Note: Before running application locally, make sure you contact the developer team as credentials have to be provided_

1. Open your terminal and run the following command to install [server dependencies](./docs/dependencies/serverDependency.md):

    ```
    npm install
    ```

2. Access the client directory and install all [client dependencies](./docs/dependencies/clientDependency.md):

    ```
    cd client
    npm install
    ```

3. Go back to the main directory and run the following command to start the server and run the client side **concurrently**

    ```
    cd ..
    npm run dev
    ```

4. The client side will be running on port : http://localhost:3000.  
   The server will be running on port : http://localhost:5555.

5. **All dependencies for server and client will be listed inside `/docs/dependencies` directory.**

## Databases Schemas and Connection

Sirius integrated `MongoDB` to manage database connections for the application. `MongoDB` is a NoSQL document database with scalability and flexibility to store data in JSON-like documents.

More documentation regarding the database can be found [here](./docs/database/Database.md)

## Project Goals

Create a task management application.

This will include:

-   Creating an account locally.
-   Signing in through Google/Github _Note: GitHub Authentication in production environment will be disabled_
-   If signing in with Google/Github, the user will have an opportunity to set their own password.
-   Signing into the application locally.
-   Connecting to a database in order to store/authenticate logging information.
-   Connection to a database to fetch user tasks and task status.
-   Allow users to create/remove tasks.
-   Allow users to modify the task status and toggle reminders.

Future Implementations will include:

-   Implementing a Calendar API in Dashboard for users to have an overall view of all tasks in a calendar view.
-   Allow users to collaborate on tasks with other users of the application.
-   Give users the ability to add other users
-   Add a specific timeline to complete certain tasks

## License

-   The license that was used for the project was MIT License.  
    MIT License is a short and simple permissive license with conditions only requiring preservation of copyright and license notices. Licensed works, modifications, and larger works may be distributed under different terms and without source code.
    -   The license can be found in [LICENSE](./LICENSE)
