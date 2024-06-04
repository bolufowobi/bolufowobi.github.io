<h1 align="center">Babs Olufowobi</h1>

<h2 align="center">About me</h2>

```C#
using System;
using System.Collections.Generic;

var details = new BioDetails
        {
            Details = new Dictionary<string, string>
            {
                ["- ⚡ Quick bio:"] = "Quality oriented self-motivating engineer that is commercially aware, evolving, and enthusiastic about building stuff",
                ["- 👯 I’m looking to collaborate on:"] = "Dotnet, C#, ASP.Net, and Docker related projects",
                ["- 💬 Ask me about:"] = "Dotnet, ASP.NET, C#, SQL, Software Design & Architecture, Web-Dev, and CI/CD Pipelines",
                ["- 📫 How to reach me:"] = "olufowobibabs@gmail.com"
            }
        };

        foreach (var (key, value) in details.Details)
        {
            Console.WriteLine($"{key} {value}");
        }
    

interface IBioDetails
{
    Dictionary<string, string> Details { get; }
}

record BioDetails : IBioDetails
{
    public Dictionary<string, string> Details { get; init; } = new();
}
```

<h2 align="center">You can reach me at :alien:</h2>

<p align="center">
  <a href="mailto:olufowobibabs@gmail.com">
    <img src="https://www.vectorlogo.zone/logos/gmail/gmail-icon.svg" alt="Babs Olufowobi's LinkedIn Profile" height="30" width="30">
  </a>

  <a href="https://www.linkedin.com/in/olufowobibabs/">
    <img src="https://www.vectorlogo.zone/logos/linkedin/linkedin-icon.svg" alt="Babs Olufowobi's LinkedIn Profile" height="30" width="30">
  </a>

  <a href="https://stackoverflow.com/users/14551698/babs-olufowobi?tab=profile">
    <img src="https://www.vectorlogo.zone/logos/stackoverflow/stackoverflow-icon.svg" alt="Babs Olufowobi's Stack Overflow Profile" height="30" width="30">
  </a>
</p>

<h2 align="center">My stack :man_technologist:</h2>

<p align="center">Tools that I use on a daily basis, or that I've used or worked (either much or a bit) with on the past</p>
<p align="center">
  <a href="https://stackshare.io/olufowobibabs/my-stack">
    <img src="http://img.shields.io/badge/tech-stack-0690fa.svg?style=flat" alt="Babs Olufowobi :: StackShare" />
  </a>
</p>
