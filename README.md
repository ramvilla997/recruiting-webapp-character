# Recruiting Webapp Character

This React-based web application is designed for creating and managing RPG character sheets. It allows users to assign attributes, skills, and classes to characters, perform skill checks, and save character data.

## Project Structure
```sh
recruiting-webapp-character/
├── public/
│ ├── index.html
├── src/
│ ├── components/
│ │ ├── AttributeControls.js
│ │ ├── ClassDisplay.js
│ │ ├── SkillCheck.js
│ │ ├── SkillControls.js
│ ├── pages/
│ │ ├── CharacterSheet.js
│ ├── App.js
│ ├── App.css
│ ├── index.js
│ ├── index.css
│ ├── consts.js
├── package.json
├── README.md


## Installation Instructions

1. Clone the repository:

```sh
   git clone https://github.com/ramvilla997/recruiting-webapp-character.git

2. Navigate to the project directory:

```sh
   cd recruiting-webapp-character

3. Install dependencies:

```sh
   npm install

4. Start the development server:

```sh
   npm start

Navigate to http://localhost:3000 to view the application.

## Usage
Run the following command to start the development server and open the project in a web browser:
```sh
npm start


## API Integration
The application integrates with a backend API to fetch and save characters. Example API endpoints used:

```sh
GET https://recruiting.verylongdomaintotestwith.ca/api/ramvilla997/character
```sh
POST https://recruiting.verylongdomaintotestwith.ca/api/ramvilla997/character


## Contributing
Contributions are welcome. Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.


