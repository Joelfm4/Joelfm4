<br><br>

[![Typing SVG](https://readme-typing-svg.herokuapp.com/?color=0290FF&size=35&center=true&vCenter=true&width=1000&lines=Hello+there+👋;)](https://git.io/typing-svg)

<br><br>

```
#include <stdio.h>

struct Profile {
    char *languages[7];
    char *frameworks[5];
};

struct Profile joel = {
    .languages = {"C++", "Assembly", "Python", "Haskell", "PowerShell", "TypeScript", NULL},
    .frameworks = {"Django", "Flask", "Tailwind", "Bootstrap", NULL}
};

void DisplayProfile(const char *category, char *arr[]) {
    printf("\n### %s\n", category);
    for(int i = 0; arr[i] != NULL; i++) {
        printf("- %s\n", arr[i]);
    }
}

int main() {
    DisplayProfile("Languages", joel.languages);
    DisplayProfile("Frameworks", joel.frameworks);

    return 0;
}
```

<br><br>

<h4 align="center">
  <a href="https://github.com/Joelfm4?tab=repositories" title="Show Repositories">🔎 Show More 🔍</a>
</h4>
