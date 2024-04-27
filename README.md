# My Static API

Welcome to the My Static API repository! This repository contains static data for various purposes, such as testing, development, or learning projects.

## Data

### 1. Sneakers Data

The "sneakers.json" file contains information about 25 sneaker products. Each entry includes the name of the sneaker, available sizes, available colors, and the path to the image file.

Example entry:

```json
{
  "name": "AirFlex Runners",
  "sizes": ["7", "8", "9", "10", "11"],
  "colors": ["Black", "White", "Red"],
  "image": "assets/shoes/airflex_runners.jpg"
}
```

### 2. Basketball Shoes Data

The "basketball_shoes.json" file contains information about 25 basketball shoe products. Similar to the sneakers data, each entry includes the name, available sizes, available colors, and the path to the image file.

Example entry:

```json
{
  "name": "Air Dunk Pro",
  "sizes": ["8", "9", "10", "11", "12"],
  "colors": ["Black/Red", "White/Blue", "Gray/Green"],
  "image": "assets/basketball_shoes/air_dunk_pro.jpg"
}
```

## How to Use

1. Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/my-static-api.git
```

2. Access the data files in your project:

```javascript
const sneakersData = require('./my-static-api/sneakers.json');
const basketballShoesData = require('./my-static-api/basketball_shoes.json');
```

3. Use the data in your application as needed. For example:

```javascript
// Access the first sneaker name
console.log(sneakersData[0].name);

// Access the available sizes of the third basketball shoe
console.log(basketballShoesData[2].sizes);

// Access the path to the image of the fifth sneaker
console.log(basketballShoesData[4].image);
```

Feel free to explore and utilize the data provided in this repository for your projects!
```

Make sure to replace "your-username" with your GitHub username. Don't forget to include additional information or adjustments as needed for your project. Hope it is useful!