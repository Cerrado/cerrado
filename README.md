### Hi there š

```C#

namespace WhatAreThose.Humans
{
  public class Hooman : Entity
  {
    public Hooman(){}
    
    public String[] getCurrentWorkplace()
    {
      var result = [ "Foot Locker EMEA š", "Software Engineer", "Supply Chain" ];
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
      var cSharp     = new Skill{ rating: SkillRating.Expert, years: 5 };
      var java       = new Skill{ rating: SkillRating.Competent, years: 3 };
      var azureCloud = new Skill{ rating: SkillRating.Competent, years: 2};
      var devOps     = new Skill{ rating: SkillRating.Competent, years: 2};
      var webDev     = new Skill{ rating: SkillRating.Proficient, years: 5}; // JavaScript, React, Angular, Nextjs
      var python     = new Skill{ rating: SkillRating.Beginner, years: 1};
      // ... more
      
      List<Skill> solidResult = new List<Skill>{ cSharp, java, azureCloud, devOps, webDev, python };
      return solidResult;
    }
    
    public String getFutureGoals()
    {
      return 'Own another motorcycle šļø, visit Italy š®š¹, improve mastery in Python š, learn F# or Scala š¤';
    }
  }
}

```

<!--
**Cerrado/cerrado** is a āØ _special_ āØ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- š­ Iām currently working on ...
- š± Iām currently learning ...
- šÆ Iām looking to collaborate on ...
- š¤ Iām looking for help with ...
- š¬ Ask me about ...
- š« How to reach me: ...
- š Pronouns: ...
- ā” Fun fact: ...
-->
