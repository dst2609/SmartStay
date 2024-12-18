# SmartStay
<p> This repo contains the code and necessary files for the final 256 project</p>

## About
<p>In this project, we explore the idea of recommending hotels to users (authors) based on the large HotelRec dataset. This project aims to develop a hybrid hotel recommendation system that combines collaborative filtering, content-based filtering, and cutting-edge neural
network techniques. </p>

### Data
<p> The dataset is a very large-scale hotel recommendation dataset. Available: https://github.com/Diego999/HotelRec </p>

<p> Filtered data link: https://drive.google.com/drive/folders/17TIW5lzr7n7L6PUetc57WRoDBAKn-XXJ?usp=sharing </p>

### Algorithms
<p> We have used SVD as baseline model and Factorization Machines (FM), Neural Collaborative Filtering (NCF), and Hybrid system for personalized recommendation. </p>

### Evaluations
<p> We have used RMSE and MSE as main evaluation metrics </p>

### System information
<p> Main system used is as follows</p>

| Windows 11 (primary)    | product |
| :--------: | :-------: |
| CPU  | AMD Ryzen 7 9800x3D    |
| GPU | Nvidia RTX 4080 Super 16GB     |
| Memory    | Corsair 64GB DDR5 6000MT/s    |

| MacbookPro (secondary)    | product |
| :--------: | :-------: |
| Chip  | Apple M2 Max    |
| GPU | 10 core     |
| Memory    | 32 GB    |


## USE
<p>Always communicate before commiting to main branch</p>
<p>Never edit anything in the repository on web</p>

## File structure
```plaintext
SmartStay/
│
├── src/                   # Source code files
│   ├── SmartStay.ipynb       # Main Python notebook with data processing
│   ├── FM.ipynb              # Python notebook Factorization Machine
│   ├── Hybrid.ipynb          # Python notebook Hybrid recommendation
│   ├── NCF.ipynb             # Python notebook Neural Collaborative Filtering
│   ├── Naive Predictor.ipynb # Python notebook Naive Average Predictor
│   ├── SVD_basic.ipynb       # Python notebook classic SVD, GridSearchCV and Finer-Split SVD
│   ├── SVD_enhanced.ipynb    # Python notebook MF GPU version and TimeDecay MF
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
