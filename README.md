### Hello there š

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
    me := SoftwareEngineer{role: "Platform Engineer"}
    me.sayHi()
}

```

<!--
**CalebmKopp/calebmkopp** is a āØ _special_ āØ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- š­ Iām currently working on ...
- š± Iām currently learning ...
- šÆ Iām looking to collaborate on ...
- š¤ Iām looking for help with ...
- š¬ Ask me about ...
- š« How to reach me: ...
- š Pronouns: ...
- ā” Fun fact: ...
-->
