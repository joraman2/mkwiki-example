FROM rockylinux:8

RUN dnf install python2 -y
RUN pip2 install mkdocs

WORKDIR /root/docs

# Start development server by default
ENTRYPOINT ["mkdocs"]
CMD ["serve", "--dev-addr=0.0.0.0:8000"]