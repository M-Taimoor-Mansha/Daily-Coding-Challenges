# Daily Coding Challenges

A personal repository for building consistency in programming, strengthening problem-solving skills, and practising coding challenges from multiple platforms.

The repository is organised around popular coding practice platforms, with space for solutions, experiments, and learning notes as the collection grows.

---

## About the Project

**Daily Coding Challenges** is intended to be a long-term collection of programming exercises and solutions. It provides a central place to practise algorithmic thinking, learn language features, revisit difficult problems, and track progress through regular coding practice.

The repository currently contains platform-specific placeholder files. Actual challenge solutions and notes can be added over time. The platform names in the repository are organisational starting points, they do not indicate that solutions for those platforms are already included.

## Practice Platforms

The repository currently has placeholders for these platforms:

| Platform / Section | What it is for |
|---|---|
| [AtCoder](https://atcoder.jp/) | Competitive programming contests and algorithmic problems |
| [Codewars](https://www.codewars.com/) | Programming kata and language practice |
| [Codeforces](https://codeforces.com/) | Competitive programming problems and contests |
| [freeCodeCamp](https://www.freecodecamp.org/) | Guided programming exercises and curriculum projects |
| [GeeksforGeeks](https://www.geeksforgeeks.org/) | Data structures, algorithms, and computer science practice |
| [HackerRank](https://www.hackerrank.com/) | Programming challenges and skill assessments |
| [LeetCode](https://leetcode.com/) | Data structures, algorithms, and interview preparation |
| Notes | Explanations, approaches, learnings, and useful references |

These sections are currently empty placeholders. As solutions are added, this README can be updated with language-specific details, problem indexes, and progress information.

## Repository Structure

```text
Daily-Coding-Challenges/
├── AtCoder          # Placeholder for AtCoder solutions
├── CodeWars         # Placeholder for Codewars solutions
├── Codeforces       # Placeholder for Codeforces solutions
├── FreeCodeCamp     # Placeholder for freeCodeCamp exercises
├── GeeksforGeeks    # Placeholder for GeeksforGeeks solutions
├── HackerRank       # Placeholder for HackerRank solutions
├── LeetCode         # Placeholder for LeetCode solutions
├── Notes            # Placeholder for practice notes
├── LICENSE          # MIT License
└── README.md        # Project documentation
```

> The platform entries shown above are currently empty files, not populated folders. They can be converted into directories when adding solution files.

## Languages and Tools

The repository is intended to support coding practice across programming languages. The current repository contents do not yet establish a specific language for the solutions.

When adding a solution, include the language and any runtime requirements in its file or in the relevant platform section. For example, JavaScript solutions can be run with [Node.js](https://nodejs.org/).

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/M-Taimoor-Mansha/Daily-Coding-Challenges.git
```

### 2. Open the project

```bash
cd Daily-Coding-Challenges
code .
```

You can use any code editor. Visual Studio Code is one option.

### 3. Add a solution

Create a directory for the platform and add your solution file. For example, to add a JavaScript LeetCode solution:

```text
Daily-Coding-Challenges/
└── LeetCode/
    └── two-sum.js
```

Example JavaScript solution file:

```javascript
/**
 * Problem: Two Sum
 * Platform: LeetCode
 * Language: JavaScript
 *
 * Add the problem URL and a short explanation when documenting
 * an actual solution.
 */

function twoSum(nums, target) {
  const seen = new Map();

  for (let i = 0; i < nums.length; i++) {
    const complement = target - nums[i];

    if (seen.has(complement)) {
      return [seen.get(complement), i];
    }

    seen.set(nums[i], i);
  }

  return [];
}

module.exports = twoSum;
```

This is an illustrative example of how a solution could be organised, it is not an existing solution currently stored in this repository.

If the file uses CommonJS exports as shown, you can test it with Node.js by importing the function from a separate test file, or adapt the export style to the platform's expected submission format.

## Recommended Solution Documentation

For consistency, consider documenting each challenge with:

- **Problem:** The challenge title.
- **Platform:** Where the problem is hosted.
- **Problem link:** A link to the original statement.
- **Language:** The language used for the solution.
- **Approach:** A brief explanation of the algorithm or reasoning.
- **Complexity:** Time and space complexity, when relevant.
- **Solution:** The implementation.

A simple file naming convention can make solutions easier to find:

```text
platform/
├── problem-name.ext
└── another-problem.ext
```

For example:

```text
LeetCode/
├── two-sum.js
├── valid-parentheses.js
└── best-time-to-buy-and-sell-stock.js
```

Use descriptive filenames and keep each challenge solution focused. If a platform requires a specific function signature or submission format, preserve that format in the solution.

## Goals

- Practise programming consistently.
- Improve logical thinking and problem-solving ability.
- Strengthen understanding of data structures and algorithms.
- Learn and reinforce programming language concepts.
- Prepare for technical interviews and coding assessments.
- Keep a searchable record of completed challenges and lessons learned.

## Progress and Contributions

This is a personal learning repository. Its contents will evolve as new challenges are attempted and documented.

If you want to suggest an improvement:

1. Fork the repository.
2. Create a branch for your change.
3. Add or improve a solution or explanation.
4. Test the code where applicable.
5. Submit a pull request with a description of the change.

When contributing a solution, include the original problem link where possible and avoid publishing copied problem statements or editorial content. Write explanations in your own words.

## License

This project is licensed under the [MIT License](LICENSE).

Copyright (c) 2026 CodewithTaimoor.

## Author

**Muhammad Taimoor Mansha**

- GitHub: [@M-Taimoor-Mansha](https://github.com/M-Taimoor-Mansha)
- LinkedIn: [Muhammad Taimoor Mansha](https://www.linkedin.com/in/muhammad-taimoor-mansha-a09455228)
- Portfolio: [portfolio-rho-two-67.vercel.app](https://portfolio-rho-two-67.vercel.app)
- Email: [taimoorc067@gmail.com](mailto:taimoorc067@gmail.com)

---

If you find this repository useful, you can give it a star and follow along as the collection grows.
