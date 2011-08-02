# Copyright (C) 2007-2011 LuaDist.
# Created by Peter Kapec
# Redistribution and use of this file is allowed according to the terms of the MIT license.
# For details see the COPYRIGHT file distributed with LuaDist.
# Please note that the package source code is licensed under its own license.

PROJECT(luadate NONE)
CMAKE_MINIMUM_REQUIRED(VERSION 2.6)
INCLUDE(dist.cmake)

# Install all files and documentation
INSTALL_LUA_MODULE(date date.lua)
INSTALL_LUA_EXECUTABLE(mkcalendar mkcalendar.lua)
INSTALL_LUA_EXECUTABLE(mkisocal mkisocal.lua)
INSTALL_DATA(README)
INSTALL_DOC(date.doc.htm date.doc.chm)
