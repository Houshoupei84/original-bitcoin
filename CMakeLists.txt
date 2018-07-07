cmake_minimum_required(VERSION 3.11)
project(original_bitcoin)

set(CMAKE_CXX_STANDARD 11)

INCLUDE_DIRECTORIES(/usr/local/lib/wx/include/osx_cocoa-unicode-3.1)

include_directories(src)

add_executable(original_bitcoin
        src/rc/addressbook16.bmp
        src/rc/addressbook16mask.bmp
        src/rc/addressbook20.bmp
        src/rc/addressbook20mask.bmp
        src/rc/bitcoin.ico
        src/rc/check.ico
        src/rc/send16.bmp
        src/rc/send16mask.bmp
        src/rc/send16masknoshadow.bmp
        src/rc/send20.bmp
        src/rc/send20mask.bmp
        src/base58.h
        src/bignum.h
        src/db.cpp
        src/db.h
        src/headers.h
        src/irc.cpp
        src/irc.h
        src/key.h
        src/license.txt
        src/main.cpp
        src/main.h
        src/makefile
        src/makefile.vc
        src/market.cpp
        src/market.h
        src/net.cpp
        src/net.h
        src/readme.txt
        src/script.cpp
        src/script.h
        src/serialize.h
        src/sha.cpp
        src/sha.h
        src/ui.cpp
        src/ui.h
        src/ui.rc
        src/uibase.cpp
        src/uibase.h
        src/uint256.h
        src/uiproject.fbp
        src/util.cpp
        src/util.h
        bitcoin.exe
        libeay32.dll
        license.txt
        mingwm10.dll
        README.md
        readme.txt)
