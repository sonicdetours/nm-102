# Copyright (c) 2015 Sonic Detours. All Rights Reserved.
#
# This program is free software: you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation, either version 3 of the License, or
# (at your option) any later version.
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
# You should have received a copy of the GNU General Public License
# along with this program.  If not, see <http://www.gnu.org/licenses/>.

VERSION        = 0.01
MCU_NAME       = 328
TARGET         = nm102
PACKAGES       = avrlib avrlib/devices nm102
RESOURCES      = nm102/resources
# EXTRA_DEFINES  = -DDISABLE_DEFAULT_UART_RX_ISR

LOCK           = 2f
LFUSE          = ff
HFUSE          = d7
EFUSE          = fd

include avrlib/makefile.mk

include $(DEP_FILE)
