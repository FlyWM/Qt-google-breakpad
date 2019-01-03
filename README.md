# Qt-google-breakpad
Qt中使用google的brekapad
主要参考： https://github.com/JPNaude/dev_notes/wiki/Using-Google-Breakpad-with-Qt
# 使用方法：
  1. pro文件中包含QtBreakpad.pri。
  2. 调用Breakpad::CrashHandler::instance()->Init(path)。
  
  具体注意事项还请关注原作者：https://github.com/JPNaude/dev_notes/wiki/Using-Google-Breakpad-with-Qt
