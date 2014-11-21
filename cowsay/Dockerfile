#  ________________________________________
# / The infamous cowsay dockerfile         \
# \ For production use only.               /
#  ----------------------------------------
#         \   ^__^
#          \  (oo)\_______
#             (__)\       )\/\
#                 ||----w |
#                 ||     ||
FROM fedora:latest
MAINTAINER Doug Smith <info@laboratoryb.org>

#bowline tag 1.0
RUN yum install -y cowsay fortune
RUN echo "Vermont is awesome" | cowsay
ENV AUTOBUILD_UNIXTIME
