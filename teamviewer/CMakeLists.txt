# SPDX-License-Identifier: GPL-2.0-or-later

install(
    FILES teamviewer-revpi.list
    DESTINATION ${CMAKE_INSTALL_SYSCONFDIR}/apt/sources.list.d
)

install(
    FILES teamviewer-revpi.gpg
    DESTINATION /usr/share/keyrings
)

install(
    FILES teamviewer-revpi.pref
    DESTINATION ${CMAKE_INSTALL_SYSCONFDIR}/apt/preferences.d
)
