<파이썬 가상환경 작업 디렉토리>

cd C:\Users\HICT\Documents\Python Environment\VE\TF
Scripts\activate
jupyter notebook


<텐서보드 실행 순서>

1. 가상환경 activate
2. 
python
import tensorflow as tf
exit()

3. log가 포함된 디렉토리로 이동 
   (i.e. cd Hands on ML)

4. tensorboard --logdir=
   (file_writer 디렉토리, i.e.tf_logs )

5. 브라우저에서 http://localhost:6006/
