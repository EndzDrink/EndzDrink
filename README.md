- 👋 Hi, I’m @EndzDrink
- 👀 I’m interested in web development
- 🌱 I’m currently learning python
- 💞️ I’m looking to collaborate on any project
- 📫 How to reach me SAMthembu@gmail.com

<!---
EndzDrink/EndzDrink is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
with open('emails.txt', 'r') as emails:
    emails = emails.readlines()

for email in emails:
    if "gmail" in email:
        print(email.rstrip())
