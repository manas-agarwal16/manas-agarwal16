class GitHubProfile {
  constructor() {
    this.username = "manas-agarwal16";
    this.name = "Manas Agarwal";
    this.bio = "Fullstack Developer | DSA Enthusiast";
    this.achievements = [
      "Knight at LeetCode",
      "Pupil at Codeforces",
      "3-Star at CodeChef"
    ];
    this.location = "Ghaziabad, Uttar Pradesh 🌍";
    this.githubUrl = "https://github.com/manas-agarwal16";
    this.skills = [
      "Node.js",
      "React.js",
      "MongoDB",
      "SQL",
      "Docker",
      "DSA"
    ];
    this.interests = [
      "Innovative Projects",
      "Competitive Programming",
      "Data Structures and Algorithms"
    ];
  }

  introduce() {
    console.log(`👋 Hello, world! I'm ${this.name}.`);
    console.log(`${this.bio}`);
    console.log(`🌍 Current location: ${this.location}`);
    console.log(`🔗 Check out my GitHub: ${this.githubUrl}`);
    console.log("\n💡 Achievements:");
    this.achievements.forEach((achievement) => {
      console.log(`   - ${achievement}`);
    });
    console.log("\n💻 Skills I'm proud of:");
    this.skills.forEach((skill) => {
      console.log(`   - ${skill}`);
    });
    console.log("\n🚀 Things I love to explore:");
    this.interests.forEach((interest) => {
      console.log(`   - ${interest}`);
    });
  }
}


const profile = new GitHubProfile();
profile.introduce();
