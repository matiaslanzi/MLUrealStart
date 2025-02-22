# Skeleton Unreal Engine 5.5 Project

This repository serves as a **starting point** for Unreal Engine 5.5 projects, providing a clean and structured foundation for development. It includes essential configurations, folder structures, and a global game instance blueprint for efficient project management.

## **Project Overview**
- **Engine Version:** Unreal Engine 5.5
- **Project Type:** C++ with Blueprint Support
- **Purpose:** Standardized starting point for Unreal Engine projects
- **Focus Areas:** Modular structure, best practices, reusable components

## **Project Structure**
```
ProjectRoot/
│── Source/                  # C++ source code
│── Content/
│   ├── Blueprints/          # Generic blueprint assets
│   ├── UI/                  # UI elements (UMG, textures, fonts)
│   ├── Meshes/              # 3D models
│   ├── Materials/           # Material assets
│   ├── Textures/            # Texture maps
│   ├── Maps/                # Levels and related assets
│   │   ├── Level_01/        # Contains Level_01 map and related assets
│   │   ├── Level_02/        # Contains Level_02 map and related assets
│   ├── Audio/               # Sounds and music
│   ├── Animations/          # Character animations
│── Config/                  # Configuration files
│── Plugins/                 # Custom plugins
│── Docs/                    # Technical documentation
│── .gitignore               # Ignore unnecessary files for Git
│── README.md                # Project overview
```

## **Key Features**
### **1. BP_DefaultGameInstance**
- **Global game state management** (not player-related)
- **Handles level transitions and game settings**
- **Event dispatchers for global events**
- **Save/Load system for settings and configurations**

### **2. Modular Folder Structure**
- **Maps Folder:** Levels are grouped into subfolders, each containing level-specific assets.
- **Player Blueprint:** All player-related logic is handled separately.
- **Centralized Configurations:** Settings are stored in the `Config/` folder.

### **3. Version Control Best Practices**
- Uses `.gitignore` optimized for Unreal Engine projects
- Modular structure for easy collaboration and expansion
- Clear separation between reusable assets and level-specific content

## **Setup Instructions**
1. **Clone the repository**:
   ```sh
   git clone https://github.com/your-repo-url.git
   ```
2. **Open the project in Unreal Engine 5.5**
3. **Set the Default Game Instance:**
   - Go to **Project Settings → Maps & Modes**
   - Set **Game Instance Class** to `BP_DefaultGameInstance`
4. **Run the project and start building!**

## **Contributing**
- Fork the repository and create feature branches.
- Follow the coding standards and file structure.
- Submit a pull request with a clear description of changes.

## **License**
This project is licensed under the MIT License. Feel free to use and modify it to fit your needs.

---
For any questions or contributions, feel free to open an issue or submit a pull request!

