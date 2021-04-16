# Nyquyst-frequency-Aliasing-undersampling-in-digital-signal

## In signal processing: Nyquyst frequency: Fs > Fnyquyst = 2*fmax

https://jackschaedler.github.io/circles-sines-signals/sampling.html

Recall for a moment the section on sound and perception. In that section we mentioned that the range of human hearing runs from about 20 Hz to 20,000 Hz. Since humans can’t actually hear frequency content above 20,000 Hz, frequencies above this limit are actively removed from most audio and music signals before they are sampled. Given what we now know about the Sampling Theorem, you won’t be surprised to hear that the most common sampling rate for audio and music signals is around 40,000 Hz, or twice the highest audible frequency.2

https://jackschaedler.github.io/circles-sines-signals/sampling2.html

## In video processing: Hieu ung banh xe ngua (Wagon-wheel effect): FPS: frames per second 

Hiện tượng kỳ lạ này đã được khoa học đặt tên hẳn hoi: Hiệu ứng bánh xe ngựa, và nó là một ảo ảnh thị giác.

Về cơ bản, hiện tượng này bắt nguồn từ việc não bộ không thể nhận ra những hình ảnh liên tiếp nhau, vì con người không thể quan sát tất cả mọi thời điểm của một chuyển động. Cụ thể hơn, chúng ta chỉ có thể thu được 10 - 12 hình ảnh mỗi giây mà thôi. (24 hinh/s: so luong samples trong film anh)

Các nghiên cứu trước kia chỉ ra rằng não bộ có thể thu được số khung hình lên tới 200 hình/giây (FPS). Tuy nhiên trong chuyển động, con số hạ xuống 13 hình. Và dù mắt chúng ta có thể thu được hình ảnh ở tốc độ cao, thậm chí là rất cao, nhưng não lại không thể xử lý toàn bộ số ảnh đó, mà chỉ được khoảng 10 - 15 FPS.

Vậy số ảnh còn lại thì làm thế nào? Não bộ đơn giản chỉ "điền vào chỗ trống". Với trường hợp của bánh xe, não sẽ lấy ngẫu nhiên một vài hình ảnh trong chuyển động, và đó là lý do vì sao bạn nhìn thấy bánh xe đứng yên, hoặc quay chậm, hoặc thậm chí là quay ngược lại so với chiều di chuyển.



