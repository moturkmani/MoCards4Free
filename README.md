# README.txt

## **Cards4Free - Pokémon Card Giveaway Gallery**

### **Purpose**
The **Cards4Free** project is a gallery-based web application designed to showcase a collection of Pokémon cards that participants can win during live events via my developed trivia game using python script. The cards displayed in the gallery serve as prizes for individuals selected to play the trivia game. 

### **How It Works**
1. **Image Gallery**:
   - The website displays a visually appealing gallery of Pokémon cards.
   - Each card is shown within a fancy picture frame design, making the display vibrant and engaging.
   - Hovering over a card blurs the image and reveals a description overlay.
     
2. **Trivia Game**:
   - The game is simple. The python code is set to ask the participant for first selecting a pokemon region. Then, they select the difficulty level. This difficulty level serves as an indicator for the # of questions you      want to answer and not the actual easiness or hardness of the questions. Easy is 3, Medium is 6, and Hard is 10 questions. You must score at least 80% to be considered a winner.

3. **Selection Process**:
   - During the live event, participants are randomly selected to play the trivia game via a random number generator. Users that choose a number that matches a generated number will be selected to play a round.
   - Winners of the trivia game will then select a number from 1 to 10, and the host will roll a die (up to 3 dice) and add that number to the participant's number and pick a card from the "Pokemon Briefcase" and reveal       the winning card. Based off of the difficulty (1 roll for Easy, 2 rolls for Medium, 3 rolls for Hard), the participant can choose to re-roll if they want to try to get another card. Previous choice will be forfeited      if they decide to roll again. Cards that are chosen to be forfeited are randmoly placed in another briefcase location.
   - Once the participant has chosen their card, it can be shipped to them 100% absolutely free (US only) OR they can select to get a cash prize equivalent to 50% of the card's value directly sent via Venmo. 

### **Key Features**
- **Dynamic Image Display**:
  - The gallery dynamically loads images from a centralized `images/` folder.
  - This ensures scalability and ease of maintenance for large collections.
  
- **User Experience Enhancements**:
  - Smooth animations, such as slide-in effects for images and hover-based interactivity.
  - A clean and responsive design suitable for various devices and screen sizes.

- **Ease of Maintenance**:
  - Adding new cards to the gallery is as simple as uploading images to the `images/` folder and updating the list in the JavaScript file (if not fully automated).

### **Folder Structure**
```
Cards4Free/
├── index.html          # Main HTML file for the website.
├── images/             # Folder containing all Pokémon card images.
│   ├── 1.jpg
│   ├── 2.jpg
│   ├── 3.png
│   └── ...             # Additional card images.
└── style.css           # (Optional) Separate file for additional styles.
├── README.md           # File containing details about the trivia game and structure

### **Getting Started**
1. **Setup**:
   - Clone the repository or download the project files from [GitHub](https://github.com/moturkmani/Cards4Free).

2. **Add Images**:
   - Place new Pokémon card images in the `images/` folder.
   - Ensure file names are unique and extensions are correct.

3. **Host the Website**:
   - The website is hosted using GitHub Pages.
   - The live URL for accessing the gallery is: `https://moturkmani.github.io/Cards4Free`.

4. **Customizing the Trivia Game**:
   - Integrate your trivia game logic into the python script titled 'pokemon_triviagame.py'.
   - Use the gallery to showcase available prizes during the event.

### **Future Enhancements**
- Automate image loading to include all files in the `images/` folder without manual updates.
- Add search or filtering capabilities to make it easier for users to browse specific cards.
- Integrate real-time updates to highlight cards that have already been won.

---
