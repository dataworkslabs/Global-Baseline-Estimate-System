# Global Baseline Estimate Movie Recommendation System

A recommendation system that predicts user movie ratings using the Global Baseline Estimate algorithm, implemented in R.

## 📊 Project Overview

This project implements a non-personalized recommendation algorithm to predict how critics would rate movies they haven't seen. Using survey data from 16 film critics rating 6 movies, the system calculates user and item biases to generate predictions.

**Main Question:** How would critic "Param" rate "Pitch Perfect 2"?

**Answer:** 2.27 out of 5 stars

## 🎯 How It Works

The Global Baseline Estimate uses a simple but effective formula:

**Predicted Rating = Overall Average + User Bias + Movie Bias**

Where:
- **Overall Average (μ):** Mean rating across all critics and movies (3.93)
- **User Bias:** How much a critic rates differently from average (Param: -0.43)
- **Movie Bias:** How much a movie is rated differently from average (Pitch Perfect 2: -1.22)

## 📁 Files

- `Global-Baseline-Estimate-Movie-Recommendations.Rmd` - Main R Markdown analysis
- `Global-Baseline-Estimate-Movie-Recommendations.html` - Rendered HTML report
- `MovieRatings.xlsx` - Raw survey data (16 critics × 6 movies)
- `Assignment3a_Approach_Hamer.qmd` - Planning document
- `README.md` - This file

## 🛠️ Technologies Used

- **R** - Statistical computing and analysis
- **readxl** - Loading Excel data
- **R Markdown** - Reproducible reporting
- Base R graphics - Data visualization

## 📈 Key Findings

- **Deadpool** and **Captain America** were the highest-rated films (above average)
- **Pitch Perfect 2** was the lowest-rated film (1.22 points below average)
- **Param** is a slightly harsher critic than average (rates 0.43 points lower)
- The prediction (2.27) makes sense: harsh critic + unpopular movie = low rating

## 🎨 Visualizations

The project includes a professional bar chart showing movie popularity deviations, with:
- Navy blue bars for above-average films
- Red bars for below-average films
- Colorblind-friendly palette
- Publication-quality styling

## 🚀 How to Run

1. Clone this repository
2. Install R and RStudio
3. Install required package: `install.packages("readxl")`
4. Open the `.Rmd` file in RStudio
5. Click "Knit" to generate the HTML report

## 📚 Course Information

**Course:** DATA 607 - Data Acquisition and Management  
**Assignment:** 3a - Global Baseline Estimate  
**Semester:** Spring 2025

## 🤝 Acknowledgments

- AI assistance from Claude (Anthropic) for R programming guidance
- Course materials from CUNY SPS Data Science program

## 📝 License

Academic project for educational purposes.
