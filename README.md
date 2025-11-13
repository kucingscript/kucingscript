# 🐱 kucingscript

```javascript
const catto = {
  name: "kucingscript",
  species: "Felis Programmicus",
  habitat: "Indonesia 🇮🇩",
  
  personality: {
	earlyBird: "awake before the sun, productive before breakfast",
	focused: "easily distracted",
  	skilled: "at Googling",
  	experienced: "in creating bugs"
  },
  
  abilities: [
	"Debugging before birds start chirping",
	"Committing at 8 AM, regretting at 8 PM",
	"Nine lives, zero documentation",
	"Copy-pasting with confidence"
  ],
  
  currentMood: () => {
    const hour = new Date().getHours();
    return hour >= 5 && hour < 12 ? "😺 Peak Performance" : "😴 Recharging...";
  },
  
  secretWeapon: "Google, Prayer, and Luck",
  
  lifeGoal: "To understand my own code after 2 weeks"
};

console.log("Meow! 🐱");
```

---
