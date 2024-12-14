## <div style="text-align: center;">
  <img width="45" alt="about" src="https://icons-for-free.com/iff/png/512/design+development+facebook+framework+mobile+react+icon-1320165723839064798.png" style="margin-top: 10px;">
</div>

### More about me
```javascript
const abdallah = {
  about: {
    name: "Abdallah Hossam",
    company: "Details Digital",
    role: "Frontend Developer",
  },
  tech: ["Next.js", "React", "Typescript", "Node.js"],
  links: {
    linkedin: "https://www.linkedin.com/in/abdallahhossam/",
  },
  funFacts: [
    "Creating bugs since 2023",
    "Believes CSS can be both a blessing and a curse, depending on the day.",
    "Will refactor the same component 10 times because it just has to be *perfect*.",
  ],
};

console.log("👋 Meet Abdallah!");
console.log(`🚀 Currently working as a ${abdallah.about.role} at ${abdallah.about.company}`);
console.log("💻 Favorite Tech Stack:", abdallah.tech);
console.log("🔗 Connect on LinkedIn:", abdallah.links.linkedin);
console.log("😂 Fun facts about me:");
abdallah.funFacts.forEach((fact, index) => console.log(`${index + 1}. ${fact}`));

setTimeout(() => console.log("🥳 Did someone say 'deploy'? Let's hope it works on the first try!"), 3000);
setTimeout(() => console.log("🤔 Or is it 'works on my machine'?"), 6000);
