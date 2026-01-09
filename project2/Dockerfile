FROM python:3.12-slim-bookworm
WORKDIR /streamlitapp2
COPY requirements.txt ./ 
RUN pip install -r requirements.txt 
COPY data_process_db.py ./
EXPOSE 8501 
CMD ["streamlit", "run", "data_process_db.py"]