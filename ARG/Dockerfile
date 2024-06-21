# ARG version
# FROM almalinux:${version:-8}
#RUN cat /etc/*release


#### we can use --build-arg during run time

# ARG version
# FROM almalinux:${version:-8}
# #RUN cat /etc/*release
# ARG NAME
# ARG COURSE
# RUN echo "name is:  ${NAME}, COURSE is: ${COURSE}"
# CMD ["sleep", "100"]

#### we can give directly
# ARG version
# FROM almalinux:${version:-8}
# #RUN cat /etc/*release
# ARG NAME=sravani
# ARG COURSE=devops
# RUN echo "name is:  ${NAME}, COURSE is: ${COURSE}"
# CMD ["sleep", "100"]

ARG version
FROM almalinux:${version:-8}
#RUN cat /etc/*release
ARG NAME=sravani
ARG COURSE=devops
ENV DURATION=120hrs
RUN echo "name is:  ${NAME}, COURSE is: ${COURSE}, duration is: ${DURATION}"
CMD ["sleep", "100"]