<h4 align="center"> بِسْمِ ٱللَّٰهِ ٱلرَّحْمَٰنِ ٱلرَّحِيمِ</h1>


<h1 align="center"> Cricket Club </h1>

<p align="center"> This React application allows users to manage a cricket team by selecting players based on available coins and viewing player details. The app limits the total number of players that can be selected and ensures that only affordable players can be added based on available coins. It features two main sections: "Selected Players" and "Available Players," with smooth navigation between them.</p>

## Project Live Link: 

<p align="center"> <a href="https://cricket-club-build-by-react.netlify.app/">Click Here to Visite Site</a> </p>


## Technologies Used
- **React:** Component-based structure for building UI.
- **React Toastify:** Displays alerts and notifications.
- **Tailwind CSS:** Styled components with a modern, responsive design.


## Key Features
- **Dynamic Coin Management:** Users can add coins to their balance, and each player selection deducts the required amount, ensuring only players within the current balance can be added.

- **Component Navigation:** Easily switch between the "Selected Players" and "Available Players" sections.

- **Player Selection with Limit Validation:** Users can select players until a maximum limit of 6 players is reached, with a warning notification if the limit is exceeded.

- **Affordable Player Validation:** The app checks each player’s cost against the available coins and only allows selection if the balance meets or exceeds the player’s required coins.

- **Intuitive Component Navigation:** Smooth navigation between "Selected Players" and "Available Players" sections allows users to switch views and manage their team easily.

- **Real-Time Notifications:** With React Toastify, the app provides instant feedback to users for events like reaching the player limit, insufficient coins, and successful player selections.




## Project Structure

- **Header:** Displays total coins available.

- **Selected Player Component:** Shows players that have already been selected. Includes a button to navigate to the Available Player section.

- **Available Player Component:** Lists all players available for selection. Only players with costs within the coin balance are selectable.




## Available Players Layout:

<p align="center">
    <img src="https://i.ibb.co.com/0QbJQBH/screencapture-localhost-5173-2024-10-25-13-03-28.png" alt="layout" border="0" >
</p>

## Selected Players Layout:

<p align="center">
    <img src="https://i.ibb.co.com/M6psqKv/screencapture-localhost-5173-2024-10-25-21-22-07.png" alt="layout" border="0" >
</p>

