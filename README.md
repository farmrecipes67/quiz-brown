# 🎓 Brown Insider Quiz

![Brown Campus](https://drive.google.com/uc?export=view&id=187hZ8DvskIvZbcndJb-nOQbZ5dbQ66MA)

## About This Quiz

Think you know Brown? This insider quiz tests your knowledge of campus traditions, history, famous alumni, hidden gems, and little-known facts that only true insiders would know.

**10 questions • 5 choices each • How well do you really know Brown?**

## How to Use

### Questions
Check out [`questions.js`](./questions.js) for the full quiz with all 10 questions and their multiple-choice options.

### Answers
The answer key with explanations is in [`answers.js`](./answers.js) — no peeking until you're done! 👀

## Quick Start

```javascript
const { questions } = require('./questions');
const { answers } = require('./answers');

// Display a question
console.log(questions[0].question);
Object.entries(questions[0].choices).forEach(([key, val]) => {
  console.log(`  ${key}: ${val}`);
});

// Check answer
console.log(`Correct: ${answers[0].correct} - ${answers[0].explanation}`);
```

## Sample Question

> **When are the Van Wickle Gates traditionally opened fully for students to process through the center?**
> - **A.** Only for Spring Weekend kickoff and the midnight organ recital
> - **B.** At Convocation and Commencement
> - **C.** Every Friday at noon and on snow days
> - **D.** When Brown wins an Ivy League title in any sport
> - **E.** During Family Weekend and Halloween

<details>
<summary>🔍 Click to reveal answer</summary>

**B** — The gates open for incoming students at Convocation and for graduates at Commencement.

</details>

## Quiz Topics Covered

- 🏛️ Campus traditions & rituals
- 📜 University history & founding stories
- 🌟 Famous alumni & their connections
- 🗺️ Hidden spots & insider knowledge
- 🎯 Little-known facts & surprising trivia

---

<div align="center">

*Generated with 💜 by [Papersaurus](https://github.com/farmrecipes67) 🦕*

*Quiz content created using AI • Campus image generated with AI*

</div>

<!-- Open Graph Tags for Social Sharing -->
<!-- og:title: Brown Insider Quiz -->
<!-- og:description: Think you know Brown? Take this 10-question insider quiz covering campus traditions, history, famous alumni, and little-known facts! -->
<!-- og:image: https://drive.google.com/uc?export=view&id=187hZ8DvskIvZbcndJb-nOQbZ5dbQ66MA -->
<!-- og:type: website -->
