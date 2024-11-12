{
 "cells": [
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "0335446b-0c3c-4da4-b7fd-e776c27f2bcd",
   "metadata": {},
   "outputs": [],
   "source": [
    "questions = {\n",
    "    \"What is the capital of France?  \":\" Paris\",\n",
    "    \"What is 3+7=?  \":\"10\",\n",
    "    \"What is the colour of sky  ?\":\" Blue\",\n",
    "    \"Who discovered Gravity?  \":\" Isaac newton\",\n",
    "    \"What is the most abundant gas on the earth  ?\":\" Nitrogen gas\",\n",
    "    \"What is the speed of light in Vaccum(in km/s)?  \":\" 300000\",\n",
    "    \"Who is known as the father of Computers?  \":\" Charles Baggage\",\n",
    "    \"What is the freezing point of water in Farenhite?  \":\" 32\",\n",
    "    \"What is the longest river in the world?  \":\" nile\",\n",
    "    \"What is the currency of japan?  \":\" Yen\",\n",
    "    \"What is the largest planet in our solar system?  \": \" Jupiter\",\n",
    "    \"Which planet is known as the Red Planet?  \":\" Mars\",\n",
    "}\n",
    "score=0\n",
    "for question,answer in questions.items():\n",
    "    user_answer=input(question+\" \")\n",
    "    if user_answer==answer:\n",
    "        score+=1\n",
    "print(f\"You got {score}/{len(questions)} correct!\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "383c2023-6461-482d-910c-ef3a5a4c331d",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.12.7"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
