#############################################################################
# Makefile for building: libUtil.a
# Generated by qmake (2.01a) (Qt 4.5.1) on: Tue Apr 15 16:23:11 2014
# Project:  Util.pro
# Template: lib
# Command: /usr/bin/qmake -spec /usr/local/Qt4.5/mkspecs/macx-g++ -macx -o Makefile Util.pro
#############################################################################

####### Compiler, tools and options

CC            = gcc
CXX           = g++
DEFINES       = -DQS_LOG_LINE_NUMBERS -DQT_NO_DEBUG -DQT_NO_KEYWORDS -DQT_XML_LIB -DQT_OPENGL_LIB -DQT_GUI_LIB -DQT_CORE_LIB -DQT_SHARED
CFLAGS        = -pipe -Os -fPIC -Wall -W $(DEFINES)
CXXFLAGS      = -pipe -O0 -g -Os -fPIC -Wall -W $(DEFINES)
INCPATH       = -I/usr/local/Qt4.5/mkspecs/macx-g++ -I. -I/Library/Frameworks/QtCore.framework/Versions/4/Headers -I/usr/include/QtCore -I/Library/Frameworks/QtGui.framework/Versions/4/Headers -I/usr/include/QtGui -I/Library/Frameworks/QtOpenGL.framework/Versions/4/Headers -I/usr/include/QtOpenGL -I/Library/Frameworks/QtXml.framework/Versions/4/Headers -I/usr/include/QtXml -I/usr/include -I/usr/local/include/openbabel-2.0 -I$(DEV)/Boost/include -I/Library/Frameworks/QGLViewer.framework/Versions/2/Headers -I../../../../OpenMesh-2.4/src -I$(DEV)/extlib/include -I/usr/local/include -I../../src -I../../build -I. -I/System/Library/Frameworks/OpenGL.framework/Versions/A/Headers -I/System/Library/Frameworks/AGL.framework/Headers -I../../build -I../../build -F/Library/Frameworks
AR            = ar cq
RANLIB        = ranlib -s
QMAKE         = /usr/bin/qmake
TAR           = tar -cf
COMPRESS      = gzip -9f
COPY          = cp -f
SED           = sed
COPY_FILE     = cp -f
COPY_DIR      = cp -f -R
INSTALL_FILE  = $(COPY_FILE)
INSTALL_DIR   = $(COPY_DIR)
INSTALL_PROGRAM = $(COPY_FILE)
DEL_FILE      = rm -f
SYMLINK       = ln -sf
DEL_DIR       = rmdir
MOVE          = mv -f
CHK_DIR_EXISTS= test -d
MKDIR         = mkdir -p
export MACOSX_DEPLOYMENT_TARGET = 10.3

####### Output directory

OBJECTS_DIR   = ../../build/

####### Files

SOURCES       = Align.C \
		EulerAngles.C \
		Function.C \
		Matrix.C \
		Preferences.C \
		qcprot.C \
		ScanDirectory.C \
		SetButtonColor.C \
		Task.C \
		QMsgBox.C \
		QsLogDest.C \
		QsLog.C \
		QsDebugOutput.C ../../build/moc_Task.cpp \
		../../build/moc_QMsgBox.cpp
OBJECTS       = ../../build/Align.o \
		../../build/EulerAngles.o \
		../../build/Function.o \
		../../build/Matrix.o \
		../../build/Preferences.o \
		../../build/qcprot.o \
		../../build/ScanDirectory.o \
		../../build/SetButtonColor.o \
		../../build/Task.o \
		../../build/QMsgBox.o \
		../../build/QsLogDest.o \
		../../build/QsLog.o \
		../../build/QsDebugOutput.o \
		../../build/moc_Task.o \
		../../build/moc_QMsgBox.o
