TARGET = iphone:clang:latest:13.0
ARCHS = arm64
INSTALL_TARGET_PROCESSES = YouTube
FINALPACKAGE = 1

include $(THEOS)/makefiles/common.mk

TWEAK_NAME = YoutubeSpeed

YoutubeSpeed_FILES = Tweak.xm
YoutubeSpeed_CFLAGS = -fobjc-arc

include $(THEOS_MAKE_PATH)/tweak.mk
