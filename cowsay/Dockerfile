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

#bowline tag 1.1
RUN yum install -y cowsay 1> /dev/null
ENV AUTOBUILD_UNIXTIME
RUN echo "Vermont is awesome" | cowsay -s
