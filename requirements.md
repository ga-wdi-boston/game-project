# Requirements

In order to get a satisfactory score, by the time you present your project, you
**must**:

-   Present **working browser game, built by you**, hosted on GitHub Pages.
-   Practice using version control by:

    -   Sharing your work through a **git repository hosted on Github**.
    -   Making **frequent, cohesive commits** dating back to the very beginning
        of the project with **good commit messages**.

-   Produce **documentation** in the form of a **README**, which must:

    -   **Link to your hosted game** in the **URL section** of your Github
        repo.
    -   **List technologies used**.
    -   **Document your planning** and tell a story about your **development
        process** and problem-solving strategy.
    -   **List unsolved problems** which would be fixed in future iterations.
    -   Link to **wireframes and user stories**.

Your app **must**:

-   Be a **single-page** application.
-   Use a custom game engine **written by you**.
-   **Be deployed online**, where the rest of the world can access it.
-   **Render a game board in the browser**.
-   **Switch turns** between X and O (or whichever markers you select).
-   **Visually display which side won** if a player gets three in a row or show
    a draw/"cat’s game" if neither wins.
-   Support playing **multiple games**, one at a time.
-   Use **jQuery** for **DOM manipulation** and **event handling**.
-   Use **AJAX** for interacting with a provided API. Specifically, your app
    must:

    -   **Visually display** the results of retrieving game statistics, such as
        total games won by a user. (READ)
    -   **Create** new games on the server. (CREATE)
    -   **Update** a game by storing new moves. (UPDATE)

-   Have **login**, **logout**, and **change password** functionality.

Your app **must not**:

-   Rely on **refreshing the page** for **any** functionality.
-   Display **non-functional** buttons, nor buttons that **do not successfully
    complete** a task.
-   Have **any** user-facing **bugs**.
-   Be playable **after finishing a game**.
-   Allow players to move in the same square **more than once**.
-   Change players when an **invalid move** is made.

Additionally, you **should**:

-   Use **semantic** HTML.
-   Practice separation of concerns by:

    -   Using the [js-template](https://github.com/ga-wdi-boston/js-template) to
        store HTML, CSS, and JavaScript in the appropriate places.
    -   Storing DOM manipulation code and network code in separate files.

-   **KISS (Keep It Stupidly Simple)**.
-   **DRY (Don't Repeat Yourself)**.

Finally, you **should not**:

-   **Use alerts** for anything.
-   **Display errors** or warnings in the console.
-   **Display debugging** messages in the console.
