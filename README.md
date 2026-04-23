# React Assignment CW-05 - Produce Filter App

Hey! This is my React project for the CW-05 assignment. It's a produce filtering app where you can search for fruits and vegetables and filter them by type. I built this to learn React components, state management, and how props work.

## Live Demo
Check out my live app here: https://nazzz00.github.io/react-assignment/

## What I Built

This app has a few different components that all work together:

- **HelloWorld** - Just a simple component that displays a heading. This was my first React component!
- **Counter** - A counter that starts at 5 and increments when you click the button. This helped me understand state and setState().
- **List** - Takes an array of items and displays them as a list using map(). Learned about props and keys here.
- **FilteredList** - The main feature. It has a search bar AND a dropdown filter that work together. You can type to search produce names or filter by Fruit/Vegetables/All.
- **App.js** - Brings everything together and holds the produce data.

## The Produce Data

I hardcoded some produce items to demonstrate filtering:
- Apple (Fruit)
- Banana (Fruit)  
- Carrot (Vegetable)
- Broccoli (Vegetable)
- Orange (Fruit)
- Spinach (Vegetable)

## How to Use

1. The counter shows 5 - click "Increment" to go up
2. Type in the search box to filter produce by name
3. Use the dropdown to show only Fruits, Vegetables, or everything
4. The search and filter work together - it only shows items that match BOTH

## Styling

I added custom CSS with:
- Variables for consistent colors and spacing
- Hover effects on buttons and list items
- A responsive layout that works on phone and desktop
- Visual feedback when you hover and click

## What I Learned

- **Components** - Breaking UI into reusable pieces makes everything cleaner
- **State** - Using setState() instead of directly modifying state (important!)
- **Props** - Passing data from parent to child components
- **Filtering** - Using filter() and AND logic to combine search + dropdown
- **Deployment** - Getting this on GitHub Pages was a struggle but I finally got it working!

## Running This Locally

If you want to run this on your computer:

```bash
# Clone the repo
git clone https://github.com/Nazzz00/react-assignment.git

# Go into the folder
cd react-assignment

# Install dependencies
npm install

# Install react-bootstrap (for the dropdown)
npm install react-bootstrap bootstrap

# Start the app
npm start
