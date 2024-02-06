# Chemical Bingo

**The game**

This Chemical Bingo project is a web-based game designed to enhance your knowledge of chemical elements in a fun and interactive way. The game utilizes a Bingo-style grid, where each cell represents a chemical element. The goal is to achieve Bingo by correctly identifying and clicking on the cells that correspond to randomly selected chemical elements.

Here's how the project works:

1. **Initialization:**
   - The game starts by displaying a Bingo grid with four rows and five columns.
   - Each cell in the grid corresponds to a chemical element symbol.

2. **Random Element Selection:**
   - Elements are randomly selected from different orbitals (s, p, d, f) to add an element of unpredictability.
   - The selected element is displayed at the top of the page for reference.

3. **Gameplay:**
   - Players click on the cells corresponding to the selected element.
   - If the clicked cell matches the selected element, it is marked as "clicked" (highlighted in green).
   - If the clicked cell does not match, it is marked as "wrong" (highlighted in red).

4. **Bingo Check:**
   - The game checks for a Bingo after each click.
   - Bingo is achieved when an entire row is filled with correctly clicked cells.
   - The winning row is highlighted, and the player is alerted about the Bingo.

5. **Next Element:**
   - After each click, a new element is randomly selected for the player to identify.
   - The cycle of random element selection and gameplay continues.

6. **Reset and New Game:**
   - Players can reset the game using the "Reset Game" button, which initializes a new grid and element selection.
   - The "Next Element" button triggers the selection of a new random element.

7. **Loading Elements:**
   - The game fetches chemical elements from an external JSON file during initialization.
   - A loading message is displayed until the elements are loaded.


**Local usage**

Once cloned the git, to start the game, first startup the server

 ```  http-server ```

Then, open the URL 'localhost:8080/chemical.html'
