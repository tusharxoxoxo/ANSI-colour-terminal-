# ANSI-colour-terminal-
ANSI colour terminal package for Go


# USAGE
package main
import (
    c "github.com/TreyBastian/colourize"
    "fmt"
)
func main() {fmt.Println(c.Colourize("Hello World!", c.Green, c.Whitebg, c.Bold))}
