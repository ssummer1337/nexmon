all: Android.mk
	$(NDK_ROOT)/ndk-build NDK_APPLICATION_MK=`pwd`/Application.mk NDK_APP_OUT=. TARGET_PLATFORM=android-21
	cp libs/armeabi/* ../../../libs/armeabi

clean:
	rm -Rf libs
	rm -Rf local
