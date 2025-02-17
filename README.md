# In Class Problem Set 3

I used ComboBoxDemo.java a few years ago.  It used to compile cleanly.  Even though the code has not changed, it now  will not compile without throwing warnings.

Doing everything from a command prompt or Git Bash (no IDEs allowed), your mission is to debug the code and find out why it stopped compiling cleanly.  When you have figured it out,  note what you changed and why it stopped working in the README.md file.

Gavin Clark, Zhuoxi Tan

**Changes to code**
Added a <String> type to the jComboBox constructor and when it was initialized.

**What caused it to stop working?**
It was constructed and initailized as a raw type