DIST          = /usr/local/Qt4.5/mkspecs/common/unix.conf \
		/usr/local/Qt4.5/mkspecs/common/mac.conf \
		/usr/local/Qt4.5/mkspecs/common/mac-g++.conf \
		/usr/local/Qt4.5/mkspecs/qconfig.pri \
		/usr/local/Qt4.5/mkspecs/features/qt_functions.prf \
		/usr/local/Qt4.5/mkspecs/features/qt_config.prf \
		/usr/local/Qt4.5/mkspecs/features/exclusive_builds.prf \
		/usr/local/Qt4.5/mkspecs/features/default_pre.prf \
		/usr/local/Qt4.5/mkspecs/features/mac/default_pre.prf \
		../common.pri \
		/usr/local/Qt4.5/mkspecs/features/release.prf \
		/usr/local/Qt4.5/mkspecs/features/default_post.prf \
		/usr/local/Qt4.5/mkspecs/features/mac/default_post.prf \
		/usr/local/Qt4.5/mkspecs/features/mac/objective_c.prf \
		/usr/local/Qt4.5/mkspecs/features/staticlib.prf \
		/usr/local/Qt4.5/mkspecs/features/static.prf \
		/usr/local/Qt4.5/mkspecs/features/warn_on.prf \
		/usr/local/Qt4.5/mkspecs/features/qt.prf \
		/usr/local/Qt4.5/mkspecs/features/unix/opengl.prf \
		/usr/local/Qt4.5/mkspecs/features/unix/thread.prf \
		/usr/local/Qt4.5/mkspecs/features/moc.prf \
		/usr/local/Qt4.5/mkspecs/features/mac/rez.prf \
		/usr/local/Qt4.5/mkspecs/features/mac/sdk.prf \
		/usr/local/Qt4.5/mkspecs/features/resources.prf \
		/usr/local/Qt4.5/mkspecs/features/uic.prf \
		/usr/local/Qt4.5/mkspecs/features/yacc.prf \
		/usr/local/Qt4.5/mkspecs/features/lex.prf \
		Util.pro
QMAKE_TARGET  = Util
DESTDIR       = ../../build/
TARGET        = libUtil.a

####### Custom Compiler Variables
QMAKE_COMP_QMAKE_OBJECTIVE_CFLAGS = -pipe \
		-Os \
		-Wall \
		-W


first: all
####### Implicit rules

.SUFFIXES: .o .c .cpp .cc .cxx .C

.cpp.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.cc.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.cxx.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.C.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o "$@" "$<"

.c.o:
	$(CC) -c $(CFLAGS) $(INCPATH) -o "$@" "$<"

####### Build rules

all: Makefile ../../build/$(TARGET) 

staticlib: ../../build/$(TARGET)

../../build/$(TARGET):  $(OBJECTS) $(OBJCOMP) 
	@$(CHK_DIR_EXISTS) ../../build/ || $(MKDIR) ../../build/ 
	-$(DEL_FILE) $(TARGET)
	$(AR) $(TARGET) $(OBJECTS)
	$(RANLIB) $(TARGET)
	-$(DEL_FILE) ../../build/$(TARGET)
	-$(MOVE) $(TARGET) ../../build/


Makefile: Util.pro  /usr/local/Qt4.5/mkspecs/macx-g++/qmake.conf /usr/local/Qt4.5/mkspecs/common/unix.conf \
		/usr/local/Qt4.5/mkspecs/common/mac.conf \
		/usr/local/Qt4.5/mkspecs/common/mac-g++.conf \
		/usr/local/Qt4.5/mkspecs/qconfig.pri \
		/usr/local/Qt4.5/mkspecs/features/qt_functions.prf \
		/usr/local/Qt4.5/mkspecs/features/qt_config.prf \
		/usr/local/Qt4.5/mkspecs/features/exclusive_builds.prf \
		/usr/local/Qt4.5/mkspecs/features/default_pre.prf \
		/usr/local/Qt4.5/mkspecs/features/mac/default_pre.prf \
		../common.pri \
		/usr/local/Qt4.5/mkspecs/features/release.prf \
		/usr/local/Qt4.5/mkspecs/features/default_post.prf \
		/usr/local/Qt4.5/mkspecs/features/mac/default_post.prf \
		/usr/local/Qt4.5/mkspecs/features/mac/objective_c.prf \
		/usr/local/Qt4.5/mkspecs/features/staticlib.prf \
		/usr/local/Qt4.5/mkspecs/features/static.prf \
		/usr/local/Qt4.5/mkspecs/features/warn_on.prf \
		/usr/local/Qt4.5/mkspecs/features/qt.prf \
		/usr/local/Qt4.5/mkspecs/features/unix/opengl.prf \
		/usr/local/Qt4.5/mkspecs/features/unix/thread.prf \
		/usr/local/Qt4.5/mkspecs/features/moc.prf \
		/usr/local/Qt4.5/mkspecs/features/mac/rez.prf \
		/usr/local/Qt4.5/mkspecs/features/mac/sdk.prf \
		/usr/local/Qt4.5/mkspecs/features/resources.prf \
		/usr/local/Qt4.5/mkspecs/features/uic.prf \
		/usr/local/Qt4.5/mkspecs/features/yacc.prf \
		/usr/local/Qt4.5/mkspecs/features/lex.prf \
		/Library/Frameworks/QtXml.framework/QtXml.prl \
		/Library/Frameworks/QtCore.framework/QtCore.prl \
		/Library/Frameworks/QtOpenGL.framework/QtOpenGL.prl \
		/Library/Frameworks/QtGui.framework/QtGui.prl
	$(QMAKE) -spec /usr/local/Qt4.5/mkspecs/macx-g++ -macx -o Makefile Util.pro
