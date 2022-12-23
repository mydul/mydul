
<img align='right' src="https://camo.githubusercontent.com/61491d59e71fec5c794945fed916a4a682b6c0404fc31f30b08a0d919c558404/68747470733a2f2f696d616765732e73717561726573706163652d63646e2e636f6d2f636f6e74656e742f76312f3537363966633430316236333162616231616464623261622f313534313538303631313632342d5445363451474b524a4738535741495553374e532f6b6531375a77644742546f6464493870446d34386b506f73776c7a6a53564d4d2d53784f703743563539425a772d7a505067646e346a557756634a45315a7657515578776b6d794578676c4e714770304976544a5a616d574c49327a76595748384b332d735f3479737a63703272795449304871544f6161556f68724938504936465879386339505774426c7141566c555335697a7064634958445a71445976707252715a32395077306f2f636f64696e672d667265616b2e676966" width="230">

### Hi, I'm Mydul ! <img src="https://media.giphy.com/media/fYSnHlufseco8Fh93Z/giphy.gif" width="30">
[![GitHub Mydul](https://img.shields.io/github/followers/mydul?label=follow&style=social)](https://github.com/mydul)

## Mydul's Biodata

```python

import json

class Biodata:
  def __init__(self, name, pronouns, education, experience):
    self.name = name
    self.pronouns = pronouns
    self.education = education
    self.experience = experience
  
  def to_dict(self):
    return {
      'name': self.name,
      'pronouns': self.pronouns,
      'education': self.education,
      'experience': self.experience
    }
  
  def to_json(self):
    return json.dumps(self.to_dict())

biodata = Biodata(
  name = "Mydul Islam",
  pronouns = "He / Him",
  education = "A postgraduate student of University of Siegen",
  experience = "Research Assistant at University of Siegen",
)

print(biodata.to_json())

# A little more about me...

language = ["English", "German", "Bengali"]
programming = ["C", "C++", "Python", "HTML", "CSS", "LaTeX", "MATLAB", "VHDL", "Arduino" , "Shell script"]
tools = ["Microsoft Office", "Proteus", "PSpice", "LTSpice", "OriginPro", "MicroWind", "COMSOL Multiphysics", "Cadence"]
accustomed = ["Linux", "Windows", "Raspbian"]


def my_skills(language, programming, tools, accustomed):

    print("\n")
    print("Language:")
    for lan in language:
        print(f"- {lan}")

    print("\n")
    print("Programming:")
    for pro in programming:
        print(f"- {pro}")

    print("\n")
    print("Tools:")
    for tool in tools:
        print(f"- {tool}")

    print("\n")
    print("Accustomed:")
    for accus in accustomed:
        print(f"- {accus}")

my_skills(language, programming, tools, accustomed)

class SWOT_analysis:
  def __init__(self, strengths, weaknesses, threats, opportunities):
    self.strengths = strengths
    self.weaknesses = weaknesses
    self.threats = threats
    self.opportunities = opportunities

  def bio(self):
    print("\n")
    print("In my own personal SWOT analysis:")
    print(f"My strengths are {self.strengths} \n")
    print(f"My weaknesses are {self.weaknesses} \n")
    print(f"My threats are {self.threats} \n")
    print(f"My opportunities is {self.opportunities} \n")

mydul = SWOT_analysis("optimistic, punctuality, energetic, open to new ideas, team player", "straightforward, sensitive, 
                                        impatient, introvert", "constantly growing industry, overworking", "networking")

mydul.bio()

```
---
⭐️[@mydul](https://github.com/mydul)

<!---
mydul/mydul is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
