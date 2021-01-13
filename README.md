## STT : 48

## 1712761 Trần Đức Thắng

## 1712710 Lê Quang Quí

# 1. Giới thiệu đề tài
Hiện nay việc điện thoại là vật dụng tất yếu của cuộc sống. Nhưng nó rất đa dạng mặt hàng nên khi chúng ta chọn mua hàng trên thế giới di dộng thì liệu chúng ta có an tâm về sản phẩm đó có đúng chất lượng như họ đã quảng cáo không ? Chúng ta không thể đọc hết tất cả bình luận để đánh giá sản phẩm được. Từ ý tưởng đó , mình tạo ra 1 hệ thống sử dụng AI ( trí tuệ nhân tạo ) để đánh giá sản phẩm dựa trên bình luận.Từ đó sẽ đưa ra gợi ý cho người dùng có nên mua sản phẩm đó hay không ? , thống kê các bình luận tiêu cực,....

# 2. Môi trường cài đặt 
- Install jupyter notebook :
+ Use conda : conda install -c conda-forge jupyterlab
+ Use pip   : pip install jupyterlab
+ pip install underthesea

# 3. hướng dẫn
- create envs skin : conda create -n review python==3.7
- activate skin :   source activate review

# 4. chạy model
- craw dữ liệu từ web thegioididong.com
  - craw-data.ipynb
- train và dự đoán kết quả
  - train_predict.ipynb

# 5. Tài liệu tham khảo

- Tham khảo các tài liệu từ các notebook có sẳn trên Kaggle

- https://gate.ac.uk/sale/nle-svm/svm-ie.pdf

- http://aurelieherbelot.net/resources/slides/teaching/SVMs.pdf
