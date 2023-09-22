# SPDX-License-Identifier: GPL-2.0-or-later

install(
    FILES revpi.sources
    DESTINATION ${CMAKE_INSTALL_SYSCONFDIR}/apt/sources.list.d/
)

install(
    FILES revpi.gpg
    DESTINATION ${CMAKE_INSTALL_SYSCONFDIR}/apt/trusted.gpg.d/
)
