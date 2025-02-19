# 🌟 Pokemon API Project

This project allows users to fetch and display Pokémon data using the **PokéAPI**. Users can enter a Pokémon name, retrieve its details, and view its sprite.

## 📝 Features
- Fetch Pokémon data using the **PokéAPI**.
- Display the Pokémon's sprite (image).
- Styled with a **custom Pokémon font** and themed UI.

## 🔧 Technologies Used
- **HTML** for structure
- **CSS** for styling (including custom Pokémon font)
- **JavaScript (ES6)** for fetching data and dynamic content
- **PokéAPI** (https://pokeapi.co/) as the data source

## 🛠 Setup Instructions
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/pokemon-project.git
   ```
2. Navigate to the project folder:
   ```sh
   cd pokemon-project
   ```
3. Open `index.html` in your browser.

## 🌟 Usage
1. Enter a Pokémon name in the input field.
2. Click the **Fetch Pokémon** button.
3. The Pokémon’s sprite will be displayed.

## 📸 Screenshots
Here are some screenshots of the project in action:
![image](https://github.com/user-attachments/assets/3ee5f257-52a3-4325-ac5d-71e20910c422)
![image](https://github.com/user-attachments/assets/42ddfde2-5aa9-4d2e-9957-ccb7456c3ff7)
![image](https://github.com/user-attachments/assets/da723296-f31c-4e5b-ad60-43d9efc780cc)





## 💎 Custom Font Issue (Fix for GitHub Pages)
If the Pokémon Solid font doesn’t load on GitHub Pages, follow these steps:
- Ensure the font file (`PokemonSolid.ttf`) is in the same directory as `index.html`.
- Update `style.css`:
  ```css
  @font-face {
      font-family: 'Pokemon Solid';
      src: url('PokemonSolid.ttf') format('truetype');
  }
  ```
- If the issue persists, use **GitHub's raw URL**:
  ```css
  @font-face {
      font-family: 'Pokemon Solid';
      src: url('https://raw.githubusercontent.com/yourusername/pokemon-project/main/PokemonSolid.ttf') format('truetype');
  }
  ```

## 💡 Improvements
- Add more details like abilities, types, and stats.
- Implement a **dark mode** option.
- Optimize for mobile responsiveness.

## 🌟 Contributing
Pull requests are welcome! Feel free to improve the code and add new features.

## 🏆 Credits
- [PokéAPI](https://pokeapi.co/) for the data.
- Pokémon font by **Chequered Ink**.

## 💎 License
This project is licensed under the **MIT License**.

