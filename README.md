<div align="center">

# 👋 Hi, I'm s0r4n9n

<br/>

[![X](https://img.shields.io/badge/Follow-%40s0r4n9n-1DA1F2?style=for-the-badge&logo=x&logoColor=white)](https://x.com/s0r4n9n)
[![Followers](https://badgen.org/img/zenn/s0r4n9n/followers?style=for-the-badge)](https://zenn.dev/s0r4n9n)

</div>

---

### about_me.py

```python
class SelfIntroduction:
    def __init__(self):
        self.name = "s0r4n9n"
        self.role = "Machine Learning Engineer"
        self.location = "Japan 🇯🇵"
        
    def current_focus(self):
        return {
            "professional": [
                "Building ML/AI solutions for production",
                "Deep learning model optimization",
                "Real-world AI applications"
            ],
            "personal": [
                "Minecraft plugin development (Java/Kotlin)",
                "ML experiments & research",
                "Documenting my learning journey"
            ]
        }
    
    def tech_stack(self):
        return {
            "languages": ["Python", "Java", "Kotlin"],
            "ml_frameworks": ["PyTorch", "TensorFlow", "scikit-learn", "Hugging Face"],
            "tools": ["Neovim", "Nix", "Git", "Jujutsu", "Linux", "Docker"]
        }
    
    def interests(self):
        return [
            "🧠 Deep Learning & Neural Architecture",
            "🔍 NLP & Computer Vision",
            "⚡ Model Optimization & MLOps",
        ]
    
    def say_hi(self):
        print("Thanks for visiting! Let's build something interesting together! 🤝")

me = SelfIntroduction()
me.say_hi()
```
