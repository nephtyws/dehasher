Using Python3.4 and PyQt5.

# Dehasher (Hash identifier)

- Automatically identify different types of hash (Currently only support identify)
- Please let me know if you find a bug or issue! (Mail me or use issues on this repository!)
- ninl123@naver.com

# Future goals

- Decrypt (If it is possible)
- Online decrypt (Like MD5, get result from online rainbow table for one-way hash functions)
- Multiple decryption (Done!)
- Support CUI
- Machine learning for better result (Remove duplicated cases)
- Apply algorithm to select meaningful word or string
- Reduce size of program
- Include file description (Resources)
- Support Bitcoin?

# Version history

- 2. 29. 2016
  - Initial release (1.0)
  - Support Mac, Windows and Linux.
  - Support single dehash (for detail result) and multiple dehash from file (*.txt, line by line)

# Known issue

- 1.0
  - CUI Support is complete, but not being applied because of PyInstaller's --noconsole option.<br> with --noconsole option, program results won't show in the command line.<br>I've working on it, but it is so hard for me.
  - Program size is too big since UPX does not support Mac (64bit) and Linux (64bit) platform, It is difficult to solve.

# License

<img align="right" src="http://www.gnu.org/graphics/gplv3-127x51.png">
The GPLv3 License <a href="https://opensource.org/licenses/GPL-3.0">(GPLv3)</a>
<br>Copyright © 2016 <a href="https://github.com/NephtywS">Woongseok Kang</a>
