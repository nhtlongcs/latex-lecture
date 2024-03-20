# Giáo trình LaTeX: Hướng dẫn tự học

*A vietnamese version of the LaTeX tutorial for beginners.*

--- 

Cung cấp hướng dẫn cơ bản về LaTeX để viết tài liệu học thuật. Phù hợp cho người mới bắt đầu muốn tự học LaTeX.

---


## Kết quả kì vọng

* Tạo tài liệu LaTeX cơ bản.
* Cấu trúc bài giảng với các phần, mục.
* Chèn công thức và hình ảnh.
* Thêm bài tập và giải đáp.

**Lưu ý:**
Để học tốt, các bạn cần ghi nhớ
- Thực hành là chìa khóa để thành thạo LaTeX.
- Có rất nhiều tài nguyên trực tuyến giúp bạn tìm hiểu các tính năng nâng cao.
- Đừng ngại thử nghiệm và khám phá các chức năng khác nhau.

Hướng dẫn này cung cấp điểm khởi đầu cho hành trình LaTeX của bạn. Với sự, bạn sẽ nhanh chóng tạo ra các bài viết học thuật chuyên nghiệp

## Yêu cầu phần mềm:

* Trình soạn thảo LaTeX (ví dụ: Texmaker, Overleaf)
* Trình đọc PDF (ví dụ: Adobe Acrobat Reader)
* Docker (tùy chọn, để biên dịch LaTeX trong môi trường cục bộ)

## Cấu trúc giáo trình:

* Giới thiệu sơ lược về LaTeX và lợi ích khi sử dụng cho giáo trình.
* Chi tiết slide có sẵn trong thư mục `slide`.

**Ví dụ về Latex:**

```latex
\documentclass[beamer]{theme}  % Thay thế "theme" bằng giao diện bạn chọn

\title{Giới thiệu về LaTeX}
\author{Tên của bạn}
\date{\today}
\begin{frame}
  \maketitle

  \begin{block}{LaTeX là gì?}
    LaTeX là hệ thống soạn thảo tài liệu mạnh mẽ giúp tạo ra đầu ra typographic chất lượng cao.
  \end{block}

  \begin{block}{Lợi ích của LaTeX cho giáo trình}
    \begin{itemize}
      <item>Định dạng chuyên nghiệp và nhất quán</item>
      <item>Dễ dàng tích hợp công thức và hình ảnh</item>
      <item>Mẫu và kiểu định dạng có thể tái sử dụng</item>
    \end{itemize}
  \end{block}
\end{frame}
```

## Danh sách bài tập

**Lưu ý:**

* Các bài tập được sắp xếp theo thứ tự từ cơ bản đến nâng cao.
* Bạn có thể sử dụng kết quả của bài tập trước để làm bài tập sau.
* Tham khảo các file PDF được cung cấp để biết kết quả mong muốn.
* 
### Bài tập 1:

**Biên dịch tài liệu đơn giản:** Làm quen với giao diện soạn thảo LaTeX cơ bản. Tạo tài liệu với tên và một đoạn văn ngắn giới thiệu về bản thân.

**Yêu cầu:**

* Tạo tài liệu định dạng `article`.
* In ra dòng chữ "hello world".
* Xuất kết quả sang định dạng PDF.

**Tham khảo:** [exercise01.pdf](problemset/exercise01.pdf) - [solution](problemset/solutions/1.tex)

### Bài tập 2:

**Mục tiêu:** Sử dụng tiếng Việt trong LaTeX và định dạng kiểu chữ cơ bản.

**Yêu cầu:**

* Sử dụng tiếng Việt trong tài liệu.
* Định dạng kiểu chữ (đậm, nghiêng, ...).

**Tham khảo:** [exercise02.pdf](problemset/exercise02.pdf) - [solution](problemset/solutions/2.tex)

### Bài tập 3:

**Mục tiêu:** Định dạng tài liệu dạng `article` và sử dụng thông tin cá nhân.

**Yêu cầu:**

* Thay đổi thông tin cá nhân.
* Cài đặt ngày tạo tệp là 26/7/2021.
* Đặt tiêu đề tài liệu là "Pima2021".

**Tham khảo:** [exercise03.pdf](problemset/exercise03.pdf) - [solution](problemset/solutions/3.tex)

### Bài tập 4:

**Mục và tiểu mục:** Chia bài viết thành các mục và tiểu mục với tiêu đề rõ ràng. Sử dụng `section` và `subsection` để chia cấu trúc chương, tạo mục lục và gõ công thức toán.

**Yêu cầu:**

* Chia tài liệu thành các phần, mục.
* Tạo mục lục.
* Gõ công thức hàm mật độ xác suất của phân phối Gaussian.

**Tham khảo:** [exercise04.pdf](problemset/exercise04.pdf) - [solution](problemset/solutions/4.tex)

### Bài tập 5:

**Mục tiêu:** Sử dụng kỹ thuật `cross-reference` để tham chiếu đến công thức toán.

**Yêu cầu:**

* Tham chiếu đến công thức đã viết trước đó.

**Tham khảo:** [exercise05.pdf](problemset/exercise05.pdf) - [solution](problemset/solutions/5.tex)

### Bài tập 6:

**Mục tiêu:** Tạo bảng trong tài liệu.

**Yêu cầu:**

* Tạo một bảng đơn giản.

**Tham khảo:** [exercise06.pdf](problemset/exercise06.pdf) - [solution](problemset/solutions/6.tex)

### Bài tập 7:

**Mục tiêu:** Hiển thị bảng có kích thước lớn hơn trang văn bản.

**Yêu cầu:**

* Xuống dòng tại từng ô trong bảng.

**Tham khảo:** [exercise07.pdf](problemset/exercise07.pdf) - [solution](problemset/solutions/7.tex)

### Bài tập 8:

**Hình ảnh:** Thêm hình ảnh (ví dụ: PNG, PDF, vv) liên quan đến tài liệu.

**Yêu cầu:**

* Chèn hình ảnh vào một dòng.
* Sử dụng tỉ lệ hình tương đối với `textwidth`.
* Đặt hình ảnh tại vị trí chỉ định.

**Tham khảo:** [exercise08.pdf](problemset/exercise08.pdf) - [solution](problemset/solutions/8.tex)

### Bài tập 9

**Mục tiêu:** Chèn mã nguồn vào tài liệu.

**Yêu cầu:**

* Sử dụng package `listings` để chèn một đoạn mã.

**Tham khảo:** [exercise09.pdf](problemset/exercise09.pdf) - [solution](problemset/solutions/9.tex)

### Bài tập 10

**Mục tiêu:** Làm cho mã nguồn hiển thị đẹp hơn.

**Yêu cầu:**

* Tăng khoảng cách giữa các dòng trong đoạn mã.

**Tham khảo:** [exercise10.pdf](problemset/exercise10.pdf) - [solution](problemset/solutions/10.tex)

### Bài tập 11

**Mục tiêu:** Hướng dẫn trích dẫn và danh sách tài liệu tham khảo bằng BibTeX.

**Yêu cầu:**

* Trích dẫn bài toán 2 (bài toán đồ thị) trong file `references.bib`.
* Hiển thị phần tài liệu tham khảo.

**Tham khảo:** [exercise11.pdf](problemset/exercise11.pdf) - [solution](problemset/solutions/11.tex)

## Tài Liệu Tham Khảo

Hướng Dẫn Overleaf: https://www.overleaf.com/learn/latex/Tutorials

Dự Án LaTeX: https://www.latex-project.org/

Stack Exchange: https://tex.stackexchange.com/

