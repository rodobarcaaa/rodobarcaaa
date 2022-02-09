### Hi there, I'm Rodolfo Echemendía Quintana 👋

```scala
def profile = {
  val pronouns     = "He" -> "Him"
  val education    = """👨‍🎓 Computer Science Engineer's (Cuba-UCI / Class of 2011)"""
  val blogUrl      = "https://rodobarcaaa.github.io/"
  val askMeAbout   = ("tech", "webdev", "soccer")
  val technologies = for {
    backend   <- {
      val java            = "My first programming language!"
      val scalaFuture     = List("Play-Framework", "Tapir", "Sangria", "Slick")
      val scalaFunctional = List("Http4s", "Tapir", "Cats", "Cats-Effect", "Monix-Task")
      val python          = "Learning FastApi!⚡"
      val node            = "Learning NestJs!𓃠"
      java +: scalaFuture :+ scalaFunctional :+ python :+ node
    }
    database  <- List("MySQL", "PostgreSQL", "Redis", "MongoDB")
    devops    <- List("Docker", "AWS", "CI/CD", "Github Actions")
  } yield println(List(backend, database, devops).mkString(" - "))
}
```

![Rodo's GitHub stats](https://github-readme-stats.vercel.app/api?username=rodobarcaaa&show_icons=true&theme=radical&count_private=true&include_all_commits=tru)


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
