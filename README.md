### 👋 Hey, I’m Nahian

🚀 I'm a pragmatic **`Full Stack Developer`** with a **`backend-first mindset`**. I specialize in building scalable APIs, automating workflows, and crafting tools that solve real-world problems — not just ship features.

---

### 🧠 My Core Stack & Tools

| Tech Area       | Stack                                                                 |
|-----------------|-----------------------------------------------------------------------|
| **Languages**   | `C#`, `Java`, `Python`, `PHP`, `JS/TS`                                |
| **Frameworks**  | `ASP.NET Core Web API`, `NestJS`, `Node.js`                          |
| **WordPress**   | `Builders/Themes/Plugins + Custom Code`                                     |
| **Databases**   | `MSSQL`, `MySQL`, `MongoDB`                                           |
| **ORMs**        | `EF Core`, `Dapper`, `NHibernate`                                     |
| **Automation**  | `Selenium`, `Playwright`, `Crawlee`, `nodriver`                       |
| **Testing**     | `xUnit`, `NUnit`                                                      |
| **DevOps**      | `Git`, `GitHub`, `DigitalOcean`, `Azure`                              |
| **IDE/Code Editor**      | `VSCode`, `Visual Studio`, `Rider`, `IntelliJ`               |

---

### 🧪 Code That Teaches

```csharp
// Clear interface segregation to avoid ambiguity
interface IInkPrinter { void Print(string doc); }
interface ILaserPrinter { void Print(string doc); }

internal class Printer : IInkPrinter, ILaserPrinter
{
    private void Print(string doc) { /* logic ambiguity for both printers */ } // ❌
    private void IInkPrinter.Print(string doc) { /* ink logic */ } // ✅
    private void ILaserPrinter.Print(string doc) { /* laser logic */ } // ✅
}
```

---

### 📊 GitHub Activity

<p align="center">
   <img src="https://github-readme-streak-stats.herokuapp.com/?user=nahiandev&theme=algolia&hide_border=true"/>
</p>

<p align="center">
  <a href="https://github.com/nahiandev">
    <img width="430" src="https://github-readme-stats.vercel.app/api?username=nahiandev&show_icons=true&theme=algolia&count_private=true">
  </a>
  <a href="https://github.com/nahiandev">
    <img src="https://github-readme-stats.anuraghazra1.vercel.app/api/top-langs/?username=nahiandev&layout=compact&theme=algolia&langs_count=6" />
  </a>
</p>

<p align="right">
  <img src="https://komarev.com/ghpvc/?username=nahiandev&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views"/>
</p>

---

### 🤝 Let’s Collaborate

I work best with:
- Solopreneurs looking to **automate manual workflows**
- Teams needing **clean API design**
- Clients who value **performance and maintainability**

---

### 🔗 Find Me Online

- 💼 [Hire on Upwork](https://www.upwork.com/freelancers/~01ded0be5baccfa296)  
- 🔗 [Connect on LinkedIn](https://www.linkedin.com/in/nahiandev)
