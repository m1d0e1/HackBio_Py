```markdown
# 📋 Stage 0: Team Information Notebook

This repository contains a Jupyter Notebook (`Stage_0.ipynb`) that defines and displays information about a team of four members. The notebook is structured to store and present details such as names, usernames, emails, hobbies, countries, disciplines, and preferred programming languages.

---

## 🔗 Access the Notebook

You can view and run this notebook directly on Google Colab by clicking the badge below:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/m1d0e1/HackBio_Py/blob/main/Stage_0.ipynb)
[![LinkedIn Video](https://www.linkedin.com/posts/dorcas-adejuyigbe-313597274_bioinformatics-datascience-python-activity-7294450770626674688-9Pqa?utm_source=share&utm_medium=member_android)

---

## 📂 Repository Structure

The repository contains the following key file:

- **`Stage_0.ipynb`**: A Jupyter Notebook that defines a dictionary (`Aspartic_Acid`) to store team member information and prints it using Python's f-strings for clear and concise output.

---

## 🧑‍🤝‍🧑 Team Members Overview

The `Aspartic_Acid` dictionary contains detailed information about each team member. Below is a summary of the data structure:

| Field         | Description                                                                 |
|---------------|-----------------------------------------------------------------------------|
| `Names`       | List of team member names.                                                 |
| `UserName`    | List of team member usernames.                                             |
| `Email`       | List of team member email addresses.                                       |
| `Hobbies`     | List of hobbies for each team member.                                      |
| `Country`     | List of countries where team members are located.                          |
| `Discipline`  | List of professional disciplines or areas of expertise for each member.    |
| `Language`    | List of preferred programming languages (e.g., Python, R).                 |

---

## 🚀 Code Functionality

### 1. **Data Storage**
The `Aspartic_Acid` dictionary is used to store structured information about the team members. Each key in the dictionary corresponds to a specific attribute of the team members.

Example:
```python
Aspartic_Acid = {
    "Names": ["Mohamed Shaaban", "Kadija Boukate", "Dorcas Adejuyigbe", "Olatunde Omoniyi"],
    "UserName": ["m0hamed", "boukate13", "Dorcas", "visionarx"],
    "Email": ["m0hamed.essamit2000@gmail.com", "boukate13@gmail.com", "dorcasadejuyigbe@gmail.com", "tundeomoniyi913@gmail.com"],
    "Hobbies": [["Football", "Programming", "reading"], "Reading", "Singing and Learning", "singing and tweeting"],
    "Country": ["Egypt", "Morocco", "Nigeria"],
    "Discipline": ["Biobanks & Complex Data Management", "Microbiology & Bioinformatics", "Medical Laboratory Science", "Pharmaceutical sciences"],
    "Language": ["Python", "R"]
}
```

### 2. **Data Display**
The notebook uses Python's f-strings to print detailed information about each team member. This approach ensures that the output is human-readable and well-formatted.

Example Output:
```
The first team member is Mohamed Shaaban. His username is m0hamed. His email is: m0hamed.essamit2000@gmail.com. His hobbies are ['Football', 'Programming', 'reading']. He is from Egypt. He is specialized in Biobanks & Complex Data Management. His preferred programming language is Python.
The second team member is Kadija Boukate. Her username is boukate13. Her email is: boukate13@gmail.com. Her hobbies are Reading. She is from Morocco. She is specialized in Microbiology & Bioinformatics. Her preferred programming language is R.
The third team member is Dorcas Adejuyigbe. Her username is Dorcas. Her email is: dorcasadejuyigbe@gmail.com. Her hobbies are Singing and Learning. She is from Nigeria. She is specialized in Medical Laboratory Science. Her preferred programming language is Python.
The fourth team member is Olatunde Omoniyi. His username is visionarx. His email is: tundeomoniyi913@gmail.com. His hobbies are singing and tweeting. He is from Nigeria. He is specialized in Pharmaceutical sciences. His preferred programming language is Python.
```

---

## 🛠️ Technologies Used

- **Jupyter Notebook**: For interactive coding and documentation.
- **Python**: For data storage, manipulation, and display.
- **f-strings**: For dynamic and readable string formatting.

---
