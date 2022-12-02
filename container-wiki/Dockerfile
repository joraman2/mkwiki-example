FROM rockylinux:8

RUN dnf install python3 python3-pip -y
RUN pip install mkdocs

WORKDIR /root/docs

# Start development server by default
ENTRYPOINT ["mkdocs"]
CMD ["serve", "--dev-addr=0.0.0.0:8000"]
