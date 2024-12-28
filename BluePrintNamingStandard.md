# BluePrint Naming Standard

## 1. Variables
```cpp
bIsGameOver       // bool
fPlayerSpeed      // float
iAmmoCount        // int
sPlayerName       // string
vSpawnLocation    // vector
cEnemyColor       // color
arrHighScores     // array
```

## 2. Functions

Start function names with a verb to clearly indicate their purpose:
- **Get**: Retrieves data, e.g., GetPlayerHealth
- **Set**: Assigns data, e.g., SetPlayerSpeed
- **Is/Has**: Returns a boolean value, e.g., IsGameOver, HasWon
- **Calculate**: Performs a calculation, e.g., CalculateDamage
- **Initialize**: Sets up initial values, e.g., InitializeGameState
- **Update**: Refreshes or modifies values, e.g., UpdatePlayerPosition
- **Handle**: Manages an event or input, e.g., HandleInput

```cpp
void GetPlayerHealth();         // Retrieves the player's current health
void SetPlayerSpeed(float Speed); // Updates the player's speed value
bool IsGameOver();              // Checks if the game has ended
void CalculateDamage();         // Computes damage dealt to an enemy
void InitializeGameState();     // Prepares the game state for a new session
void UpdatePlayerPosition();    // Refreshes the player's position
void HandleInput();             // Processes user input
void OnPlayerDeath();           // Responds to the player's death event
void ResetUI_Local();           // Resets the UI within a local scope
```
