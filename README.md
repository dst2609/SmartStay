# SmartStay
<p> This repo contains the code and necessary files for the final 256 project</p>

## About
<p>In this project, we explore the idea of recommending hotels to users (authors) based on the large HotelRec dataset. This project aims to develop a hybrid hotel recommendation system that combines collaborative filtering, content-based filtering, and cutting-edge neural
network techniques. </p>

### Data
<p> The dataset is a very large-scale hotel recommendation dataset. Available:[HotelRec](https://github.com/Diego999/HotelRec)</p>

### Algorithms
<p> We have used SVD as baseline model and Factorization Machines (FM), Neural Collaborative Filtering (NCF), and Hybrid system for personalized recommendation. </p>

### Evaluations
<p> We have used RMSE and MSE as main evaluation metrics </p>

### System information
<p> Main system used is as follows</p>
| Windows 11 (primary)    | product |
| -------- | ------- |
| CPU  | AMD Ryzen 7 9800x3D    |
| GPU | Nvidia RTX 4080 Super 16GB     |
| Memory    | Corsair 64GB DDR5 6000MT/s    |



## USE
<p>Always communicate before commiting to main branch</p>
<p>Never edit anything in the repository on web</p>

## File structure
```plaintext
SmartStay/
│
├── src/                   # Source code files
│   ├── SmartStay.ipynb       # Main Python notebook         
│   
├── proposal/              # Project proposal
│   ├── Project proposal.pdf         
|
├── data/                  # Data for hotel_reviews (not on github)
│   ├── hotel_reviews.csv                 # csv file containing reviews, converted
|   |── combined_filtered_reviews.csv     # csv file containing processed and filtered reviews
│
├── .gitignore             # Git ignore file
├── README.md              # Main project README
└── LICENSE                # License information
