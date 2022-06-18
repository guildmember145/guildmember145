package main

import (
	"fmt"
)

type Bio map[string]string

func main() {
	for k, v := range GetBio() {
		fmt.Printf("%+v: %+v\n", k, v)
	}
}

func GetBio() Bio {
	return Bio{
		"- ⚡ Quick bio:":                    "A kind of -knowledge lover! foodLover-gamer-coder-programmer-catLover-",
		"- 🔭 I’m currently working on":      " Software Developer",
		"- 🌱 I’m currently learning":        "I will never stop learning(Personal goal)",
		"- 👯 I’m looking to collaborate on": "Python, Rust,Cibersecurity projects",
		"- 🤔 I’m looking for help with":     "Anything related to what I am currently learning 😅",
		"- 💬 Ask me about":                  "Python, Rust, WASM, SQL, Software Design & Architecture, Love Cybersecurity!",
		"- 📫 How to reach me:":              "https://github.com/guildmember145",
         https://github-readme-stats.vercel.app/api?username=guildmember145
	}
}
