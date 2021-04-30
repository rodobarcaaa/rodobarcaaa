### Hi there, I'm Rodolfo Echemendía Quintana 👋

```scala
def profile = {
  val pronouns     = "He" -> "Him"
  val education    = """👨‍🎓 Computer Science Engineer's (Cuba-UCI / Class of 2011)"""
  val blogUrl      = "https://rodobarcaaa.github.io/"
  val askMeAbout   = ("tech", "webdev", "soccer")
  val technologies = for {
    backEnd   <- {
      val scala  = List("Play", "Slick", "Tapir", "Sangria")
      val python = "Learning FastApi"
      scala :+ python
    }
    databases <- List("MySQL", "PostgreSQL", "Redis", "MongoDB")
    devOps    <- List("Docker", "AWS", "CI/CD", "Github Actions")
    frontEnd  <- List("HTML", "CSS", "JS", "TS", "Learning ReactJS")
  } yield println(List(backEnd, databases, devOps, frontEnd).mkString(", "))
}
```

<!--
**rodobarcaaa/rodobarcaaa** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
