FROM agrigorev/model-2024-hairstyle:v3

RUN pip install numpy==1.23.1
RUN pip install pillow
RUN pip install --no-deps https://github.com/alexeygrigorev/tflite-aws-lambda/raw/main/tflite/tflite_runtime-2.14.0-cp310-cp310-linux_x86_64.whl

CMD ["/bin/bash"]