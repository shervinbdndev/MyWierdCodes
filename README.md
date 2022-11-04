<h1><b>چگونه به وحشیانه ترین حالت یه استریگ رو نمایش بدیم</b></h1>
<div align='left'>
<h3><b>How to Display String in Wildest Way<h3>
<h6><b>Python 3.11.0</b><h6>
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