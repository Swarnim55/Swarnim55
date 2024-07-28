# Hi there, I'm Swarnim 👋

I'm a passionate Frontend Developer with over 5 years of experience in web development.
For Frontend, I love working with React, Next.js, and TypeScript.
For Backend, I love working with Node.js, Express, and MongoDB. (Also working with Python and DjangoRestFramework)
Being a CS Engineer, I am also a big fan of IOT, Robotics, and Machine Learning.

## 🛠 Technologies & Tools

- **Languages:** JavaScript, TypeScript, HTML, CSS, C, C++, Python, Java, C#
- **Frameworks:** React, Next.js, Tailwind CSS, Express, DjangoRestFramework
- **Databases:** MongoDB, MySQL, PostgreSQL
- **Tools:** Git, Docker, Jest, Vitest, pnpm, SWR, React Query
- **Other:** CI/CD workflows, ElectronJS, React Native

## 🔥 My GitHub Stats

![Your GitHub Stats](https://github-readme-stats.vercel.app/api?username=swarnim55&show_icons=true&theme=radical)

## 📊 Language Usage

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=swarnim55&layout=compact&theme=radical)

## 🏆 GitHub Trophies

![Trophies](https://github-profile-trophy.vercel.app/?username=swarnim55&theme=radical)

## 🚀 Projects I have worked on

### VisionERP
A collaborative ERP solution for management of workforce, inventory, and point of sales.

### Sageflick
A Complete Theater Management System for theater owners.

### Simuverse
An Augmented Reality embedded e-commerce platform.

### Whirlykop
A web-based tool for analyzing and visualizing data for Advertising and Marketing Agencies.

### UniversityMIS
A web-based tool for managing student information, admissions, finance and other course related stuffs for Colleges and Universities.

## 📝 Certifications

- PHP w MySQL from (VisionLearningCenter)
- Frontend Engineering from Meta (Coursera)
- Machine Learning from Internshala
- Cisco COMPTIA A+ from Cisco

## 📫 How to Reach Me

- [LinkedIn](https://linkedin.com/in/swarnim55)
- [Twitter](https://twitter.com/swarnim55)
- [Email](mailto:swarnim55@gmail.com)

## 📈 Language Ratio Across Repositories

```markdown
```python
import requests
from collections import Counter

username = 'yourusername'
response = requests.get(f'https://api.github.com/users/{username}/repos')
repos = response.json()

languages = Counter()

for repo in repos:
    lang_response = requests.get(repo['languages_url'])
    repo_languages = lang_response.json()
    languages.update(repo_languages)

total_bytes = sum(languages.values())

language_ratios = {lang: (bytes/total_bytes) * 100 for lang, bytes in languages.items()}

for lang, ratio in language_ratios.items():
    print(f'{lang}: {ratio:.2f}%')

## 📊 Average Language Ratio




