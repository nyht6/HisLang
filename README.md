
# HisLang - A code language not for her.
# 注：本项目制作目的只是为了嘲讽HerLang这么个玩意

Programming is not a female privilege, boys can also program well.

## Demo

```herlang
function you_can_do_this:
    say "Hello! Everyone's World!"
    say "编程很美，但不属于女权xxn们！"
end

start:
    you_can_do_this
end
```

it outputs:

```
Hello! Everyone's World!
编程很美，但不属于女权xxn们！
```

## How to use

```
Usage: hcp in.herc out.cpp
```

and then you can use `g++` to build an executable file.

```shell
g++ out.cpp -o out
```

then you can run it!

```shell
./out
```

## How to build

```shell
mkdir build
cd build
cmake ..
cmake --build . --config Release
```

or, you can use Microsoft Visual Studio.

## Notes

This project is still under active development and there may be a lot of issues. You can actively submit fixes.
