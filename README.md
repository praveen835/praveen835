class PraveenkumarBalakrishnan:
    def __init__(self):
        self.name         = "Praveenkumar Balakrishnan"
        self.location     = "Coimbatore, India 🇮🇳"
        self.degree       = "B.Tech — Artificial Intelligence & Data Science (2023–2027)"
        self.college      = "KGISL Institute of Technology | CGPA: 8.93"
        self.email        = "praveenwinner143@gmail.com"

        self.stack = {
            "languages"   : ["Python", "Java", "HTML", "CSS"],
            "data_science": ["NumPy", "Pandas", "Matplotlib", "Seaborn", "Scikit-learn"],
            "ml"          : ["Linear Regression", "StandardScaler", "One-Hot Encoding"],
            "web"         : ["Bootstrap", "Responsive Design", "Gradio"],
            "tools"       : ["VS Code", "Google Colab", "Git", "GitHub", "Joblib"],
        }

        self.currently_learning = [
            "Deep Learning & Neural Networks",
            "MLOps & Model Deployment",
            "SQL & Database Management",
            "FastAPI for ML APIs",
        ]

        self.fun_fact = "I built a salary predictor with R² ≈ 0.89 and deployed it via Gradio! 🎯"

    def motto(self) -> str:
        return "Code it. Model it. Deploy it. 🚀"

me = PraveenkumarBalakrishnan()
print(me.motto())
