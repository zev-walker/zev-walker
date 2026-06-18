class Vineeth:
    def __init__(self):
        self.name = "Vineeth TP"
        self.location = "Kerala, India"
        self.degree = "B.Tech in ECE, APJ Abdul Kalam Technological University (KTU)"
        self.stack = ["Python", "NumPy", "Pandas", "Scikit-learn", "PyTorch"]
        self.currently_learning = [
            "Deep Learning fundamentals",
            "Kaggle Titanic competition",
            "Multimodal AI & agentic systems"
        ]
        self.fun_fact = (
            "Has terraformed more virtual worlds in Minecraft "
            "than ML models deployed to production — for now."
        )

    def motto(self):
        return (
            "The Universe is under no obligation to make sense to us, "
            "so we build models to understand it anyway."
        )


vineeth = Vineeth()
print(vineeth.motto())
