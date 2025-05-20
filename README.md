# Image-Caption
model generate describe from image 
# Image Captioning using CNN + LSTM with Attention

## Giới thiệu
Project này xây dựng một mô hình học sâu (Deep Learning) để tự động tạo chú thích (caption) cho hình ảnh. Mô hình sử dụng kiến trúc kết hợp giữa mạng CNN (InceptionV3 hoặc ResNet50) để trích xuất đặc trưng ảnh và mạng LSTM có cơ chế Attention để tạo ra câu mô tả phù hợp.
## Công nghệ và thư viện sử dụng
- Python 3.x
- TensorFlow / Keras
- NumPy, Pandas
- Matplotlib, Seaborn
- nltk (BLEU score)
- Pillow
- tqdm
## Data
- Dữ liệu sử dụng là bộ Flickr30k, gồm ảnh và các caption mô tả ảnh.
- Link kaggle: https://www.kaggle.com/datasets/eeshawn/flickr30k
- weight and tokenizer : https://www.kaggle.com/datasets/nguynchiuvn/weight-flick30k

## Model cho kết quả tốt hơn CNN + LSTM như thông thường
![image](https://github.com/user-attachments/assets/479767b1-10ea-4e47-886d-cf6a1622a69b)

## Kết quả demo
![image](https://github.com/user-attachments/assets/6fdda1ba-74be-4b8f-aee3-736ff9ba2443)

## Đánh giá
![image](https://github.com/user-attachments/assets/22727a06-1ec4-45a6-95be-ccd7eaad8764)
