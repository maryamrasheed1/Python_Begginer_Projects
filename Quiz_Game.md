# QUIZ_GAME_PROJECT
questions = {
    "What is the capital of France?  ":" Paris",
    "What is 3+7=?  ":"10",
    "What is the colour of sky  ?":" Blue",
    "Who discovered Gravity?  ":" Isaac newton",
    "What is the most abundant gas on the earth  ?":" Nitrogen gas",
    "What is the speed of light in Vaccum(in km/s)?  ":" 300000",
    "Who is known as the father of Computers?  ":" Charles Baggage",
    "What is the freezing point of water in Farenhite?  ":" 32",
    "What is the longest river in the world?  ":" nile",
    "What is the currency of japan?  ":" Yen",
    "What is the largest planet in our solar system?  ": " Jupiter",
    "Which planet is known as the Red Planet?  ":" Mars",
}
score=0
for question,answer in questions.items():
    user_answer=input(question+" ")
    if user_answer==answer:
        score+=1
print(f"You got {score}/{len(questions)} correct!")
