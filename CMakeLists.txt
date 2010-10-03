# Copyright (C) 2007-2009 LuaDist.
# Created by Peter Kapec
# Redistribution and use of this file is allowed according to the terms of the MIT license.
# For details see the COPYRIGHT file distributed with LuaDist.
# Please note that the package source code is licensed under its own license.

PROJECT(luadate NONE)
CMAKE_MINIMUM_REQUIRED(VERSION 2.6)
INCLUDE(dist.cmake)

# Install all files and documentation
INSTALL (FILES date.lua DESTINATION ${INSTALL_LMOD})
INSTALL (FILES mkcalendar.lua mkisocal.lua DESTINATION ${INSTALL_BIN})
INSTALL (FILES README DESTINATION ${INSTALL_DATA})
INSTALL (FILES date.doc.htm date.doc.chm DESTINATION ${INSTALL_DOC})
