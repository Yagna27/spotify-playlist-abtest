This project analyzes whether **mood-based** playlists outperform **genre-based** playlists in listener engagement, using data from the Spotify Web API.

## 🔍 Objective
Determine if mood-themed playlists result in higher average track popularity than genre-themed ones.

## 📊 Approach
- Collected ~2,300 playlists (~138K tracks) from Spotify
- Labeled playlists as *Mood* or *Genre*
- Calculated engagement metrics: avg track popularity, duration, track count
- Performed:
  - Independent two-sample t-test
  - Bootstrap confidence intervals
  - Outlier analysis

## ✅ Results
- Mood playlists show significantly higher engagement  
- 95% CI for mean difference (after outlier removal): **[5.56, 7.99]**  
- Statistical tests confirm robustness of findings

## 🛠️ Tech Stack
- Python (Pandas, NumPy, SciPy, Seaborn, Matplotlib)
- Spotify Web API
- Jupyter / Colab

## 📌 Conclusion
**Mood-based playlists are more engaging** than genre-based ones, as measured by average track popularity — statistically and practically significant.

## 📬 Contact
[LinkedIn](https://www.linkedin.com/in/yagnasreependala/) | meetyagna@gmail.com
