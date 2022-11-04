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