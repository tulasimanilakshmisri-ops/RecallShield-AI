Week 9 Practice

Pickle:
df = pd.read_pickle("students.pkl")

Image:
from PIL import Image
img = Image.open("student_data.png")

Glob:
import glob
files = glob.glob("students_*.csv")

Database:
import sqlite3
conn = sqlite3.connect("students.db")
df = pd.read_sql("SELECT * FROM students", conn)
