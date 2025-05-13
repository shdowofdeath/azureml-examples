#FROM mcr.microsoft.com/azureml/openmpi4.1.0-ubuntu20.04
FROM python:3.12.10

# python installs
COPY requirements.txt .
RUN pip install -r requirements.txt && rm requirements.txt

# set command
CMD ["bash"]
