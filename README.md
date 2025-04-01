# Students YAML Data

This repository contains a YAML file with student data, including names, ages, majors, and GPAs.

## 📂 File Structure
- `students.yaml` → Contains structured student data.

## 📜 YAML File Contents
```yaml
students:
  - name: Alice
    age: 21
    major: Computer Science
    gpa: 3.8
  - name: Bob
    age: 22
    major: Mathematics
    gpa: 3.5
  - name: Charlie
    age: 20
    major: Physics
    gpa: 3.9
  - name: David
    age: 23
    major: Chemistry
    gpa: 3.2
  - name: Eva
    age: 21
    major: Computer Science
    gpa: 3.7


🚀 How to Use
Clone the repository:

sh
Copy
Edit
git clone https://github.com/ShikharP21/students.git
Navigate into the folder:

sh
Copy
Edit
cd students
Use Python to read the YAML file:

python
Copy
Edit
import yaml

with open("students.yaml", "r") as file:
    data = yaml.safe_load(file)
    print(data)
🛠 Tools Used
YAML

Git & GitHub

VS Code

📌 Author
Shikhar Pathak

GitHub: ShikharP21

📢 Feel free to fork, star ⭐, or contribute!
markdown
Copy
Edit

### **Steps to Add This in Your Repo**
1. In **VS Code**, create a new file named `README.md`.  
2. Copy and paste the above content.  
3. Save the file.  
4. Push it to GitHub:  
   ```sh
   git add README.md
   git commit -m "Added README file"
   git push origin main
