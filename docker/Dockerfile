FROM pytorch/pytorch:latest
WORKDIR /app
COPY . .
RUN pip install jupyter ipykernel
CMD ["jupyter", "notebook", "--ip=0.0.0.0", "--allow-root"]
