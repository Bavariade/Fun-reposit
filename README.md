
#!/bin/bash
# pre-commit hook to show a fun GitHub message

python3 - <<END
import rando

fun_messages = [
    "Hey coder! Remember, every bug you fix today is a mysterious feature someone will thank you for tomorrow. Keep pushing!",
    "GitHub adventure time! Commit like nobody's watching, push like everyone is, and may your merges never conflict!",
    "Warning: Excessive coding may cause sudden enlightenment, random genius ideas, or an uncontrollable urge to rename variables!",
    "Life is like a pull request: sometimes it gets rejected, sometimes it gets merged, but every change counts.",
    "Code, coffee, repeat. Your keyboard might get tired, but your imagination never will. Keep those commits coming!"
]

print("\n💻 Fun GitHub Message 💻\n")
print(random.choice(fun_messages))
print("\n🚀 Happy Coding! 🚀")
END
