# Portfolio_passwords

## About
This dataset focuses on short passwords and the ease with which they can be cracked in a short amount of time. It aims to answer questions about the types of passwords we should avoid, identify the most commonly used passwords, and understand the time it takes for hackers to crack them and gain access to user accounts. The data for this project was obtained from [Bad Passwords (Never Use them)](https://www.kaggle.com/datasets/sujaykapadnis/bad-passwords-never-use-them). The analysis was conducted using SQL and Tableau.

## About Data
The dataset was obtained from [Bad Passwords (Never Use them)](https://www.kaggle.com/datasets/sujaykapadnis/bad-passwords-never-use-them). It includes a list of passwords used by users of the 'Information is Beautiful' group. The dataset comprises 9 columns and 499 rows. Citation("tidytuesdayR")

| Variable       | Class          | Description  |
| ------------- |:-------------:| -----:|
| rank      | popularity in their database of released passwords | double |
| password      | Actual text of the password      |   character |
| category | What category does the password fall in to?      |    character |
| value      | Time to crack by online guessing    |   double |
| time_unit      | Time to crack by online guessing | character |
| offline_crack_sec | Time to crack offline in seconds      |    double |
| rank_alt     | Rank 2 | double |
| strength     | Strength = quality of password where 10 is highest, 1 is lowest      |   double |
| font_size | Used to create the graphic for KIB      |    double |

## Asking Questions
To find answers on how to improve the safety of passwords and help people in creating more difficult-to-crack passwords, we should consider the following questions:

1. Do people prefer creating passwords using numbers, letters or a combination of both?
2. What categories of passwords do people commonly use?
3. Which passwords are the most popular and are they easy to guess?
4. Which types of passwords are more difficult to crack?
5. Is there a correlation between password strength or length and the time needed to crack these passwords?

