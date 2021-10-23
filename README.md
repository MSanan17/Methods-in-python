# Methods-in-python
class emp:
    no = 12
    def details(self):
        return f"name is {self.name} and salary is {self.salary}"
    def __init__(self,aname,asalary):
        self.name = aname
        self.salary = asalary

    @classmethod
    def change(cls,newleaves):
        cls.no = newleaves

harry = emp("harry",155)
harry.change(89)
print(harry.no)
