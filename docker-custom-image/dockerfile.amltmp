FROM public.ecr.aws/lambda/python:3.7.2022.09.08.17

COPY requirements.txt ./
RUN pip install --upgrade pip ipython ipykernel
RUN pip3 install -r requirements.txt
CMD python -m ipykernel_launcher -f $DOCKERNEL_CONNECTION_FILE