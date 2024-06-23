class MyProfile:
    def __init__(self, name, profession):
        self.name = name
        self.profession = profession
    
    def describe(self):
        print(f"print('Hello, World! My name is {self.name}. I am a {self.profession}.')")
        print(f"print('Learning is a lifelong journey, and I'm committed to continuous growth.')")
        
my_profile = MyProfile("Gulmira", "Backend developer")
my_profile.describe()
