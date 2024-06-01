#
# Copyright (C) 2018 DingYi <dingyi139@gmail.com>
#
# This is free software, licensed under the Apache License, Version 2.0 .
#

include $(TOPDIR)/rules.mk

LUCI_TITLE:=Support for WireGuard VPN
LUCI_DEPENDS:=+kmod-wireguard +wireguard-tools
LUCI_PKGARCH:=all

PKG_MAINTAINER:=DingYi <dingyi139@gmail.com>

include ../../luci.mk

# call BuildPackage - OpenWrt buildroot signature
