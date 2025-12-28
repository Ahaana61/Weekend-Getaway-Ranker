# Weekend Getaway Ranker

This project builds a data-driven recommendation engine that suggests the best weekend travel destinations in India based on a given source city.

## Features
- Uses Google review ratings and popularity
- Approximates distance using State and Zone
- Ranks destinations using a weighted scoring algorithm

## Technologies Used
- Python
- Pandas
- NumPy

## How It Works
1. User provides a source city
2. Destinations are filtered to nearby states or zones
3. Rating, popularity, and distance are normalized
4. Final score is calculated and destinations are ranked

## How to Run
```bash
python weekend_getaway_ranker.py
