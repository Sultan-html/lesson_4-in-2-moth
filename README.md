""""первое"""
# """ Объектно ориентированное программирование """

# Full_name = 'Ниязалиев Султан'
# FullName = 'Ниязалиев Султан'
# print(Full_name.count('f'))

# def add_function():
#     pass

# class Car: #шаблон или же чертеж 
#     def __init__(self, model, marka, color): #__init__ (магический метод) конструктор
#         'Атрибут объекта'
#         self.model = model # self (ссылка на текущий объект)
#         self.marka = marka
#         self.color = color
#         'Атрибут класса'
#         self.bak = 10
#         self.is_start = False
        
#     def info(self):
#         print(f'Марка машины-{self.marka}, модель-{self.model}, цвет-{self.color}')
        
#     def start(self):
#         if self.bak > 0:
#             self.is_start = True
#             print(f'Машина {self.marka} - {self.model} заведена')
#         else:
#             print(f'Машина {self.marka} - {self.model} нет топлива')
            
#     def stop(self):
#         self.is_start = False
#         print(f'Машина {self.marka} - {self.model} заглушено')
        
#     def drive(self, city):
#         if self.is_start == True:
#             print(f"машинa -{self.marka} - {self.model} едет в {city}")
#         else:
#             print(f"Машина {self.marka} - {self.model} не заведена!")

# bmw = Car('m5 f90', 'BMW', 'black')
# bmw.info()
# bmw.start()
# # bmw.stop()
# bmw.drive('Катар')

# """ Создать класс (Book).Передать параметры (avtor, book_name, year). Создать метод info. Вызвать переданный аргумент """
    

"""второе, (не до конца код)"""
# import datetime
# class car:
#     def init(self , miliage , make , year ):
#         self.__miliage=miliage
#         self._make=make
#         self.year=year
#     def diss_info(self):
#         print(f'марка-{self._make}, год-{self.year}')
    

#     def _calculate_age(self):
#         ccurent=datetime.datetime.now().year
        # return ccurent- self.__miliage
"""тертье"""
# "Полиморфизм"

# num1 = 1
# num2 = 2 

# print(num1 + num2)

# string1 = "Hello, "
# string2 = "Geeks"

# print(string1 + string2)

# print(len("ООП - программирование"))

# print(len(['Python', 'Java', "C#", "Scala", 'Ruby']))

# print(len({"Python": "Django", "Js": 'React' }))


# class Cat:
#     def __init__(self, name, preferences):
#         self.name = name 
#         self.preferences = preferences
        
#     def info(self):
#         print(f'Я кот. Меня зовут {self.name}. Мне {self.preferences} года')
        
#     def make_sound(self):
#         print("Мяу!")
        
        
# class Dog:
#     def __init__(self, name, preferences):
#         self.name = name 
#         self.preferences = preferences
        
#     def info(self, color):
#         print(f'Я собака. Меня зовут {self.name}. Мне {self.preferences} года, цвет {color}')
        
#     def make_sound(self):
#         print("Гаф!")
        
# cat = Cat("Васька", 2)
# dog = Dog('Мухтар', 3)

# # for animal in (cat, dog):
# #     animal.make_sound()
# #     animal.info("Черный")
# #     animal.make_sound()        
    

# class PaymentMethod:
#     def pay(self, amount):
#         pass 

# class CreditCard(PaymentMethod):
#     def pay(self, amount):
#         return f'Сумма {amount}, оплачиватеся по кредитной карте'
    
# class PayPal(PaymentMethod):
#     def pay(self, amount):
#         return f'Сумма {amount}, оплачивается по PayPal'
    
# class BankTransfer(PaymentMethod):
#     def pay(self, amount):
#         return f'Сумма {amount}, оплачивается по банковскому переводу'

# payments  = [CreditCard(), PayPal(), BankTransfer()]

# for payment in payments:
#     print(payment.pay(100))

