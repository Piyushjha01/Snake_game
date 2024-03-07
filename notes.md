# learned Inheritence in python for example class animal
class Animal :
    def __init__(self):
      self.num_eyes = 2
    def breathe(self):
        print("Inhale, exhale.")

class Fish(Animal):
    def __init__(self):
        super().__init__()
    def swim(self):
    print("moving in water.")


# to overwrite the function defined in parent class
    def breathe(self):
        super().__init()
        print("overwrite")
nemo = Fish()
nemo.swim()
nemo.breathe()
print(nemo.num_eyes)


