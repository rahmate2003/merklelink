
# MerkleLink - React + Vite
MerkleLink is a web-based application built with React and Vite that allows users to create profile pages by displaying various important links in one place. This app is similar to **Linktree**.
## Features
- **Easy to add links**: Users can add multiple links that will be displayed on their profile page.
- Responsive design**: The app is designed to display well on various devices, including mobile phones.
- Icon support**: Each link can display an icon for easy navigation.
## Project Setup
### 3.1. Project Setup
Create a new project using Vite and React templates:
``bash
npm create vite@latest merklelink --template react
cd merklelink
npm install
```
### 3.2. Installing Additional Dependencies
To add icons and styling, install `react-icons` and other required dependencies:
```bash
npm install react-icons
```
### 3.3. Run the Project
After installing the dependencies, you can run the application with the following command:
```bash
npm run dev
```
## Project Structure
```
/src
  /components
    LinkItem.jsx # Display one link
    Header.jsx # Display profile header
  App.jsx
  index.css # Styling for the application
```
## Developing the App
- **Adding Links**: You can add links by adding a new object inside the `links` array in the `App.jsx` file.
- **Customization 

Translated with DeepL.com (free version)
