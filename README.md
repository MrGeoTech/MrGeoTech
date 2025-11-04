<h1 align="center">Welcome to my GitHub!</h1>

```zig
pub const Bio = struct {
    
    pub const KnownLanguage = enum(u8) {
        c,
        java,
        kotlin,
        vhdl,
        verilog,
        zig,
        python
    };

    name: []const u8 = "Isaac George",
    username: []const u8 = "MrGeoTech",
    location: []u8 = "United States",
    occupation: ?[]u8 = "Student",
    institution: ?[]u8 = "NDSU 🟩🦬🟨",
    favoriteLanguage: KnownLanguage = .zig,
    
    age: u8 = 20,

    interests: [][]const u8 = .{
        "Computing History",
        "Performance Optimization",
        "VLSI Design",
        "Programming",
        "Linux",
        "Video Games",
        "Music",
    },

    linked_in: []const u8 = "https://www.linkedin.com/in/isaac-george-tech/",
};
```

<h2 align="center"><br/>Metrics</h3>

<img src="./metrics.terminal.svg" alt="MrGeoTech's Statistics">

<h2 align="center"><br/>Statistics</h3>

<h3 align="center">Profile views</h3>
<h4 align="center">
<img src="https://profile-counter.glitch.me/{MrGeoTech}/count.svg" alt="My GitHub views counter" />
</h4>

<h3 align="center">Other</h3>
<h4 align="center">
<img src="https://github-readme-stats.vercel.app/api?username=MrGeoTech&show_icons=true&theme=tokyonight" alt="My stats">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MrGeoTech&langs_count=10&theme=tokyonight&layout=compact" alt="My top languages">
</h4>
<!--
**MrGeoTech/MrGeoTech** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
