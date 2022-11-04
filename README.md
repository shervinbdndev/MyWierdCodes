<h1><b>چگونه به وحشیانه ترین حالت یه استرینگ رو نمایش بدیم</b></h1>
<h3><b>به عبارتی دیگر: چگونه مثل سیشارپ، پایتون کد بزنیم</b></h3>
<div align='left'>
<h4><b>How to Display String in Wildest Way</b><h4>
<h4>Other Meaning: How to code <b>Python</b> Like <b>(C#)</b><h4>
<h6>Python 3.11.0<h6>

<h4><h4>
<br>

```py

import sys
from overrides.overrides import override
from typing import (Literal , Union , Self)


class Print:
    def __init__(self: Self, /, _input: str) -> Union[Literal[None] , Self]:
        super(Print, self).__init__()
        self.__s = _input
        
    def __str__(self: Self) -> str:
        return str(sys.stdout.write(self.__s))
    


class PrintOutput(Print):
    @override
    def __str__(self: Self) -> str:
        return 'Hello World!'
    


if (__name__ == '__main__'):
    my_var = PrintOutput(not __debug__)
    print(my_var)

```

</div>
<br>


<h1><b>پروژه ساخت کلاس انسان</b></h1>
<h3><b>یه پروژه ساده و راحت جهت نشون دادن شئ گرایی تو پایتون</b></h3>
<div align='left'>
<h4><b>A Simple Project to Show OOP(Object Oriented Programming) in Python</b><h4>
<h6>Python 3.11.0<h6>

<h4><h4>
<br>

```py

from typing import (
    Literal ,
    Union ,
    Self ,
    Dict,
    Any ,
)




def main() -> Literal[None]:
    # Creating Instance & Initializing                                    ایجاد نمونه و مقداردهی
    
    h1: Human = Human(name='shervin' , family='badanara' , age=19 , code=5180195225)
    
    # Printing Properities & Behavior Of the above Instance               نمایش خصوصیت ها و رفتارهای نمونه بالا
    print(h1)
    print(h1.name)
    print(h1.family)
    print(h1.age)
    print(h1.code)
    print(h1.UserData())




class DNA:
    _meta_data: Dict[str,str] = {}



class Human(DNA):
    def __init__(self: Self, *, name: str, family: str, age: int, code: int) -> Union[Literal[None], Self]:
        super(Human, self).__init__()
        self.__name = self._meta_data['name'] = name
        self.__family = self._meta_data['family'] = family
        self.__age = self._meta_data['age'] = age
        self.__code = self._meta_data['code'] = code
        
    def __str__(self: Self) -> str:
        return f'{self.name} {self.family}'
        
    @property
    def name(self: Self):
        return self.__name
    
    @property
    def family(self: Self):
        return self.__family
    
    @property
    def age(self: Self):
        return self.__age
    
    @property
    def code(self: Self):
        return self.__code
    
    def UserData(self: Self) -> Any:
        return self._meta_data
    

    


if (__name__ == '__main__'):
    main()


```

</div>