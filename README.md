# Semantic-Book-Recommender
Model được xây dựng trên colab xong kéo về đây dùng chứ không build trực tiếp trên máy có đường link hướng dẫn build là : https://colab.research.google.com/drive/14B2fZ2SIXKNgtMd43sGCmCVC3pD5RYFj?usp=drive_link

Bước 1: Dùng pd làm sạch dữ liệu null hoặc feature không cần thiết

Bước 2: Dùng langchain để xử lí phần vectodatabase(chia đoạn,học theo ngữ nghĩ,embedding)

Bước 3: Tính độ tương đồng của query và dataset chọn top_k = 10

Bước 4: Xét độ tưởng đồng của sách với nhau khi click và show ra

Bước 5: Deploy với gradio
<img width="1896" height="915" alt="image" src="https://github.com/user-attachments/assets/809b77a6-f3a9-4bfa-88b9-b2dfc5bcf767" />
<img width="1825" height="609" alt="image" src="https://github.com/user-attachments/assets/d618ea4b-e0df-4176-805d-3b3d39e2c010" />

