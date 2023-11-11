package main

import "fmt"

func main() {
	fmt.Println("Welcome to my quiz game!")

	fmt.Printf("\nEnter your name: ")
	var name string

	fmt.Scan(&name)
	fmt.Printf("Hello, %v, welcome to the game!\n", name)
	fmt.Printf("Enter your age: ")
	var age uint
	fmt.Scan(&age)

	if age >= 10 {
		fmt.Println("Yay you're ready to play")
	} else {
		fmt.Println("You can't play")
		return
	}

	score := 0
	num_questions := 2

	fmt.Println("What is better, British soccer or American football?")
	var answer string
	var answer2 string
	fmt.Scan(&answer, &answer2)

	if answer+" "+answer2 == "British soccer" || answer+" "+answer2 == "british soccer" {
		fmt.Println("Correct!")
		score++
	} else {
		fmt.Println("Incorrect!")
	}

	fmt.Println("How many players does soccer have?")
	var players uint
	fmt.Scan(&players)

	if players == 11 {
		fmt.Println("Correct!")
		score++
	} else {
		fmt.Println("Incorrect!")
	}

	fmt.Printf("You scored %v ou of %v!\n", score, num_questions)
	percent := (float64(score) / float64(num_questions)) * 100
	fmt.Printf("You scored: %v%%!", percent)
}
