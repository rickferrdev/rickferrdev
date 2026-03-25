<!-- Banner -->
<p align="center">
  <img src="img/banner.jpg" alt="Banner" width="100%" height="250px" style="object-fit:cover; border-radius:12px;">
</p>

<div align="center">

### Hey! I'm Henrick 👋

Always looking for new **experiences** and challenges!

[![tabnews](https://img.shields.io/badge/tabnews-000000?style=for-the-badge&logo=tabnews&logoColor=white)](https://www.tabnews.com.br/rickferrdev)
[![linkedin](https://img.shields.io/badge/Linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rickferr)

---

Backend developer with experience in API architecture and system integrations.
Focused on robust software engineering, security, testing, documentation, and standardization.
Dedicated to continuous learning, critical requirements analysis, and multidisciplinary collaboration.

</div>

```go
type Languages string
type Tools string
type Architecture string

type Rickferr struct {
	Name         string
	Age          uint
	Code         []Languages
	Tools        []Tools
	Architecture []Architecture
}

rickferr := Rickferr{
	Name:  "Henrick Ferreira Saraiva",
	Age:   18,
	Code:  []Languages{"JS/TS", "golang", "rust", "python"},
	Tools: []Tools{"prettier", "eslint", "biome"},
	Architecture: []Architecture{
		"RESTful APIs",
		"Clean Architecture",
		"Microservices",
		"Event-Driven Architecture",
		"Hexagonal Architecture",
	},
}

// This will cause a "panic: runtime error: index out of range [4] with length 4"
favoriteLanguage := rickferr.Code[len(rickferr.Code)]
fmt.Println("My favorite language is:", favoriteLanguage)
fmt.Printf("%+v\n", rickferr)
```

---

### 🛠️ Skills

#### Backend
![Node.js](https://img.shields.io/badge/Node.js-2D2D2D?style=for-the-badge&logo=node.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-2D2D2D?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-2D2D2D?style=for-the-badge&logo=javascript&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-2D2D2D?style=for-the-badge&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-2D2D2D?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-2D2D2D?style=for-the-badge&logo=go&logoColor=white)

#### Frontend
![HTML5](https://img.shields.io/badge/HTML5-2D2D2D?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-2D2D2D?style=for-the-badge&logo=css3&logoColor=white)
![React](https://img.shields.io/badge/React-2D2D2D?style=for-the-badge&logo=react&logoColor=white)

#### Database
![SQLite](https://img.shields.io/badge/SQLite-2D2D2D?style=for-the-badge&logo=sqlite&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-2D2D2D?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-2D2D2D?style=for-the-badge&logo=mongodb&logoColor=white)

#### Hosting
![Azure](https://img.shields.io/badge/Azure-2D2D2D?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-2D2D2D?style=for-the-badge&logo=vercel&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-2D2D2D?style=for-the-badge&logo=cloudflare&logoColor=white)

---

<div align="center">

I'm currently studying **System Analysis and Development**.
My goal is to explore different areas of technology to become a well-rounded developer.

I occasionally share tech-related ideas and articles on [LinkedIn](https://www.linkedin.com/in/rickferr) and [Dev.to](https://dev.to/rickferrdev).

Feel free to reach out to me through my website or e-mail for work-related discussions.

I'm currently looking for my first professional opportunity in the programming field! 🖤

<br>

~ rickferr.dev@gmail.com

</div>
