class AjsalAshraf:
    def __init__(self):
        self.name = "Ajsal Ashraf"
        self.location = "Kollam, Kerala 🇮🇳"
        self.education = [
            "BCA — Data Science, Amrita Vishwa Vidyapeetham (2026)",
            "MCA — AI & Data Science, Amrita Vishwa Vidyapeetham (in progress)",
        ]
        self.email = "ajsalashraf07@gmail.com"
        self.phone = "+91-8848957650"

    def skills(self):
        return {
            "languages": ["Python", "Java", "TypeScript", "JavaScript", "C", "R", "SQL"],
            "ml_ai": ["PyTorch", "TensorFlow", "Scikit-learn", "OpenCV", "Hugging Face", "RAG / vector search"],
            "backend": ["FastAPI", "Flask", "Spring Boot"],
            "frontend": ["React", "Next.js", "Three.js / WebGL", "GSAP"],
            "databases": ["PostgreSQL", "SQLite", "ChromaDB", "Supabase"],
            "computational_biology": ["BLAST", "UniProt", "RCSB PDB", "AutoDock", "PyMOL", "NetworkX", "SciPy (ODE modeling)"],
        }

    def currently_learning(self):
        return [
            "Multiscale computational disease modeling — extending past Parkinson's",
            "AlphaFold-based structural biology",
            "Advanced deep learning architectures",
            "MCA coursework — AI & Data Science",
        ]

    def motto(self):
        return "I like turning messy biological and clinical data into something a system can actually reason over. 🚀"

engineer = AjsalAshraf()
