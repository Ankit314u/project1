# Emoji Mood Responder

mood_responses = {
    "happy": ("😊", "That's awesome! Keep smiling!"),
    "sad": ("😢", "It's okay to feel sad sometimes. Tomorrow is a new day."),
    "angry": ("😠", "Take a deep breath. Things will get better."),
    "excited": ("🤩", "Yay! Enjoy the excitement!"),
    "tired": ("😴", "Get some rest. You deserve it!"),
    "nervous": ("😬", "Just relax, you've got this!"),
    "bored": ("😐", "Maybe try something new today?")
}

user_mood = input("How are you feeling today? ").lower()

if user_mood in mood_responses:
    emoji, message = mood_responses[user_mood]
    print(f"{emoji} {message}")
else:
    print("🤔 I'm not sure how to respond to that, but I hope you have a good day!")
