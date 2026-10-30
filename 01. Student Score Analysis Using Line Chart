
# Student Score Analysis Using Line Chart

# Step 1: Import required libraries
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

# Step 2: Create the student dataset
data = {
    "Student": [
        "sriram", "siva", "naveen", "sriraghu", "ganesh",
        "anil", "naga", "mohitha", "niranjan", "kiran"
    ],

    "Math": [92.5, 93, 98, 82, 56, 94, 90, 89, 90, 87],

    "Science": [90, 82, 76, 98, 92, 80, 79, 91, 89, 95],

    "English": [91, 78, 89, 89, 98, 87, 93, 92, 97, 90],

    "age": [17, 18, 16, 19, 17, 19, 20, 19, 16, 15],

    "hours_studied": [3, 4, 5, 7, 8, 10, 2, 4, 5, 8]
}

# Step 3: Create a DataFrame
df = pd.DataFrame(data)

# Step 4: Display the dataset
print("STUDENT DATASET")
print(df)

# Step 5: Create the line chart
plt.figure(figsize=(10, 5))

# Math marks
plt.plot(
    df["Student"],
    df["Math"],
    marker="o",
    label="Math",
    color="blue"
)

# Science marks
plt.plot(
    df["Student"],
    df["Science"],
    marker="s",
    label="Science",
    color="green"
)

# English marks
plt.plot(
    df["Student"],
    df["English"],
    marker="^",
    label="English",
    color="red"
)

# Step 6: Add chart title and labels
plt.title("Student Score Trends", fontsize=14)
plt.xlabel("Student")
plt.ylabel("Marks")

# Step 7: Rotate student names
plt.xticks(rotation=45)

# Step 8: Display legend
plt.legend()

# Step 9: Adjust chart layout
plt.tight_layout()

# Step 10: Save the chart
plt.savefig("line_chart.png", dpi=150)

# Step 11: Display the chart
plt.show()
