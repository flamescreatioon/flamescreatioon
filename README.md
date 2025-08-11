# 👋 Hi, I'm Flames

🚀 **Full Stack Developer | Automation Specialist | Product Designer**

I’m passionate about crafting **beautiful, functional, and impactful** digital experiences — from **web and mobile apps** to **automation systems** that save people hours of work. I blend design thinking with strong technical execution, and I’m always exploring ways to solve real-world problems with code.

---

## 🔥 What I Do

💻 **Web & Mobile Development**  
- MERN / Flutter / Node.js / React / Supabase / PostgresSQL 
/ MongoDB / MySQL / React Native / PHP / Laravel  
- Mobile Applications, Progressive Web Apps, scalable APIs, and database-driven systems

🎨 **UI/UX Design**  
- Figma / Adobe XD / Miro / Jira 

⚙️ **Automation & AI Integration**  
- n8n, Make, Airtable  
- AI-driven personalization and analytics

---

## 🛠 Tech Stack

**Languages:**  
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=000)  ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=fff)  ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=fff)  ![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=fff)  ![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=fff)  ![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=fff)  ![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=fff)  ![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=fff)  

**Frameworks & Tools:**  
`React` `Node.js` `Express` `Flutter` `Supabase` `MongoDB` `TailwindCSS` `n8n` `Firebase` `MySQL` `React Native` `Laravel`

**Design & Collaboration:**  
`Adobe Suite` `Notion` `Slack` `Trello`

---

### My Developer Mind Map

Here's a visual overview of my skills and projects.

```mermaid
graph LR
    %% --- Central Node ---
    A((🏆 My Skillset))

    %% --- Category Nodes ---
    B[🛠 Languages]
    C[📦 Frameworks & Libraries]
    D[⚙️ Tools & Platforms]
    E[🤖 Automation & AI]
    F[🎨 Design & Creative]
    G[🗄️ Databases]

    %% --- Primary Spokes ---
    A --> B
    A --> C
    A --> D
    A --> E
    A --> F
    A --> G

    %% --- Mesh Connections (Linking Categories) ---
    C -- uses --> B
    C -- queries --> G
    D -- deploys --> C
    E -- built with --> B

    %% --- Skill Nodes (connected to categories) ---
    subgraph Languages
        B --> B1[JavaScript]
        B --> B2[TypeScript]
        B --> B3[Python]
        B --> B4[C++]
        B --> B5[Dart]
        B --> B6[SQL]
    end

    subgraph Frameworks & Libraries
        C --> C1[React.js]
        C --> C2[Node.js]
        C --> C3[Next.js]
        C --> C4[Flutter]
        C --> C5[TailwindCSS]
        C --> C6[GraphQL]
    end

    subgraph Databases
        G --> G1[MongoDB]
        G --> G2[PostgreSQL]
        G --> G3[Supabase]
        G --> G4[Firebase]
        G --> G5[MySQL]
    end

    subgraph Tools & Platforms
        D --> D1[Docker]
        D --> D2[Git & GitHub]
        D --> D3[CI/CD]
        D --> D4[Vercel]
        D --> D5[Nginx]
    end

    subgraph Automation & AI
        E --> E1[OpenAI API]
        E --> E2[LangChain]
        E --> E3[Pinecone]
        E --> E4[n8n]
    end

    subgraph Design & Creative
        F --> F1[Figma]
        F --> F2[Adobe Suite]
        F --> F3[Canva]
    end

    %% --- Styling ---
    style A fill:#4CAF50,stroke:#333,stroke-width:3px,color:white
    style B fill:#2196F3,color:white
    style C fill:#9C27B0,color:white
    style D fill:#795548,color:white
    style E fill:#FF9800,color:white
    style F fill:#E91E63,color:white
    style G fill:#f44336,color:white
   
```

```mermaid  
classDiagram
    direction LR

    class Skillset {
        +name: String
        +yearsExperience: int
    }

    class Languages {
        +JavaScript()
        +TypeScript()
        +Python()
        +SQL()
    }

    class Frameworks {
        <<Library>>
        +React_js
        +Node_js
        +Next_js
        +Flutter
    }

    class Databases {
        +PostgreSQL
        +MongoDB
        +Firebase
        +Supabase
    }
    
    class Tools {
        +Docker
        +Git
        +GitHub_Actions
        +Vercel
    }

    Skillset "1" -- "1..*" Languages : knows
    Skillset "1" -- "1..*" Frameworks : uses
    Frameworks --|> Languages : built on
    Skillset "1" -- "1..*" Databases : manages
    Skillset "1" -- "1..*" Tools : operates
```

```mermaid
graph TD
    subgraph Core Expertise [Daily Use & High Proficiency]
        direction LR
        S1[React.js]
        S2[TypeScript]
        S3[Node.js]
        S4[Git & GitHub]
        S5[PostgreSQL]
        S6[Docker]
    end

    subgraph Specialized Tools [Occasional Use & High Proficiency]
        direction LR
        T1[Next.js]
        T2[GraphQL]
        T3[Python]
        T4[CI/CD]
        T5[Nginx]
    end
    
    subgraph Foundational Knowledge [Daily Use & Competent]
        direction LR
        U1[SQL]
        U2[JavaScript]
        U3[TailwindCSS]
        U4[Figma]
    end

    subgraph Broad Skills [Occasional Use & Competent]
        direction LR
        V1[Flutter]
        V2[C++]
        V3[Java]
        V4[OpenAI API]
        V5[Adobe Suite]
    end

    style Core Expertise fill:#e8f5e9,stroke:#4caf50
    style Specialized Tools fill:#e3f2fd,stroke:#2196f3
    style Foundational Knowledge fill:#fff3e0,stroke:#ff9800
    style Broad Skills fill:#fce4ec,stroke:#e91e63
```

```mermaid
pie
    title Skill Distribution
    "Languages" : 10
    "Frameworks & Libraries" : 11
    "Tools & Platforms" : 10
    "Automation & AI" : 7
    "Design & Creative" : 6
    "Databases" : 6
```

## 📌 Featured Projects

- **🏠 Housing Platform (P2P + Escrow)** – A secure property rental/purchase system with KYC verification & Supabase backend.  
- **🍔 Buka Food Ordering App** – Flutter + Node.js with QR-based menu and real-time order tracking.  
- **🤖 AI Booking Agent** – Voice-enabled booking assistant using Twilio, GPT, and real-time transcription.  
- **📊 Lead Generation Automation Tool** – AI-powered cold email automation with tracking and follow-ups.  

*(More in my repos — feel free to explore!)*

## 📊 GitHub Stats & Activity

![Flames's GitHub Stats](https://github-readme-stats.vercel.app/api?username=flamescreatioon&show_icons=true&theme=radical)  ![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=flamescreatioon&layout=compact&theme=radical)  

![Flames's Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=flamescreatioon&theme=react-dark&hide_border=true)

![GitHub Streak](https://streak-stats.demolab.com?user=flamescreatioon&theme=radical&hide_border=true)  

---

---

## 📫 Let’s Connect

- **Portfolio:** [Coming Soon 🚧]  
- **LinkedIn:** [https://www.linkedin.com/in/ugo-nelson-757811246/]
- **Twitter:** [https://x.com/Flames_js]
- **Email:** donflames@gmail.com

---

💡 _"Technology should solve problems, not create them."_  
Let’s build something amazing together.
