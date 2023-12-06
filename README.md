# Portfolio_passwords

## About
This dataset focuses on short passwords and the ease with which they can be cracked in a short amount of time. It aims to answer questions about the types of passwords we should avoid, identify the most commonly used passwords, and understand the time it takes for hackers to crack them and gain access to user accounts. The data for this project was obtained from [Bad Passwords (Never Use them)](https://www.kaggle.com/datasets/sujaykapadnis/bad-passwords-never-use-them). The analysis was conducted using SQL and Tableau.

## About Data
The dataset was obtained from [Bad Passwords (Never Use them)](https://www.kaggle.com/datasets/sujaykapadnis/bad-passwords-never-use-them). It includes a list of passwords used by users of the 'Information is Beautiful' group. The dataset comprises 9 columns and 499 rows:

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

