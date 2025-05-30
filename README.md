![HerLang](/assets/logo.png)
# HarLang - A code language for her.

Programming is not a male privilege, girls can also program well.

## Demo

```herlang
function you_can_do_this:
    say "Hello! Her World!"
    say "编程很美，也属于你！"
end

start:
    you_can_do_this
end
```

it outputs:

```
Hello! Her World!
编程很美，也属于你！
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