/usr/local/Qt4.5/mkspecs/common/unix.conf:
/usr/local/Qt4.5/mkspecs/common/mac.conf:
/usr/local/Qt4.5/mkspecs/common/mac-g++.conf:
/usr/local/Qt4.5/mkspecs/qconfig.pri:
/usr/local/Qt4.5/mkspecs/features/qt_functions.prf:
/usr/local/Qt4.5/mkspecs/features/qt_config.prf:
/usr/local/Qt4.5/mkspecs/features/exclusive_builds.prf:
/usr/local/Qt4.5/mkspecs/features/default_pre.prf:
/usr/local/Qt4.5/mkspecs/features/mac/default_pre.prf:
../common.pri:
/usr/local/Qt4.5/mkspecs/features/release.prf:
/usr/local/Qt4.5/mkspecs/features/default_post.prf:
/usr/local/Qt4.5/mkspecs/features/mac/default_post.prf:
/usr/local/Qt4.5/mkspecs/features/mac/objective_c.prf:
/usr/local/Qt4.5/mkspecs/features/staticlib.prf:
/usr/local/Qt4.5/mkspecs/features/static.prf:
/usr/local/Qt4.5/mkspecs/features/warn_on.prf:
/usr/local/Qt4.5/mkspecs/features/qt.prf:
/usr/local/Qt4.5/mkspecs/features/unix/opengl.prf:
/usr/local/Qt4.5/mkspecs/features/unix/thread.prf:
/usr/local/Qt4.5/mkspecs/features/moc.prf:
/usr/local/Qt4.5/mkspecs/features/mac/rez.prf:
/usr/local/Qt4.5/mkspecs/features/mac/sdk.prf:
/usr/local/Qt4.5/mkspecs/features/resources.prf:
/usr/local/Qt4.5/mkspecs/features/uic.prf:
/usr/local/Qt4.5/mkspecs/features/yacc.prf:
/usr/local/Qt4.5/mkspecs/features/lex.prf:
/Library/Frameworks/QtXml.framework/QtXml.prl:
/Library/Frameworks/QtCore.framework/QtCore.prl:
/Library/Frameworks/QtOpenGL.framework/QtOpenGL.prl:
/Library/Frameworks/QtGui.framework/QtGui.prl:
qmake:  FORCE
	@$(QMAKE) -spec /usr/local/Qt4.5/mkspecs/macx-g++ -macx -o Makefile Util.pro

dist: 
	@$(CHK_DIR_EXISTS) ../../build/Util1.0.0 || $(MKDIR) ../../build/Util1.0.0 
	$(COPY_FILE) --parents $(SOURCES) $(DIST) ../../build/Util1.0.0/ && $(COPY_FILE) --parents Align.h Constants.h EulerAngles.h Function.h Matrix.h Numerical.h OpenGL.h Preferences.h qcprot.h ScanDirectory.h SetButtonColor.h Task.h QMsgBox.h QSLogDest.h QsLog.h QsDebugOutput.h QsLogLevel.h ../../build/Util1.0.0/ && $(COPY_FILE) --parents Align.C EulerAngles.C Function.C Matrix.C Preferences.C qcprot.C ScanDirectory.C SetButtonColor.C Task.C QMsgBox.C QsLogDest.C QsLog.C QsDebugOutput.C ../../build/Util1.0.0/ && (cd `dirname ../../build/Util1.0.0` && $(TAR) Util1.0.0.tar Util1.0.0 && $(COMPRESS) Util1.0.0.tar) && $(MOVE) `dirname ../../build/Util1.0.0`/Util1.0.0.tar.gz . && $(DEL_FILE) -r ../../build/Util1.0.0


