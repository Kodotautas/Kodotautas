# Hi! 👋

<img src="https://komarev.com/ghpvc/?username=Kodotautas&style=flat-square&color=blue" alt=""/>

```python
class DataEngineer:
    """A class representing a Data Engineer."""

    def __init__(self):
        """Initialize the Data Engineer with some attributes."""
        self.name = "Kodotautas"
        self.current_role = "Data Engineer"
        self.programming_languages = ['Python', 'GoLang', 'SQL']
        self.cloud_services = {'GCP': ['Dataflow', 'Datastream', 'Dataform', 'Cloud functions']}
        self.tools = ['Airflow', 'dbt', 'Kubernetes', 'Docker']
        selg.bi_tools = ['Superset', 'Looker Studio', 'Streamlit', 'PowerBi', 'Tebleau']
        self.hobbies = ['Coding', 'Transport', 'Sports Photography']

    def say_hi(self):
        """Greet the user and introduce the Data Engineer."""
        print(f"Hi, I'm {self.name} and I'm a {self.current_role}. Thanks for visiting!")

    def display_hobbies(self):
        """Display the hobbies of the Data Engineer."""
        print(f"My hobbies are: {', '.join(self.hobbies)}")

    def display_skills(self):
        """Display the skills of the Data Engineer."""
        print(f"I know these programming languages: {', '.join(self.programming_languages)}")
        print(f"I have experience with these cloud services: {', '.join(self.cloud_services)}")
        print(f"I use these tools: {', '.join(self.tools)}")

    def __str__(self):
        """Return a string representation of the Data Engineer."""
        return f"DataEngineer(name={self.name}, current_role={self.current_role}, hobbies={self.hobbies}, programming_languages={self.programming_languages}, cloud_services={self.cloud_services}, tools={self.tools})"

me = DataEngineer()
me.say_hi()
me.display_hobbies()
me.display_skills()
print(me)
```

## 🏆 GitHub Trophies

[![trophy](https://github-profile-trophy.vercel.app/?username=Kodotautas&theme=nord&column=7)](https://github.com/ryo-ma/github-profile-trophy)
