# fixana
Fixes Katakana and Hiragana in Unicode Private Use Area

The font MingLiU_HKSCS uses some Unicode Private Use Area for Katakana and Hiragana. (F6F6 - F79F) This is not commonly used so when copying the text and pasting somewhere else (with other fonts), the text cannot be displayed properly.

This little script correct them to normal Unicode range. (3040 - 30ff)

# fixana
修正因錯誤使用 Unicode 而無法顯示的日文平假名和片假名

細明體_HKSCS 使用了 Unicode 專用區來表示日文平假名和片假名。(F6F6 - F79F) 這並不是通用的 Unicode 區域，因此在別的字型無法正確顯示，例如導致複製貼上時變成亂碼的情況。

這段小程式把這些錯誤的文字修正為一般使用的 Unicode 區域 (3040 - 30ff)