clean:compiler_clean 
	-$(DEL_FILE) $(OBJECTS)
	-$(DEL_FILE) *~ core *.core


####### Sub-libraries

distclean: clean
	-$(DEL_FILE) $(TARGET) 
	-$(DEL_FILE) Makefile


mocclean: compiler_moc_header_clean compiler_moc_source_clean

mocables: compiler_moc_header_make_all compiler_moc_source_make_all

compiler_objective_c_make_all:
compiler_objective_c_clean:
compiler_moc_header_make_all: ../../build/moc_Task.cpp ../../build/moc_QMsgBox.cpp
compiler_moc_header_clean:
	-$(DEL_FILE) ../../build/moc_Task.cpp ../../build/moc_QMsgBox.cpp
../../build/moc_Task.cpp: Task.h
	/Developer/Tools/Qt/moc $(DEFINES) $(INCPATH) -D__APPLE__ -D__GNUC__ Task.h -o ../../build/moc_Task.cpp

../../build/moc_QMsgBox.cpp: QMsgBox.h
	/Developer/Tools/Qt/moc $(DEFINES) $(INCPATH) -D__APPLE__ -D__GNUC__ QMsgBox.h -o ../../build/moc_QMsgBox.cpp

compiler_rcc_make_all:
compiler_rcc_clean:
compiler_image_collection_make_all: qmake_image_collection.cpp
compiler_image_collection_clean:
	-$(DEL_FILE) qmake_image_collection.cpp
compiler_moc_source_make_all:
compiler_moc_source_clean:
compiler_rez_source_make_all:
compiler_rez_source_clean:
compiler_uic_make_all:
compiler_uic_clean:
compiler_yacc_decl_make_all:
compiler_yacc_decl_clean:
compiler_yacc_impl_make_all:
compiler_yacc_impl_clean:
compiler_lex_make_all:
compiler_lex_clean:
compiler_clean: compiler_moc_header_clean 

####### Compile

../../build/Align.o: Align.C Align.h \
		qcprot.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o ../../build/Align.o Align.C

../../build/EulerAngles.o: EulerAngles.C EulerAngles.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o ../../build/EulerAngles.o EulerAngles.C

../../build/Function.o: Function.C Function.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o ../../build/Function.o Function.C

../../build/Matrix.o: Matrix.C Matrix.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o ../../build/Matrix.o Matrix.C

../../build/Preferences.o: Preferences.C Preferences.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o ../../build/Preferences.o Preferences.C

../../build/qcprot.o: qcprot.C qcprot.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o ../../build/qcprot.o qcprot.C

../../build/ScanDirectory.o: ScanDirectory.C ScanDirectory.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o ../../build/ScanDirectory.o ScanDirectory.C

../../build/SetButtonColor.o: SetButtonColor.C SetButtonColor.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o ../../build/SetButtonColor.o SetButtonColor.C

../../build/Task.o: Task.C Task.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o ../../build/Task.o Task.C

../../build/QMsgBox.o: QMsgBox.C QMsgBox.h \
		QsLog.h \
		QsLogLevel.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o ../../build/QMsgBox.o QMsgBox.C

../../build/QsLogDest.o: QsLogDest.C QsLogDest.h \
		QsLogLevel.h \
		QsDebugOutput.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o ../../build/QsLogDest.o QsLogDest.C

../../build/QsLog.o: QsLog.C QsLog.h \
		QsLogLevel.h \
		QsLogDest.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o ../../build/QsLog.o QsLog.C

../../build/QsDebugOutput.o: QsDebugOutput.C QsDebugOutput.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o ../../build/QsDebugOutput.o QsDebugOutput.C

../../build/moc_Task.o: ../../build/moc_Task.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o ../../build/moc_Task.o ../../build/moc_Task.cpp

../../build/moc_QMsgBox.o: ../../build/moc_QMsgBox.cpp 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o ../../build/moc_QMsgBox.o ../../build/moc_QMsgBox.cpp

####### Install

install:   FORCE

uninstall:   FORCE

FORCE:

