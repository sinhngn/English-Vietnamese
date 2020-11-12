# English Vietnamese
Corpus English Vietnamese from OpenSubtitle_v2018 (http://opus.nlpl.eu/index.php)

Trong Corpus này bao gồm dữ liệu từ OpenSubtitle_v2018 và dữ liệu đã xử lý lại (OpenSubtitles_v2018_Context)

### OpenSubtitles_v2018_Context 
(https://drive.google.com/drive/folders/17Sw_zXANv9vI2QlDeBzkClSjJUOfg-NE?usp=sharing)
* en_second.txt và vi_second.txt là dữ liệu đã thêm Giây bắt đầu (startSecond), giây kết thúc (endSecond), câu (text). Cấu trúc file với thứ tự như sau:
        startSecond <> endSecond <> text

* en_context_source.txt và vi_context_source.txt là dữ liệu ghép theo context cách nhau bởi <BOS>, các câu cách nhau dưới 5s sẽ được nhập chung với nhau, với thứ tự câu [context <BOS> source]
  
* en_anaphoric.txt và vi_anaphoric.txt là dữ liệu được chọn lại theo các câu source có chứa các từ anaphoric
