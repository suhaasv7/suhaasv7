<div align="center">

# Suhaas V

**Full Stack Developer**

Building websites that look good and feel easy to use.

[GitHub](https://github.com/suhaasv7) · [LinkedIn](https://www.linkedin.com/in/suhaasv7/) · [Twitter](https://twitter.com/suhaas_v10) · [Email](mailto:suhaasvijay7@gmail.com)

</div>

---

## About

I'm a web developer, always learning and adapting to new technologies. My passion lies in creating websites that are both visually appealing and user-friendly. Staying updated with the latest trends in web technology is a commitment I've made to ensure continuous growth.

## Learning & languages

| Language | Where I am |
| :--- | :--- |
| JavaScript | Moderate + Learning |
| HTML | Proficient |
| CSS | Proficient |
| Java | Beginner |
| C | Learning |

## Stack & tools

**Web development**

![Next.js](https://img.shields.io/badge/Next.js-161b22?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-161b22?style=flat-square&logo=react&logoColor=61DAFB)
![HTML5](https://img.shields.io/badge/HTML5-161b22?style=flat-square&logo=html5&logoColor=E34F26)
![CSS3](https://img.shields.io/badge/CSS3-161b22?style=flat-square&logo=css&logoColor=1572B6)
![JavaScript](https://img.shields.io/badge/JavaScript-161b22?style=flat-square&logo=javascript&logoColor=F7DF1E)
![TypeScript](https://img.shields.io/badge/TypeScript-161b22?style=flat-square&logo=typescript&logoColor=3178C6)
![Node.js](https://img.shields.io/badge/Node.js-161b22?style=flat-square&logo=nodedotjs&logoColor=339933)
![Express](https://img.shields.io/badge/Express-161b22?style=flat-square&logo=express&logoColor=white)

**Design & workflow**

![Figma](https://img.shields.io/badge/Figma-161b22?style=flat-square&logo=figma&logoColor=F24E1E)
![VS Code](https://img.shields.io/badge/VS%20Code-161b22?style=flat-square&logo=visualstudiocode&logoColor=007ACC)
![Android Studio](https://img.shields.io/badge/Android%20Studio-161b22?style=flat-square&logo=androidstudio&logoColor=3DDC84)
![npm](https://img.shields.io/badge/npm-161b22?style=flat-square&logo=npm&logoColor=CB3837)
![Git](https://img.shields.io/badge/Git-161b22?style=flat-square&logo=git&logoColor=F05032)
![GitHub](https://img.shields.io/badge/GitHub-161b22?style=flat-square&logo=github&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-161b22?style=flat-square&logo=vite&logoColor=646CFF)

<details>
<summary>A little about me, in React</summary>

```javascript
import React, { useState } from "react";

const SoftwareEngineer = () => {
  const [state] = useState({
    name: "Suhaas V",
    role: "Full Stack Developer",
    languagesKnown: [
      { language: "JavaScript", status: "Moderate + Learning" },
      { language: "Html", status: "Proficient" },
      { language: "Css", status: "Proficient" },
      { language: "Java", status: "Beginner" },
      { language: "C", status: "Learning" },
    ],
  });

  const sayHi = () => {
    console.log("Thanks for dropping by, hope you find some of my work interesting.");
  };

  const renderLanguageSkills = () => {
    return state.languagesKnown.map((lang) => (
      <li key={lang.language}>
        {lang.language} - {lang.status}
      </li>
    ));
  };

  return (
    <div>
      <h1>Hello, I'm {state.name}!</h1>
      <p>I am a {state.role}.</p>
      <p>I know these programming languages:</p>
      <ul>{renderLanguageSkills()}</ul>
      <button onClick={sayHi}>Say Hi!</button>
    </div>
  );
};

export default SoftwareEngineer;
```

</details>

## GitHub activity

<details>
<summary>Stats & most-used languages</summary>

![Suhaas's GitHub stats](https://github-readme-stats.vercel.app/api?username=suhaasv7&show_icons=true&theme=github_dark&hide_border=true)

![Most-used languages](https://github-readme-stats.vercel.app/api/top-langs/?username=suhaasv7&layout=compact&theme=github_dark&hide_border=true)

</details>

---

## Get in touch

- [Twitter — @suhaas_v10](https://twitter.com/suhaas_v10)
- [LinkedIn — suhaasv7](https://www.linkedin.com/in/suhaasv7/)
- [Email — suhaasvijay7@gmail.com](mailto:suhaasvijay7@gmail.com)

Thanks for dropping by. Hope you find some of my work interesting.
