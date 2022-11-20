### Hello there 👋

```go
#!/usr/bin/go

import (
    "fmt"
)
type SoftwareEngineer struct {
    name            string  `default:"Caleb Kopp"`
    role            string  `default:"Software Engineer"`
    stateLivingIn   string  `default:"Minnesota"`
}
func (engineer *SoftwareEngineer) sayHi() {
    fmt.Println("Hello! I am", engineer.name, " thanks for stopping by!")
}
func main () {
    me := SoftwareEngineer{role: "Sr. Platform Engineer"}
    me.sayHi()
}

```

<!--
**CalebmKopp/calebmkopp** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
