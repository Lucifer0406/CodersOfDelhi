Here’s a polished `README.md` tailored for your project **Coders of Delhi** based on the notebooks and datasets you uploaded:

---

# 👥 Coders of Delhi

**Coders of Delhi** is a Python-based data project that simulates a social network of Delhi's tech community. It explores **friend recommendations** and **page suggestions** based on user interests and mutual connections using JSON-based user data.

> 📍Inspired by social platforms like Facebook and LinkedIn – built for learning graph traversal, recommendation systems, and network analysis.

---

## 🗂️ Project Structure

```
├── CODmain.ipynb             # Main notebook for user-based recommendations
├── CODmain2.ipynb            # Extended version with improved logic
├── PeopleYouMayKnow.ipynb    # Suggests friends based on mutual connections
├── PagesYouMightLike.ipynb   # Recommends pages based on friends' interests
├── cleanedDATA.json          # Cleaned minimal dataset
├── data.json                 # Primary dataset
├── data2.json                # Data with deliberate inconsistencies (for testing)
├── massive_data.json         # Larger dataset (30 users) for scalability testing
```

---

## 🔍 Key Features

### ✅ People You May Know

* Uses mutual friends to suggest potential connections.
* Implements basic graph traversal techniques.
* Emulates real-world "People You May Know" logic.

### ✅ Pages You Might Like

* Suggests pages liked by a user's friends but not by the user.
* Enhances engagement by tapping into social recommendations.

---

## 📊 Datasets

* Each JSON file contains:

  * `users`: ID, name, list of friends, and liked pages.
  * `pages`: Page ID and names (e.g. “Python Developers”, “AI & ML Community”).
* `massive_data.json` mimics a larger social graph to evaluate performance.

---

## 📌 How to Run

1. Clone this repo

   ```bash
   git clone https://github.com/yourusername/coders-of-delhi.git
   cd coders-of-delhi
   ```

2. Open notebooks (`.ipynb`) using Jupyter Notebook, VSCode, or Google Colab.

3. Load any of the JSON files depending on the dataset size or type.

---

## 🧠 Skills Demonstrated

* 📚 JSON data parsing
* 🔄 Recommendation algorithms
* 📈 Graph-based logic
* 🧹 Data cleaning and validation
* 📦 Modular notebook structure

---

## 📌 Ideal For

* Beginners exploring data structures
* Learners practicing with graph networks
* Developers interested in social media algorithms
* Mini projects for college or bootcamps

---

## 🛠️ Built With

* Python (v3.8+)
* Jupyter Notebooks
* JSON
* pandas (for extended analysis – optional)

---

Let me know if you want a version with GIFs, demo images, or usage examples in Markdown!
