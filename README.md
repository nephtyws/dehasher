Using Python3.4 and PyQt5.

# Dehasher

- Automatically identify the different types of hash (Currently only support identify)
- Please let me know if you find a bug or issue! (Mail me or use issues on this repository!)
- ninl123@naver.com

# Future goals

- Decrypt (If it is possible)
- Online decrypt (Like MD5, get result from online rainbow table for one-way hash functions)
- Multiple decryption (Done!)
- Support CUI
- Machine learning for better result (Remove duplicated case)
- Apply algorithm to select meaningful word or string
- Reduce size of program
- Include file description (Resources)
- Support bitcoin?

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

<img align="right" src="http://opensource.org/trademarks/opensource/OSI-Approved-License-100x137.png">
The MIT License <a href="https://opensource.org/licenses/MIT">(MIT)</a>
<br>Copyright © 2016 <a href="https://github.com/NephtywS">Woongseok Kang</a>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
