include $(TOPDIR)/rules.mk

LUCI_TITLE:=栋仔个性化主题
LUCI_DEPENDS:=
PKG_VERSION:=1.0
PKG_RELEASE:=1

include $(INCLUDE_DIR)/package.mk

define Package/luci-theme-dongzhai
  $(call Package/luci/webtemplate)
  TITLE:=栋仔个性化主题
  DEPENDS:=+luci-compat
endef

define Package/luci-theme-dongzhai/description
  基于Design主题修改的栋仔个性化主题
endef

define Build/Configure
endef

define Build/Compile
endef

define Package/luci-theme-dongzhai/install
	$(INSTALL_DIR) $(1)/www/luci-static/dongzhai
	$(CP) ./files/* $(1)/www/luci-static/dongzhai/
endef

$(eval $(call BuildPackage,luci-theme-dongzhai))
