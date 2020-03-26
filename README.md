# class-in-class

class compyotr:

    def __init__(self,name,num):
        self.name = name
        self.num = num

    def show(self):
        print(self.name,self.num)

    class hp:

        def __init__(self):
            self.name = 'hp'
            self.ram = '8gb'
            self.cpu = 'i5'
            self.hard = '1 tb'

        def printmino1(self):
            print(self.name, self.ram, self.cpu, self.hard)

    class dell:
        def __init__(self):
            self.name = 'dell'
            self.ram = '4gb'
            self.cpu = 'i3'
            self.hard = '1 tb'

        def printmino2(self):
            print(self.name, self.ram, self.cpu, self.hard)

    class asser:
        def __init__(self):
            self.name = 'asser'
            self.ram = '6 gb'
            self.cpu = 'i5'
            self.hard = '500 gb'
        def printmino3(self):
            print(self.name,self.ram,self.cpu,self.hard)

    class condor:
        def __init__(self):
            self.name = 'condor'
            self.ram = '2 gb'
            self.cpu = 'i3'
            self.hard = '200 gb'
        def printmino4(self):
            print(self.name,self.ram,self.cpu,self.hard)


pos = compyotr.hp()
pos.printmino1()

pos2 = compyotr.dell()
pos2.printmino2()

pos3 = compyotr.asser()
pos3.printmino3()

pos4 = compyotr.condor()
pos4.printmino4()
