- š Hi, Iām @EndzDrink
- š Iām interested in web development
- š± Iām currently learning python
- šļø Iām looking to collaborate on any project
- š« How to reach me SAMthembu@gmail.com

<!---
EndzDrink/EndzDrink is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
with open('emails.txt', 'r') as emails:
    emails = emails.readlines()

for email in emails:
    if "gmail" in email:
        print(email.rstrip())
