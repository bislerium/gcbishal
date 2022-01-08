### Hi there 👋

<!--
**gcbishal/gcbishal** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
using System;
using System.Collections.Generic;
using System.Globalization;

```
namespace Human
{
    internal class Person
    {
        const String Name = "Bishal GC";
        readonly DateTime BirthDate = DateTime.ParseExact("2001/11/08", "yyyy/MM/dd", CultureInfo.InvariantCulture);
        String Passion = "Software Engineer";
        List<String> Interests = new List<string>
        {
            "Internet", "Mobile Application", "DSA", "UI/UX", "Full-stack", "Gaming", "Tech"
        };
        List<String> Language = new List<String>()
        {
            "C#", "Java", "Python", "Dart",
        };
        Dictionary<String, List<String>> Technologies = new Dictionary<String, List<String>>() 
        {
            { "Mobile", new List<String>() {
                    "Flutter",
            }},
            { "Fontend", new List<String>() {
                    "HTML", "CSS", "JS",
            }},
            { "Backend", new List<String>() {
                    "Asp.net", "Django", "Django Rest", 
            }},
            { "Database", new List<String>() {
                    "Oracle SQL", "MySQL",
            }},
            { "Misc", new List<String>() {
                    "XML", "JSON",
            }},
        };
        List<String> Tools = new List<string>()
        {
            "IntelliJ IDEA", "NetBean", "PyCharm", "VS", "VS Code", "Draw.io", "Word", "Powerpoint", "Inkscape", "Figma",
        };
        List<String> Lanuage_Spoken = new List<String>()
        {
            "en_UK", "ne_NP", "hi_IN",
        };
        String AboutMe = @"""
                The End of Graduation sparkles the start of my passion and Carrier. Learning...
                Current Focus on: C# and .Net Technologies
        """;
    }
}
```

