### Hi there 👋

```C#

namespace WhatAreThose.Humans
{
  public class Hooman : Entity
  {
    public Hooman(){}
    
    public String[] getCurrentWorkplace()
    {
      var result = [ "Foot Locker EMEA 👟", "Software Engineer", "Supply Chain" ];
      return result;
    }
   
   public enum SkillRating
   {
    Touched = 0,
    Beginner = 1,
    AdvancedBeg = 2,
    Competent = 3,
    Proficient = 4,
    Expert = 5,
    Napoleon = 6
   }
   
    public List<Skill> getNonRustySkills()
    {
      var cSharp = new Skill{ rating: SkillRating.Expert, years: 5 };
      var java = new Skill{ rating: SkillRating.Competent, years: 3 };
      var azureCloud = new Skill{ rating: SkillRating.Competent, years: 2};
      var devOps = new Skill{ rating: SkillRating.Competent, years: 2};
      var webDev = new Skill{ rating: SkillRating.Proficient, years: 5}; // JavaScript, React, Angular, Nextjs
      var python = new Skill{ rating: SkillRating.Beginner, years: 1};
      // ... more
      
      List<Skill> solidResult = new List<Skill>{ cSharp, java, azureCloud, devOps, webDev, python };
      return solidResult;
    }
    
    public String getFutureGoals()
    {
      return 'Own another motorcycle 🏍️, visit Italy 🇮🇹, improve mastery in Python 🐍, learn F# or Scala 🤔';
    }
  }
}

```

<!--
**Cerrado/cerrado** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
