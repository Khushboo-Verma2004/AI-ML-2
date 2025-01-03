## 🎶 Music Genre Classification  

**Welcome to the Music Genre Classification Project!** 🌟  

In the ever-growing world of music, classifying songs into genres automatically can save time and improve user experiences on streaming platforms. This project uses Machine Learning to classify music tracks into their respective genres based on audio features such as tempo, rhythm, and pitch. By analyzing and extracting key characteristics from the audio files, the model predicts the genre of a given song.  

Utilizing techniques like **Feature Extraction** and **Supervised Learning**, this project showcases how AI can streamline music categorization. Whether you’re a music lover, a data scientist interested in audio processing, or someone exploring the world of machine learning, this project offers an engaging look at how technology is transforming the music industry.  

**Dive into the world of music and AI, and explore the power of genre classification!** 🚀  

# 🙌 Maintainers 👩‍💻 :

- [Vani Varanya](https://github.com/vanivaranya)
- [Saumya Gupta](https://github.com/ISaumya1011)

# 🙌 Collaborator 👩‍💻 :
- [Bhavya](https://github.com/its-bhavya)

---

## OVERVIEW:
This project builds a machine learning model to classify audio data into various genres based on features extracted from audio files. The dataset includes statistical metrics like mean and variance for various audio properties such as MFCCs, spectral centroids, bandwidths, and zero-crossing rates. 

Preprocessing steps include feature extraction and normalization using MinMaxScaler. A Random Forest classifier is trained on the preprocessed data to predict genres. 

The model’s effectiveness is evaluated using metrics like accuracy, confusion matrices, and classification reports, with visualizations to explore class distributions and feature importance.

---

## Project Category: 
Machine Learning

---

## DATASET:
### Features:
***Statistical audio features include:***

length: Duration of the audio file.

chroma_stft_mean and chroma_stft_var: Mean and variance of the chroma short-time Fourier transform.

rms_mean and rms_var: Root Mean Square mean and variance.

spectral_centroid_mean and spectral_centroid_var: Spectral centroid mean and variance.

spectral_bandwidth_mean and spectral_bandwidth_var: Spectral bandwidth mean and variance.

rolloff_mean: Spectral roll-off point mean.

mfcc1_mean to mfcc20_mean and corresponding variances: Mean and variance of the first 20 MFCC coefficients.

zero_crossing_rate_mean and zero_crossing_rate_var: Mean and variance of zero-crossing rates.

harmony_mean and harmony_var: Mean and variance of harmonic content.

perceptr_mean and perceptr_var: Perceptual features mean and variance.

### Target Feature: 
***Audio genre classification with genres:***
 - Rock
 - Pop
 - Jazz
 - Hip-hop
 - Classical
 - Blues
 - Country
 - Disco
 - Metal
 - Reggae

---

## Libraries Used:
 - Librosa
 - Scikit-learn
 - Pandas
 - NumPy
 - Matplotlib
 - Seaborn

---

## 🛠️ How to Get Started  

1. **Fork this Repository**  
   Click the **Fork** button to create your copy of this repository.  

2. **Clone the Repository**  
   ```bash  
   git clone https://github.com/GDG-IGDTUW/AI-ML-1.git  
   cd repo-name  
   ```  

3. **Install Dependencies**  
   Navigate to the project folder you're interested in.  
   For example:  
   ```bash  
   cd Sentiment-Analysis
   ```  
   Load the dataset and Install necessary Libraries

4. **Make Your Contributions**  
   - Perform EDA.
   - Train models.
   - Enhance Accuracy.
   - Add features.  
   - Test your changes.  

5. **Submit a Pull Request**  
   Push your changes and create a pull request to propose your contributions! 🎉  


---

## 🤝 Contributing Guidelines  

We ❤️ contributions! Follow these simple steps to contribute:  

1. **Browse through Issues and Choose any**  
   Browse the [Issues](#) tab and comment on the one you'd like to work on.  

2. **Clone the Repo, Make changes and Branch Out**  
   Create a new branch for your changes:  
   ```bash  
   git checkout -b feature-name  
   ```  

3. **Commit Your Work**  
   Write clear and concise commit messages:  
   ```bash  
   git commit -m "Add: Feature description"  
   ```  

4. **Push and PR**  
   Push your branch and create a pull request for review.  

---

🌟 Tips for Contributors
 - Follow the repository’s code style and structure.
 - Keep ML model training scripts well-indented and include comments.
 - Share any interesting results or insights in the pull request description.
 - If you want an issue to be assigned to you, Tag us and mention so under the issue.
 - Please be patient and Feel free to Tag the maintainer or collaborators for any queries. ❤️

---

Happy Coding and Collaborating!🚀❤️
