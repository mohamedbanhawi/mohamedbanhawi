### Hi there 👋


[![Google Scholar][1]][2]
[![LinkedIn][3]][4]

[1]:  https://img.shields.io/badge/-GoogleScholar-blue?style=social&logo=google
[2]:  https://scholar.google.com/citations?user=nWCJ_EQAAAAJ&hl=en "My Google Scholar Profile"
[3]:  https://img.shields.io/badge/-Linkedin-blue?style=social&logo=linkedin
[4]:  https://www.linkedin.com/in/mohamedelbanhawi/ "My LinkedIn Profile"



```proto
message AboutMe {
  option (api_version) = 32;
  option (created_at) = {
    year: 1991,
    month: MARCH,
    day: 15
  };
  option (kind) = HUMAN;
  option (metadata) = {
    name: "Mohamed Elbanhawi",
    from: "🇪🇬",
    live_in: "🇦🇺",
    languages: [ Python, GO, C, C++, Matlab ],
    hobbies: ["📖", "🏍️", "🧙‍♂️", "🏋️"]
  };
}
```
