# Hi! 👋

```python
class DataEngineer:
    """A class representing a Data Engineer."""

    def __init__(self):
        """Initialize the Data Engineer with some attributes."""
        self.attributes = {
            "name": "Kodotautas",
            "current_role": "Data Engineer",
            "programming_languages": ['Python', 'GoLang', 'SQL'],
            "cloud_services": {'GCP': ['Dataflow', 'Datastream', 'Dataform', 'Cloud functions']},
            "tools": ['Airflow', 'dbt', 'Kubernetes', 'Docker'],
            "bi_tools": ['Superset', 'Looker Studio', 'Streamlit', 'PowerBi', 'Tebleau'],
            "hobbies": ['Coding', 'Transport', 'Sports Photography']
        }

    def display_info(self):
        """Display all the information of the Data Engineer."""
        print(f"Hi, I'm {self.attributes['name']} and I'm a {self.attributes['current_role']}. Thanks for visiting!")
        print(f"My hobbies are: {', '.join(self.attributes['hobbies'])}")
        print(f"I know these programming languages: {', '.join(self.attributes['programming_languages'])}")
        print(f"I have experience with these cloud services: {', '.join(self.attributes['cloud_services'])}")
        print(f"I use these tools: {', '.join(self.attributes['tools'])}")

me = DataEngineer()
me.display_info()
```

## 🏆 GitHub Trophies

[![trophy](https://github-profile-trophy.vercel.app/?username=Kodotautas&theme=nord&column=7)](https://github.com/ryo-ma/github-profile-trophy)
