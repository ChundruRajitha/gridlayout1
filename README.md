# Cricket Stats Dashboard

A visually appealing and responsive dashboard designed to display cricket statistics and other related information such as top players, teams, and match reports. This project uses a grid layout to present various statistics for a specific cricket season, offering an engaging way to showcase key metrics.

## Features

- **Responsive Grid Layout**: The dashboard layout automatically adapts to different screen sizes, making it mobile-friendly.
- **Player and Team Stats**: Displays stats such as the number of sixes, hundreds, Orange Cap holder stats, and FairPlay winners.
- **Icons and Backgrounds**: Use of Font Awesome icons and custom background images to enhance the visual appeal of the dashboard.
- **Visually Organized Information**: Data is organized in separate sections (boxes), which makes it easy to find relevant statistics.

## Sections in the Dashboard

1. **Box 1**: Displays the number of sixes hit in the season.
2. **Box 2**: Displays the winner of the season with the team logo.
3. **Box 3**: Displays the number of hundreds scored in the season.
4. **Box 4**: Displays the Orange Cap winner (top scorer) with relevant statistics.
5. **Box 5**: Displays the FairPlay winner with points.
6. **Box 6**: Displays an icon for the "Pics" section (could be linked to player images or highlights).
7. **Box 7**: Displays an interesting fact about the season or the league.
8. **Box 8**: Displays an icon for the "Match Reports" section.
9. **Box 9**: Displays an icon for the "Highlights" section.

## Technologies Used

- **HTML**: Used for structuring the page and content.
- **CSS**: Used for styling the layout, grid, and responsive design.
- **Font Awesome**: Used for icons to represent different sections.
  
## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/cricket-stats-dashboard.git
   ```

2. **Navigate to the project folder**:
   ```bash
   cd cricket-stats-dashboard
   ```

3. **Open the `index.html` file** in any web browser to view the dashboard.

## Project Structure

```
/cricket-stats-dashboard
│
├── index.html             # Main HTML file
├── /asserts               # Folder for storing images and assets
│   ├── image1.avif        # Image for background
│   ├── image2.avif        # Image for background
│   └── CSK logo.png       # Team logo
└── README.md              # Project documentation
```

## Customization

- You can **update the content** in the boxes by modifying the HTML inside each `<div>` element with class `box`.
- You can **change the background images** by replacing the files inside the `/asserts` folder.
- To adjust the **layout** or grid structure, update the `grid-template-columns` and `grid-template-rows` properties in the CSS file.
- The Font Awesome icons can be updated to suit other types of content or replaced with different icons.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The **Font Awesome** library for icons: [Font Awesome](https://fontawesome.com/)
- The **CSS Grid Layout** for responsive design.
