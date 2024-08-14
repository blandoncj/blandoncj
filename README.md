<p align="center">
  <img src="https://i.imgur.com/9Yrnii0.png"></img>
</p>

```python
class Blandoncj(SoftwareEngineer):
  def __init__(self):
    self.username = 'blandoncj'
    self.name = 'Jacobo Blandón'
    self.skills = {
      'frontend': ['HTML', 'CSS', 'Bootstrap', 'Tailwind', 'JavaScript', 'ReactJS'],
      'backend': ['Java', 'Python', 'Flask', 'Django', 'NodeJS'],
      'database': ['MariaDB/MySQL', 'SQLite3', 'PostgreSQL'],
      'tools': ['Git', 'GitHub', 'VSCode', 'Postman', 'Bash']
    }

  def __str__(self):
    return f'{self.name} ({self.username}) - Skills: {", ".join(self.skills.keys())}'

if __name__ =='__main__':
  me = Blandoncj()
  print(me)
```
